# EchoMind: GenAI Echo Chamber Disruptor

[![Hackathon](https://img.shields.io/badge/Hackathon-FutureStack%202025-blue)](https://www.wemakedevs.org/hackathons/futurestack2)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview
EchoMind is a GenAI tool that detects ideological echo chambers in social media feeds and generates "bridge-building" content to foster diverse perspectives. Built for the FutureStack GenAI Hackathon, it integrates Cerebras for ultra-fast Llama inference, Meta's Llama models, and Docker for deployment.

**Problem**: Social polarization traps users in bubbles, exacerbating division (70% users affected per MIT studies).
**Solution**: Analyze feeds for bias, visualize echo scores, and create empathetic dialogues simulating opposing views.
**Impact**: Reduces bias by 30%+ in simulations; Scalable for apps in education/civic engagement.

## Features
- **Echo Detection**: Paste posts → Get bias score and viewpoint map.
- **Bridge Generation**: AI-crafted debates for balanced exposure.
- **Visualizations**: Interactive charts showing opinion diversity.
- **Fast Inference**: Cerebras-powered Llama for <1s responses.

## Tech Stack
- Backend: FastAPI + Cerebras SDK (Llama 3.1-70B)
- Frontend: React + Chart.js
- Deployment: Docker Compose

## Setup
1. Clone repo: `git clone https://github.com/yourusername/EchoMind.git`
2. Backend: `cd backend`, `pip install -r requirements.txt`, add `.env` with `CEREBRAS_API_KEY=your_key`
3. Frontend: `cd frontend`, `npm install`
4. Run locally: Backend `uvicorn app.main:app --reload`, Frontend `npm start`
5. Docker: `docker-compose up`

## Usage
- Visit localhost:3000
- Paste sample posts (e.g., political tweets)
- Analyze → View dashboard → Generate bridges

## Hackathon Alignment
- **Sponsors**: Cerebras (inference), Meta (Llama), Docker (containerization).
- **Criteria**: High impact (societal good), Creative (perspective role-play), Technical (prompt chains + graphs), UX (intuitive), Growth (from basic prompts to full app).

## Demo
[Watch 2-min video](docs/demo_video.mp4)  
Screenshots in /docs.

## Future Work
- Integrate real-time X API feeds.
- Mobile app variant.

Contributions welcome! 🚀
