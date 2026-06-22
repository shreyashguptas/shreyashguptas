# Shreyash Gupta

> Building things that solve problems I run into.

Associate Director of Analytics at the University of Arkansas. Maker, tinkerer, and small-business owner working where hardware, software, and AI meet. Whether it's a 3D-printed enclosure for a mesh radio, a voice agent running on a Raspberry Pi, or a site that teaches machine learning with real-world analogies — if it solves a problem, I'm probably building it.

---

## What I'm Working On

### 🔌 OffGrid Devices

Designing and manufacturing MagSafe-compatible enclosures for [Meshtastic](https://meshtastic.org) and [MeshCore](https://meshcore.co.uk/) off-grid mesh networking devices. CAD in Shapr3D, printed on a small Prusa farm (Core One + Prusa XL), and shipped through [the OffGrid Devices site](https://offgridevices.com), [Etsy](https://www.etsy.com/shop/OffGridDevices), and Amazon.

### 🤖 AI & Agents

- **Javia** — a voice assistant I built end to end, hardware and software. Press a button, ask anything, and get a spoken answer back in under 1.5 seconds — with short- and long-term memory so it gets more personal over time. Raspberry Pi with dual I2S mics in a custom 3D-printed enclosure; FastAPI + Supabase backend; Whisper (via Groq) → a 120B open model → streamed speech.
- **Agentic video pipeline** — turns long-form video into short vertical clips by chaining five models: Whisper (transcription) → Qwen3-VL (scene understanding) → a Claude-agent highlight picker → YOLO (subject tracking) → FFmpeg (9:16 export). Roughly $1–2 per video instead of $30/month for SaaS, and any stage swaps out when a better model ships.
- **Hand-built RAG** — the AI chat on [shreyashg.com](https://shreyashg.com) runs retrieval I wrote from scratch: embeddings with hybrid search (cosine similarity + BM25) fused via Reciprocal Rank Fusion. No managed vector database — the retrieval logic is all mine.
- **TubeGenius** — an MCP server built for the Hugging Face MCP Hackathon that auto-generates titles, descriptions, and thumbnails. For the image side, I fine-tuned Stable Diffusion on a set of top-performing YouTube thumbnails.

### 🛠️ Hardware & CAD

- **Needle-decompression indicator (patent pending)** — a thumb-sized 3D-printed turbine that mounts on a chest-decompression needle (the emergency treatment for a collapsed lung) and spins the instant air flows, giving the person treating it a clear "you're in" signal. Adds almost no weight, and prints in the field.
- **Parametric heat-set insert generator** — one Shapr3D file that generates 20 brass insert sizes (M2–M6) from three inputs, reverse-engineered from caliper measurements. Open-sourced on [Printables](https://www.printables.com/@shreyashgupta/models) and [GrabCAD](https://grabcad.com/shrey.g-2).
- **Drone frames + topology optimization** — exploring generative, topology-optimized quadcopter frames: let the solver decide where material belongs along the load paths, then print the result.

### 🌐 Websites I Build & Run

- **[shreyashg.com](https://shreyashg.com)** — My personal site. Writing, projects, and a self-hosted AI chat with the hand-built RAG above.
- **[billsincongress.com](https://billsincongress.com)** — A Congressional bill tracker that helps you understand the bills your representatives are proposing, with plain-English summaries and live status.
- **[mlfordummy.com](https://mlfordummy.com)** — Machine learning explained with real-world analogies.

---

## Find My 3D Models

I publish my designs across all the major 3D printing platforms — pick whichever you already use:

- **Printables** → [@shreyashgupta](https://www.printables.com/@shreyashgupta/models)
- **MakerWorld** → [@shreyashgupta](https://makerworld.com/en/@shreyashgupta/)
- **Thingiverse** → [@shreyashguptas](https://www.thingiverse.com/shreyashguptas/designs)
- **GrabCAD** → [@shrey.g-2](https://grabcad.com/shrey.g-2)

I'm also a [Shapr3D Creator Partner]([https://www.shapr3d.com](https://www.shapr3d.com/?utm_source=creators&utm_medium=socials&utm_campaign=shreyashgupta)), so a lot of the parametric source files are available alongside the STLs.

---

## Watch & Listen

- **YouTube** → [@ShreyashGuptas](https://www.youtube.com/@ShreyashGuptas) — Build-in-public videos: Shapr3D CAD, 3D printing, and maker business.
- **Podcast** → *The Federalist Papers: Explained* — A plain-English walkthrough of the Federalist Papers, one essay at a time.
  - [Listen on Spotify](https://open.spotify.com/show/4WDAio2kR6DbCkyuMRX8ea)
  - [Listen on Apple Podcasts](https://podcasts.apple.com/us/podcast/the-federalist-papers-explained/id1885411973)

---

## The Stack I Reach For

| | |
|---|---|
| **Design & Make** | Shapr3D · Prusa Core One + XL · PETG / PLA / TPU · Pixelmator Pro · Final Cut Pro |
| **Code** | Python · TypeScript · Next.js / React · FastAPI · and web stuff when the project calls for it |
| **AI & Agents** | Claude Agent SDK · MCP · Whisper · YOLO · Stable Diffusion · hand-rolled RAG · PyTorch |
| **Hardware** | Raspberry Pi · Arduino · RAK WisBlock · Heltec · breadboards and a soldering iron |
| **Home Lab** | TrueNAS Scale · UniFi · Docker · self-hosted whenever I can get away with it |

---

## Connect

- **X / Twitter** → [@ShreyashGuptas](https://x.com/ShreyashGuptas)
- **LinkedIn** → [in/shreyashgupta5](https://www.linkedin.com/in/shreyashgupta5/)
- **Personal site** → [shreyashg.com](https://shreyashg.com)

---

## Philosophy

If I'm running into a problem, I'm probably not the only one. Build the thing, share what I learn, repeat.
