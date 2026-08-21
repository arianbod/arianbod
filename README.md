

AI/ML engineer and researcher. My work sits where machine learning meets SAR/satellite remote sensing, seismic risk, and Bayesian calibration. I also build full-stack web and mobile products, which is how most of the research below actually ships and gets used.

- GitHub: [@arianbod](https://github.com/arianbod) (handle `arianbod`, name Amin Abtahi — legal: Seyed Mohammad Amin Abtahi)
- Project site: [quakewise.com](https://quakewise.com)
- ORCID: [0009-0009-4175-7636](https://orcid.org/0009-0009-4175-7636)

## Research

**QuakeWise — building-level seismic damage from physics + satellite data.** ([quakewise.com](https://quakewise.com))

The core method is a reliability-tempered Bayesian late fusion. It combines a physics-based fragility prior with a satellite damage likelihood, and each source's weight is set by its own measured calibration through an inverse-Brier reliability temper, so a source that turns out to be unreliable gets discounted automatically rather than by hand.

I validated it on about 80,917 real buildings across four earthquakes: Türkiye 2023, Noto 2024, Morocco 2023, and Haiti 2021. The headline result is expected calibration error dropping from 0.42 to 0.03. I also report where it does not help: the gain shows up mainly where hazard varies across the scene, and it narrows under a harder spatial-block split. QuakeWise is the thesis for my MSc in Electrical and Computer Engineering (supervisor Dr. Hamid Farrokh Ghatte).

Methods and tools: Python, PyTorch, physics-informed neural networks, computer vision, Bayesian inference, SAR and optical remote sensing.

**Publications.** Two first-author conference papers from this line of work (Greece 2025, Bosnia 2026). A journal article extending the fusion method is in preparation.

**Background.** Three Master's degrees: MIS, an MSc in Data Science (2025), and the MSc in Electrical and Computer Engineering currently in progress with QuakeWise as the thesis.

## Selected work

- **[nextjs-fs-earthquake](https://github.com/arianbod/nextjs-fs-earthquake)** — the QuakeWise application and MSc thesis project: a building-level earthquake-damage estimator. The research front end where the fusion model meets a usable interface.
- **[quakewise-paperb-replication](https://github.com/arianbod/quakewise-paperb-replication)** — replication package for the reliability-tempered Bayesian fusion paper: code, canonical results, and provenance/lineage manifests so the numbers can be reproduced.
- **[quakewise-platform](https://github.com/arianbod/quakewise-platform)** — QuakeWise V2, a three-layer system: Next.js gateway, Expo mobile app, and a FastAPI/Python AI backend that serves the model.
- **[gemini-live-next](https://github.com/arianbod/gemini-live-next)** — real-time voice and video chat wired to the Google Gemini Live API in Next.js.
- **[ai-agent-bundle-on-nextjs](https://github.com/arianbod/ai-agent-bundle-on-nextjs)** — a multimodal voice-assistant starter (voice, video, screen share, file upload) I reuse when starting a new agentic app.

## Engineering

The day-to-day engineering that supports the research and pays the bills:

- **Full-stack web** — Next.js (App Router, server actions), TypeScript, React, Prisma, Postgres (Neon), Tailwind, shadcn/ui, TanStack Query, deployed on Vercel
- **Mobile** — React Native / Expo
- **AI integration** — wiring Gemini, Claude, and OpenAI models into production products
- **Data / ML** — Python, PyTorch, pandas, scikit-learn, Jupyter; joining messy real-world sources and training models on them
- Currently learning Rust

## Links

[GitHub](https://github.com/arianbod) · [quakewise.com](https://quakewise.com) · [ORCID 0009-0009-4175-7636](https://orcid.org/0009-0009-4175-7636)
