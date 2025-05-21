This is my **public GitHub**. Most of my active projects are self-hosted on a private Gitea instance for operational security and control. *(And you can self-host too! — it's dead simple )*

## Who I Am

I'm a systems engineer and automation architect building full-stack, AI-driven workflows designed for **scale**, **stealth**, and **persistence**.

I specialize in end-to-end systems that:

- Automate human-like behavior on web and mobile (Tinder, YouTube, LinkedIn, Reddit)
- Integrate with LLMs for autonomous task handling (commenting, scraping, classification)
- Push and log structured data across Supabase, local vector stores, and REST APIs
- Leverage self-hosted infrastructure for resilience and rapid iteration

All tools, scripts, and agents are built with **operational realism** in mind — I prioritize stealth, session integrity, and human behavior emulation.

## Current Focus Areas

- **LLM Agent Systems**  
  Modular agents powered by Ollama (LLaMA 3), FastAPI backends, custom memory layers, and Telegram interfaces.  
  Tasks include: comment generation, task queues, persona simulation, and remote command control.

- **Guerrilla Marketing Pipelines**  
  Full-stack campaigns using comment bots, persona-building crawlers, and video watchers that replicate organic engagement on platforms like YouTube and Reddit.  
  Each account runs headless or inside a VM/VNC-controlled browser with strict proxy hygiene and behavior randomization.

- **YouTube & Content Intelligence Systems**  
  - Harvests recommended videos and comment threads for trend mapping  
  - Logs interactions, likes, and scraped metadata to Supabase  
  - Embeds top comments for contextual LLM input

- **Server + Automation Infra**  
  - Self-hosted Gitea (GitHub alt), Supabase, Ollama, and API services on local metal  
  - VPN overlay networks via WireGuard and Tailscale  
  - Containerized services using Docker Compose with exposed RPC endpoints

- **Reddit Video Content System**  
  Telegram-triggered automation that:
    - Accepts Reddit links → pulls top videos/comments  
    - Generates “Top 5” short-form video clips with ffmpeg + AI titles  
    - Sends output back to Telegram

## Stack Snapshot

- **Languages**: Python, Bash, JavaScript, SQL  
- **Core Tools**: FastAPI, Playwright, ffmpeg, Ollama, Supabase  
- **Infra**: Docker, Gitea, WireGuard, Tailscale, systemd, cron  
- **Browser Automation**: Firefox + extensions, Incognition, adb for Android  
- **LLM Ops**: local LLaMA 3, embedding + CLIP, RAG pipelines, self-hosted models  
- **Data Pipelines**: REST APIs, webhook ingestion, JSONL logs, auto DB insertions  
- **Storage**: PostgreSQL (via Supabase), vector DB (custom or local), session cache (SQLite)
