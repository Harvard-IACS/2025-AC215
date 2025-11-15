---
layout: page
title: Project Showcase
description: Listing of Project Showcase Information.
nav_order: 7
---

<style>
.project-showcase {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.25rem;
  margin: 2rem 0;
}

.project-card {
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  padding: 1.25rem;
  background: white;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.07), 0 4px 14px rgba(0, 0, 0, 0.05);
  transition: transform 0.2s, box-shadow 0.2s;
  display: flex;
  flex-direction: column;
}

.project-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
}

.project-image {
  width: 180px;
  height: 180px;
  object-fit: cover;
  border-radius: 6px;
  margin-bottom: 1rem;
  background: #f6f8fa;
}

.project-title {
  font-size: 1.1rem;
  font-weight: 600;
  margin-bottom: 0.75rem;
  color: #24292e;
}

.project-description {
  font-size: 0.875rem;
  line-height: 1.5;
  color: #586069;
  flex-grow: 1;
}

/* Hide anchor links on project titles */
.project-title .anchor-heading,
.project-card .anchor-heading {
  display: none !important;
}

@media (prefers-color-scheme: dark) {
  .project-card {
    background: #1e1e1e;
    border-color: #30363d;
  }
  
  .project-title {
    color: #e6edf3;
  }
  
  .project-description {
    color: #8b949e;
  }
}

@media (max-width: 1000px) {
  .project-showcase {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 600px) {
  .project-showcase {
    grid-template-columns: 1fr;
  }
}
</style>

## AC215 Project Showcase
**December 10th 2025 - 9:00 AM - 12:00 PM**

**Projects created by AC215 students**

---

<div class="project-showcase">

<div class="project-card">
  <img src="../assets/projects/PinoutAI.png" alt="PinoutAI" class="project-image">
  <h3 class="project-title">PinoutAI</h3>
  <p class="project-description">
    An app that helps electrical engineers choose components and chat with their datasheets. PinoutAI streamlines the component selection process by providing intelligent recommendations and interactive datasheet exploration.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/TheBearDungeon.jpg" alt="AI DnD Master" class="project-image">
  <h3 class="project-title">AI DnD Master</h3>
  <p class="project-description">
    An intelligent multi-agent system designed to enhance Dungeons & Dragons gameplay. It features specialized agents that handle storytelling, combat management, and interactive interfaces to create an immersive and automated DnD experience.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/NutriSnap.png" alt="NutriSnap" class="project-image">
  <h3 class="project-title">NutriSnap</h3>
  <p class="project-description">
    NutriSnap aims to simplify the process of food tracking and nutritional analysis by replacing cumbersome manual data entry with a seamless, AI-powered system that accepts multi-modal input like photos and voice.
  </p>
</div>


<div class="project-card">
  <img src="../assets/projects/Menufesto.png" alt="Menufesto" class="project-image">
  <h3 class="project-title">Menufesto</h3>
  <p class="project-description">
    An AI-powered menu translation app designed specifically for Chinese cuisine, where literal translations often lead to confusion. Using computer vision and large language models, it provides culturally aware explanations that clarify ingredients and cooking techniques for non-native Chinese-speaking tourists.
  </p>
</div>


<div class="project-card">
  <img src="../assets/projects/FinWhiz.png" alt="FinWhiz" class="project-image">
  <h3 class="project-title">FinWhiz</h3>
  <p class="project-description">
    An AI-powered financial education assistant built for GenZ and Millennials looking to understand their personal finances. Through incorporating insights from user-uploaded documents and citing reputable financial sources, FinWhiz provides personalized financial education while avoiding risky financial advice territory.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/ERP_for_SMEs.png" alt="ERP for SMEs" class="project-image">
  <h3 class="project-title">ERP for SMEs</h3>
  <p class="project-description">
    A comprehensive ERP system specifically designed for small and medium-sized enterprises in the rice market industry. The system integrates data pipeline infrastructure with microservices architecture and Multi-Agent System to provide real-time analytics, forecasting, and intelligent querying capabilities.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/BoraBondCustomerAssistant.png" alt="BoraBond Customer Assistant" class="project-image">
  <h3 class="project-title">BoraBond Customer Assistant</h3>
  <p class="project-description">
    LLM-Powered Customer Service Assistant for BoraBond, a startup that allows US-Based Retail investors to access local-currency African government bonds. The chat system answers customer questions when context is available, and has the capability to differentiate and appropriately escalate user questions and feedback.
  </p>
</div>


<div class="project-card">
  <img src="../assets/projects/DolFar.png" alt="DolFar" class="project-image">
  <h3 class="project-title">DolFar</h3>
  <p class="project-description">
    Fighting Mental Wellbeing Crisis with AI-Powered Event Discovery. DolFar delivers psychologically-informed event recommendations in under 30 seconds using a 5-question assessment rooted in positive psychology (PERMA framework) to match users with local events that address their mental health needs.
  </p>
</div>


</div>

---
<!-- 
## Add Your Project

To add more projects, simply copy the following template and fill in your project details:

<div class="project-card">
  <img src="assets/projects/YourProjectImage.png" alt="Your Project Name" class="project-image">
  <h3 class="project-title">Your Project Name</h3>
  <p class="project-description">
    Your project description goes here. Keep it concise - 2-3 sentences that capture the essence of your project.
  </p>
</div> -->