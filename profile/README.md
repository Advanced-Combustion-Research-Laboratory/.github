# Advanced Combustion Research Laboratory (ACRL)

<div align="right">
  <button onclick="switchLanguage('zh')">中文</button> | 
  <button onclick="switchLanguage('en')">English</button>
</div>

<div id="zh-content" style="display: block;">

## 组织简介

Advanced Combustion Research Laboratory (ACRL) 是一个专注于先进燃烧技术、燃烧原理及发动机相关技术研究与开发的专业科研组织。本实验室成立于2025年12月26日，致力于推动燃烧科学的前沿研究，为能源高效利用和环境保护提供创新解决方案。

## 研究领域

### 核心研究方向
1. **先进燃烧技术**
   - 高效清洁燃烧技术
   - 低排放燃烧系统
   - 新型燃料燃烧特性研究
   - 燃烧过程优化与控制

2. **燃烧基础原理**
   - 燃烧化学反应动力学
   - 湍流燃烧相互作用
   - 火焰传播与稳定性
   - 燃烧不稳定性机理

3. **发动机技术**
   - 内燃机燃烧优化
   - 燃气轮机燃烧室设计
   - 航空发动机燃烧系统
   - 新型动力装置燃烧技术

4. **交叉学科研究**
   - 燃烧与传热耦合
   - 燃烧污染物生成与控制
   - 燃烧数值模拟与实验验证
   - 燃烧系统智能化

## 研究成果

本实验室的大部分公开文件包含了组织成员的相关研究成果，主要包括：

### 学术论文
- 国际期刊发表的高水平研究论文
- 国际会议报告与论文集
- 专题研究报告与技术白皮书

### 技术成果
- 燃烧系统优化设计方案
- 新型燃烧器专利技术
- 燃烧诊断与测量技术
- 数值模拟软件与工具

### 开源项目
- 燃烧化学反应机理数据库
- 可公开的实验数据
- 燃烧数值模拟代码库
- 实验数据处理工具
- 教学与培训材料

### 更新日志
- **2025年12月26日**：实验室正式成立
- **2025年12月26日**：官方网站与文档系统建立

### 版权声明
© 2025 Advanced Combustion Research Laboratory. 保留所有权利。

</div>

<div id="en-content" style="display: none;">

## Organization Introduction

Advanced Combustion Research Laboratory (ACRL) is a professional scientific research organization focused on advanced combustion technology, combustion principles, and engine-related technology research and development. The laboratory was established on December 26, 2025, and is dedicated to advancing cutting-edge research in combustion science, providing innovative solutions for efficient energy utilization and environmental protection.

## Research Areas

### Core Research Directions
1. **Advanced Combustion Technology**
   - High-efficiency clean combustion technology
   - Low-emission combustion systems
   - Combustion characteristics of new fuels
   - Combustion process optimization and control

2. **Fundamental Combustion Principles**
   - Combustion chemical reaction kinetics
   - Turbulence-combustion interactions
   - Flame propagation and stability
   - Combustion instability mechanisms

3. **Engine Technology**
   - Internal combustion engine combustion optimization
   - Gas turbine combustor design
   - Aircraft engine combustion systems
   - New power plant combustion technology

4. **Interdisciplinary Research**
   - Combustion and heat transfer coupling
   - Combustion pollutant formation and control
   - Combustion numerical simulation and experimental validation
   - Intelligent combustion systems

## Research Achievements

Most of the laboratory's public documents contain relevant research achievements of organization members, mainly including:

### Academic Papers
- High-level research papers published in international journals
- International conference reports and proceedings
- Special research reports and technical white papers

### Technical Achievements
- Combustion system optimization design solutions
- New burner patent technologies
- Combustion diagnostics and measurement techniques
- Numerical simulation software and tools

### Open Source Projects
- Combustion chemical reaction mechanism databases
- Publicly available experimental data
- Combustion numerical simulation code libraries
- Experimental data processing tools
- Teaching and training materials

### Update Log
- **December 26, 2025**: Laboratory officially established
- **December 26, 2025**: Official website and documentation system established

### Copyright Notice
© 2025 Advanced Combustion Research Laboratory. All rights reserved.

</div>

<script>
function switchLanguage(lang) {
    const zhContent = document.getElementById('zh-content');
    const enContent = document.getElementById('en-content');
    
    if (lang === 'zh') {
        zhContent.style.display = 'block';
        enContent.style.display = 'none';
    } else if (lang === 'en') {
        zhContent.style.display = 'none';
        enContent.style.display = 'block';
    }
    
    // Update URL hash for bookmarking
    window.location.hash = lang;
    
    // Update button styles to show active state
    const buttons = document.querySelectorAll('button');
    buttons.forEach(button => {
        if (button.textContent === '中文' && lang === 'zh') {
            button.style.fontWeight = 'bold';
            button.style.color = '#007bff';
        } else if (button.textContent === 'English' && lang === 'en') {
            button.style.fontWeight = 'bold';
            button.style.color = '#007bff';
        } else {
            button.style.fontWeight = 'normal';
            button.style.color = '';
        }
    });
}

// Check URL hash on page load
window.addEventListener('DOMContentLoaded', function() {
    const hash = window.location.hash.substring(1);
    if (hash === 'zh' || hash === 'en') {
        switchLanguage(hash);
    }
});
</script>

<style>
button {
    background: none;
    border: 1px solid #ccc;
    padding: 5px 15px;
    margin: 0 5px;
    cursor: pointer;
    border-radius: 3px;
    font-size: 14px;
}

button:hover {
    background-color: #f5f5f5;
    border-color: #999;
}

button:active {
    background-color: #e5e5e5;
}
</style>
