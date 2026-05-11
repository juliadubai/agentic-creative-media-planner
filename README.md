**Agentic Creative Media Planner (ACMP)**
A prototype agent that blends advertising strategy, creative intelligence, and multimodal AI.

**Overview**
The Agentic Creative Media Planner (ACMP) explores how agentic systems can transform the future of advertising. It analyzes brand briefs, generates creative concepts, produces AI‑driven music and sonic branding, infers audiences, recommends publishers, and proposes AdCP‑aligned budgets — creating a unified, intelligent planning workflow.

This project sits at the intersection of AI, advertising, creative development, and music technology, demonstrating how multimodal models and agentic reasoning can reshape how brands build and deploy campaigns.

**1. Brand Brief Analysis**
Extracts the core strategic elements of the brief:brand identity, objectives, tone & messaging, constraints, funnel stage, value propositions

**2. AI Driven Creative Generation (Optional).**
Produces the creative direction when needed: campaign concepts, messaging frameworks, scripts & copy, visual ideas, emotional toneboards, storytelling angles.
This stage can be skipped if the user already has creative assets or wants to focus on media‑first planning.

**3. AI‑Driven Music & Sonic Branding (Optional).**
Generates and evaluates sonic identity elements: music variations (Suno, Stable Audio, etc.), instrumentation & rhythm direction, emotional resonance mapping, sonic brand cues, brand‑fit scoring. 
This stage is optional and triggered only when sonic branding or audio assets are relevant to the campaign.
  
**4. Audience Intelligence**
Uses AI‑native reasoning to infer audiences: psychographics, behaviors, contextual signals, interest clusters, lookalike patterns, intent‑based segments. 

**5. Publisher Mapping.**
Recommends publishers, platforms, and formats across the full digital ecosystem, based on audience insights and creative/sonic direction. 
The agent evaluates: Display (premium web, news, lifestyle, finance, etc.), Online Video (pre‑roll, mid‑roll, outstream, instream), Native (MSN, Outlook, premium editorial placements), Connected TV (CTV) (Netflix, Roku, Tubi, Pluto, Samsung TV+, etc.), Retail Media (Amazon, Walmart, Target, Mercado Libre, etc.), Social (Meta, TikTok, YouTube, Pinterest, Snapchat, LinkedIn), Audio (Spotify, Pandora, iHeart, podcasts, streaming radio), AI Surfaces (ChatGPT, Copilot, AI assistants), Country‑Specific Publishers (LATAM: Globo, Clarin, El Tiempo, Falabella, Liverpool, etc.)

This stage outputs a structured recommendation including: best‑fit channels, rationale, format suggestions, contextual alignment, expected reach & engagement patterns, 

**Project Structure**

agentic-creative-media-planner/
│
├── agent/                     
│   ├── main_agent.py                  # Orchestrates the full pipeline
│   ├── brand_brief_analysis.py        # Stage 1
│   ├── creative_generation.py         # Stage 2 (optional)
│   ├── music_sonic_branding.py        # Stage 3 (optional)
│   ├── audience_intelligence.py       # Stage 4
│   ├── publisher_mapping.py           # Stage 5
│   ├── adcp_budgeting.py              # Stage 6
│   └── utils/
│       ├── prompt_templates.py
│       ├── brand_brief_parser.py
│       └── scoring_functions.py
│
├── workflows/                 
│   ├── brief_analysis.yaml
│   ├── creative_generation.yaml
│   ├── music_sonic_branding.yaml
│   ├── audience_intelligence.yaml
│   ├── publisher_mapping.yaml
│   ├── adcp_budgeting.yaml
│   └── full_pipeline.yaml
│
├── notebooks/                 
│   ├── audio_analysis.ipynb
│   ├── spectrogram_analysis.ipynb
│   ├── stem_comparison.ipynb
│   └── creative_scoring.ipynb
│
├── examples/                  
│   ├── brand_brief_fashion.json
│   ├── brand_brief_travel.json
│   ├── brand_brief_cpg.json
│   ├── output_fashion_campaign.md
│   ├── output_travel_campaign.md
│   └── output_cpg_campaign.md
│
├── docs/                      
│   ├── architecture_diagram.png
│   ├── pipeline_overview.png
│   ├── publisher_mapping

**Why This Project Exists**
Advertising is shifting from static planning to dynamic, agent‑driven systems. Creative is becoming multimodal. Sonic branding is becoming AI‑native. Media planning is becoming adaptive and intelligence‑driven.

**ACMP demonstrates how a single agent can unify these components into a cohesive workflow — a glimpse into the next generation of advertising tools.**

**Status**
Early prototype. Work in progress. 
Contributions, ideas, and discussions are welcome.
