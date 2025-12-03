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

<div class="project-card">
  <img src="../assets/projects/gana.png" alt="gana" class="project-image">
  <h3 class="project-title">gana</h3>
  <p class="project-description">
    Gana's vision is to allow people to bet on their motivations and form a social community along the way. Users upload selfies of themselves as the gym and AI detects whether gym environment is verified.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/TopShot.png" alt="TopShot" class="project-image">
  <h3 class="project-title">TopShot</h3>
  <p class="project-description">
    TopShot is an AI-powered app that serves as a photography tutor to beginners. It will analyze user-uploaded photos to provide feedback on technical parameters and visual composition. Novice photographers will be provided with constructive, personalized feedback to help them improve their skills.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/UpcurvEd.jpeg" alt="UpcurvEd" class="project-image">
  <h3 class="project-title">UpcurvEd</h3>
  <p class="project-description">
    Generating educational content such as animations, podcasts, quizzes to explain complex concepts in STEM using natural language.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/HistoriCam.png" alt="HistoriCam" class="project-image">
  <h3 class="project-title">HistoriCam</h3>
  <p class="project-description">
    HistoriCam is a mobile-first web application that combines computer vision, geolocation, and historical data to provide instant information about landmarks. Users can point their camera at a building or landmark, and the app will identify it and provide historical context and interesting facts.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Art3D.png" alt="Art3D" class="project-image">
  <h3 class="project-title">Art3D</h3>
  <p class="project-description">
    Tired of flat visuals? Our tool lifts any 2D drawing into a delicate 3D mesh - no modeling skills required! With a plug-and-play interface powered by a robust end-to-end AI pipeline, creators get ready-to-use 3D assets for games, avatars, animation, and even virtual assets like furniture, all in just a few clicks.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Randori.png" alt="Randori" class="project-image">
  <h3 class="project-title">Randori</h3>
  <p class="project-description">
    Randori is an autonomous AI agent that plans and executes penetration tests in controlled, containerized environments. It automates manual pentesting tasks to identify weaknesses, reducing the time and cost of traditional security testing.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/DailyDrip.png" alt="DailyDrip" class="project-image">
  <h3 class="project-title">DailyDrip</h3>
  <p class="project-description">
    Brewing coffee consistently to match individual taste preferences is difficult due to the large number of variables (beans, roast, grind size, water ratio, temperature, etc.) and subjective nature of taste. DailyDrip aims to solve this by providing a data-driven, personalized coffee assistant that recommends brewing recipes, generates visual brewing timelines, and learns from user feedback.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/DataDetox.jpg" alt="DataDetox" class="project-image">
  <h3 class="project-title">DataDetox</h3>
  <p class="project-description">
    DataDetox is an interactive AI agent orchestration system that leverages MCP, graph-based data, and cloud infrastructure to trace ML data and model provenance. Using Hugging Face model information and arXiv papers, the system traces how datasets and models connect across the AI ecosystem, helping developers identify hidden risks like copyrighted data or problematic datasets that propagate downstream.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/HERM.png" alt="HERM (Skin the Code)" class="project-image">
  <h3 class="project-title">HERM (Skin the Code)</h3>
  <p class="project-description">
    Our project builds an AI-driven skincare product recommendation system, that unifies skin analysis, contextual factors such as weather and personal schedule, and personalized product recommendations. Powered by RAG, multi-agent pipelines, and GCP infrastructure to deliver personalized, reliable suggestions based on a user's skin needs and context.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/LessHueMoreVue.jpg" alt="Less Hue, More Vue" class="project-image">
  <h3 class="project-title">Less Hue, More Vue</h3>
  <p class="project-description">
    Less Hue is a platform that allows for the transmission of photos in low bandwidth environments. We compress photos through decoloration and use a model to recolor the model. Our initial use case is for photojournalists in areas of the world with poor internet connection.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/TummyAI.png" alt="TummyAI" class="project-image">
  <h3 class="project-title">TummyAI</h3>
  <p class="project-description">
    In this project, we aim to develop an AI-powered gastrointestinal health assistant called TummyAI. The app features computer vision technology to recognize common fermentable oligo-saccharides, disaccharides, mono-saccharides, and polyols (FODMAP) foods from user-uploaded photos and classify them into low-, moderate-, or high-FODMAP categories.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/BallotHelper.png" alt="Ballot Helper" class="project-image">
  <h3 class="project-title">Ballot Helper</h3>
  <p class="project-description">
    Ballot Helper is a tool that helps Massachusetts voters discover information about local election candidates. By automatically collecting and organizing candidate information from cities across the state, it lets voters ask natural questions like "What does this candidate think about housing?" to get clear answers. The system uses an LLM and RAG to make researching local elections as simple as having a conversation.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/OptimusDose.jpg" alt="Optimus Dose" class="project-image">
  <h3 class="project-title">Optimus Dose</h3>
  <p class="project-description">
    Optimus-Dose is an intelligent diabetes management web app that delivers personalized insulin recommendations by combining blood glucose monitoring, meal tracking, AI-powered carbohydrate estimation from meal photos, and patient-specific parameters. The integrated RAG system leverages up-to-date research and clinical guidelines to provide evidence-based, explainable dosing suggestions that prioritize medical safety.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Dialogos.png" alt="Dialogos.ai" class="project-image">
  <h3 class="project-title">Dialogos.ai</h3>
  <p class="project-description">
    Dialogos AI turns your study materials into personalised flashcards and pairs you with an AI Socratic tutor that helps you truly master concepts - not just memorise answers. Upload your study materials, and our system automatically generates smart flashcards tailored to different learning levels, then guides you through practice with an intelligent tutor that asks thought-provoking questions to deepen your understanding.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/HARV.jpg" alt="HARV" class="project-image">
  <h3 class="project-title">HARV</h3>
  <p class="project-description">
    HARV (Harvard Attendance Recognition & Verification) tackles attendance fraud by combining geolocation checks and machine-learning–based ID verification of student lecture hall scans. After a quick setup at the start of the semester, it runs with virtually no ongoing effort from instructors.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/FitAI.png" alt="FitAI" class="project-image">
  <h3 class="project-title">FitAI</h3>
  <p class="project-description">
    FitAI is a containerized, end-to-end system that delivers personalized fitness recommendations powered by large language models (LLMs) and retrieval-augmented generation (RAG).
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/StyleMe.png" alt="StyleMe" class="project-image">
  <h3 class="project-title">StyleMe</h3>
  <p class="project-description">
    StyleMe is a personal AI stylist designed to turn any existing wardrobe into endless outfit ideas. It understands each clothing item and recommends combinations that match an individual's style. No more "nothing to wear" moments.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/NewsJuice.png" alt="NewsJuice" class="project-image">
  <h3 class="project-title">NewsJuice</h3>
  <p class="project-description">
    NewsJuice transforms passive news consumption into an interactive conversation with AI. Busy people ask questions about the news out loud and receive instant, personalized podcast responses from live news articles—turning commutes and multitasking time into effortless, interactive news briefings tailored to one's interests.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/FormulaOnePenaltyTool.png" alt="Formula One Penalty Tool" class="project-image">
  <h3 class="project-title">Formula One Penalty Tool</h3>
  <p class="project-description">
    This project demystifies Formula One race penalties by translating dense FIA regulations and steward reports into clear, fan-friendly explanations. Powered by AI, the system analyzes each infringement, references the exact clauses breached, and compares penalties to similar past cases to assess fairness.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Duped.png" alt="Duped" class="project-image">
  <h3 class="project-title">Duped</h3>
  <p class="project-description">
    A cosmetics dupe-finder app that finds the best low-cost alternatives while maintaining the same functionality. Snap a photo or enter a name, and Duped will find you great dupes and even check for harmful product interactions!
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/EverydayEmotions.png" alt="Everyday Emotions" class="project-image">
  <h3 class="project-title">Everyday Emotions</h3>
  <p class="project-description">
    Everyday Emotions is an AI mental health assistant designed to provide long-term emotional support. It combines mood tracking and an AI chatbot in one platform, allowing users to record their daily feelings through a calendar and receive private, instant emotional support anytime.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/SteamAppIndieLaunch.jpg" alt="Steam App Indie Launch" class="project-image">
  <h3 class="project-title">Steam App Indie Launch</h3>
  <p class="project-description">
    Our app is for everything related to publishing and operating a game on Steam, covering onboarding, store setup, pricing, release processes, sales events, community tools, and platform policies. It also documents technical integration of the Steamworks SDK and Web API, plus finance, tax, and marketing guidance.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/TarAIntino.png" alt="TarAIntino" class="project-image">
  <h3 class="project-title">TarAIntino</h3>
  <p class="project-description">
    We present TarAIntino, an end-to-end system to generate personalized movie trailers (and eventually full movies) using AI. Our core innovations lie in applying advanced preference elicitation techniques to map a user's abstract tastes onto a continuous "cinematic taste space" and orchestrating a resilient, production-grade pipeline to translate that taste into a coherent visual story.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/HopIn.png" alt="HopIn" class="project-image">
  <h3 class="project-title">HopIn</h3>
  <p class="project-description">
    Finding an affordable and suitable apartment in Boston/Cambridge is a stressful and time-consuming process. HopIn tackles the issue by centralizing the scattered information and provide personalized guidance using AI.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/LyvHealth.png" alt="Lyv Health" class="project-image">
  <h3 class="project-title">Lyv Health</h3>
  <p class="project-description">
    Lyv Health is a longevity clinic-meets-platform helping women optimize their health through personalized protocols covering nutrition, exercise, supplements, prescriptions, and peptides. We ran a beta this past summer where we saw strong traction: 100% rebooking on telehealth, $510 ARPU, and a waitlist of 5,000 people.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/FirstAidLLM.png" alt="FirstAid-LLM" class="project-image">
  <h3 class="project-title">FirstAid-LLM</h3>
  <p class="project-description">
    FirstAid-LLM transforms static medical manuals into a dynamic, hands-free assistant for urgent care. By leveraging a RAG pipeline grounded in over 130+ trusted sources (e.g., AHA, Red Cross), the system provides cited, step-by-step instructions via text or voice. This ensures laypersons and trainees can access verifiable, hallucination-free guidance for non-life-threatening emergencies instantly.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Dosewise.png" alt="Dosewise" class="project-image">
  <h3 class="project-title">Dosewise</h3>
  <p class="project-description">
    Dosewise is a drug treatment efficacy predictor. It allows healthcare professionals to monitor patients and see the effect of the drug before it is given. We use a time series model to predict the treatment effect (with drug) and the control (without the drug).
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/ABC.png" alt="ABC: AI Background Music Composer" class="project-image">
  <h3 class="project-title">ABC: AI Background Music Composer</h3>
  <p class="project-description">
    With the rapid rise of short video platforms such as TikTok and YouTube, background music has become an essential factor in shaping the atmosphere and emotional impact of video content. AI Background Music Composer provides an AI-powered solution that generates original background music directly from video input and user preference, overcoming the limitations of existing music libraries.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/NoteAIFy.png" alt="NoteAIFy" class="project-image">
  <h3 class="project-title">NoteAIFy</h3>
  <p class="project-description">
    NoteAIFy is an end-to-end, AI-powered note tutor that corrects your course notes and reinforces key concepts. With integrated data versioning to track your learning history and a RAG-enhanced retrieval system to minimize errors, every recommendation is personalized and grounded in your own materials.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/pibu.png" alt="pibu.ai" class="project-image">
  <h3 class="project-title">pibu.ai</h3>
  <p class="project-description">
    Get fast, helpful insights about your skin conditions with our secure, easy‑to‑use AI app. Upload a photo to receive general information and suggestions, track changes over time, and chat with an AI assistant—while knowing your images and data are kept private and secure.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/AlminO.jpg" alt="AlminO" class="project-image">
  <h3 class="project-title">AlminO</h3>
  <p class="project-description">
    AIMinO is an agentic AI system that enables natural-language control of multiplex imaging data, allowing users to explore, analyze, and model tissue images interactively through Napari and OMERO.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/Amicus.png" alt="AlminO" class="project-image">
  <h3 class="project-title">Amicus</h3>
  <p class="project-description">
    Amicus is an AI-powered legal copilot designed to streamline complex litigation review by organizing, analyzing, and synthesizing massive, mixed-format document corpora. It automates issue tagging, privilege detection, timeline construction, and cross-document inconsistency checks while preserving human oversight and full auditability. The system dramatically reduces review time and enhances accuracy for law firms and litigation teams.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/PredictBG.png" alt="PredictBG" class="project-image">
  <h3 class="project-title">PredictBG</h3>
  <p class="project-description">
    PredictBG is an application designed to help people with diabetes anticipate glucose changes and manage daily decisions with less stress. By combining CGM data, food-photo carbohydrate estimation, and adaptive forecasting models, the system produces actionable and understandable guidance.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/JadeEstimationAI.png" alt="Jade Estimation AI" class="project-image">
  <h3 class="project-title">Jade Estimation AI</h3>
  <p class="project-description">
    The Jade Estimator AI Platform leverages advanced AI, including computer vision and a hybrid RAG system, to provide transparent and explainable jade price estimations. It transforms opaque jade appraisal into an intuitive experience, offering objective analysis and interactive expert conversation for both consumers and professionals.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/TheConsult.jpg" alt="The Consult" class="project-image">
  <h3 class="project-title">The Consult</h3>
  <p class="project-description">
    The Consult is an AI assistant that delivers referenced, clinically sound answers for both clinicians and researchers. It pairs Gemini with retrieval over PubMed-derived content so users can see citations, study details, and configurable evidence filters.
  </p>
</div>

<div class="project-card">
  <img src="../assets/projects/InfluencerLens.png" alt="InfluencerLens" class="project-image">
  <h3 class="project-title">InfluencerLens</h3>
  <p class="project-description">
    To help brands cut through chaotic creator ecosystems and identify partners who fit their marketing goals, InfluencerLens is an AI-driven multimodal RAG platform that understands creator content, audience signals, and brand intent. It delivers transparent, high-quality influencer recommendations that enable faster, more accurate, and more strategic selections.
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