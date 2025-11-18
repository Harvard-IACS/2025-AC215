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

<div class="project-card">
  <img src="../assets/projects/EatYourSkinOut.jpg" alt="Eat Your Skin Out" class="project-image">
  <h3 class="project-title">Eat Your Skin Out</h3>
  <p class="project-description">
    A recommendation system that uses an LLM to detect skin conditions and generate nutrient-based food suggestions tailored to personal preferences. This project is designed for individuals with skin concerns who prefer gentler, internal, and longer-term approaches to skin health.
  </p>
</div> 

<div class="project-card">
  <img src="../assets/projects/Tressure.png" alt="Tressure" class="project-image">
  <h3 class="project-title">Tressure</h3>
  <p class="project-description">
  The Tressure web/mobile app quantifies hair density and hair health over time
It is better than other existing treatments because it is more accessible (less expensive), it quantifies the difference, and it allows users to chat with app. We target tracking hair regrowth and initial time to start using hair loss products as two major applications.
  </p>
</div> 

<div class="project-card">
  <img src="../assets/projects/Evea.png" alt="Evea" class="project-image">
  <h3 class="project-title">Evea</h3>
  <p class="project-description">
  Every month, millions of women experience painful, disruptive symptoms and most are told to take birth control, antidepressants, or simply “deal with it.” We deserve better, that's why we are building digital functional health practice to help tackle PMS through lifestyle changes. We integrate wearable data, cycle tracking, and symptom logs with women's health research to give personalized insights and interventions.
  </p>
</div> 

<div class="project-card">
  <img src="../assets/projects/Avi.png" alt="Avi" class="project-image">
  <h3 class="project-title">Avi</h3>
  <p class="project-description">
    We're building a digital twin platform that helps people unlock shared context. For individuals, our platform connects data across services to unlock deeper insights, smarter recommendations, and more personalized experiences. For professionals, we build intelligent digital twins that handle the repetitive, foundational work to shift the human focus to the last mile: the unique touch that makes each client experience exceptional.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/BiteFinder.png" alt="BiteFinder" class="project-image">
  <h3 class="project-title">BiteFinder</h3>
  <p class="project-description">
    BiteFinder is an AI-powered web app that helps users identify insect bites and receive tailored treatment advice. By combining image and text analysis through a multimodal pipeline, it classifies the likely insect type and retrieves relevant medical guidance using a Retrieval-Augmented Generation (RAG) model.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/CrimsonCompass.png" alt="Crimson Compass" class="project-image">
  <h3 class="project-title">Crimson Compass</h3>
  <p class="project-description">
    Crimson Compass is an AI-powered guide to what's happening around Cambridge. Designed for Harvard students, it makes discovering local events as easy as having a conversation: just ask, "What free art events are happening this weekend?" and get personalized suggestions powered by smart search and curated data from across the city.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/CADCoderNextGen.png" alt="CAD-Coder-NextGen" class="project-image">
  <h3 class="project-title">CAD-Coder-NextGen</h3>
  <p class="project-description">
    CAD-Coder NextGen leverages LLAVA/Qwen-based LLM model to provide mechanical engineers, enthusiasts and educators with the necessary tools to make modifications to CAD images. Users upload an image file through a Chat-GPT style user interface and can get the python-query code directly from it.
  </p>
</div>

<!-- <div class="project-card">
  <img src="../assets/projects/Spatially.png" alt="Spatially" class="project-image">
  <h3 class="project-title">Spatially</h3>
  <p class="project-description">
    Spatially aims to address the housing crisis by developing a scalable pipeline for producing informative zoning-ordinance tools. Zoning ordinances—large, highly technical regulatory documents that dictate what can be built, where, and how—are difficult for property owners and small developers to navigate, and existing digital tools are limited to a few cities and generally not user-friendly. To overcome these barriers, Spatially integrates zoning ordinance text, development plans, and census-based spatial context, leveraging large language models (LLM) to extract, structure, and deliver precise, accessible zoning guidance.
  </p>
</div> -->

<div class="project-card">
  <img src="../assets/projects/Spatially.png" alt="Spatially" class="project-image">
  <h3 class="project-title">Spatially</h3>
  <p class="project-description">
    Spatially addresses the housing crisis by making complex zoning ordinances accessible to property owners and small developers. Using LLMs, it extracts and structures zoning regulations from technical documents, integrating them with development plans and spatial data to deliver clear, actionable guidance on what can be built and where.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/HarvardLoop.jpg" alt="Harvard Loop" class="project-image">
  <h3 class="project-title">Harvard Loop</h3>
  <p class="project-description">
    Harvard Loop is an AI powered lost and found app designed specifically for the Harvard community. We use LLM-powered embeddings to quickly and accurately match lost and found items.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/VibeMaps.png" alt="VibeMaps" class="project-image">
  <h3 class="project-title">VibeMaps</h3>
  <p class="project-description">
    Our project flips local discovery on its head by letting people search for vibes instead of addresses. We map the atmosphere and energy of real spaces so users can ask for what they actually want - like a cozy date spot, a high-energy workspace, or a minimalist, quiet café. The result is a way to navigate the world by feeling, not coordinates.
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