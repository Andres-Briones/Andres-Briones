## Andres Briones

I've just finished my Master's in Theoretical Physics at the University of Geneva, and I'm open to new opportunities.
I like turning messy scientific and real-world data into tools people can actually use: data pipelines, physical
models, small web apps, and lately AI agents.

### Featured: Flame in Freefall (NASA Space Apps 2026)

In one weekend at the NASA Space Apps hackathon, team **Orbita Chalaca** built **Ignis**, an AI-assisted dashboard that summarises, ranks and interprets the
24 NASA microgravity combustion investigations for spacecraft fire safety. Getting that far in a weekend was only
possible because we built it with AI coding agents.
→ [Live app](https://orbita-web-813905724775.us-central1.run.app)

My part was the physics and the data, in [**flame-in-freefall**](https://github.com/Andres-Briones/flame-in-freefall)
([demo of the data](https://andres-briones.github.io/flame-in-freefall/)):

- one knowledge record per investigation (physics with equations, findings with quoted sources, limitations)
- 2,177 test rows from NASA's PSI archive on a common schema, with every error found in the source data kept as a
  visible correction instead of a silent fix
- reviews of the 352 papers the investigations cite
- physical models and a data server (REST + MCP) that the dashboard and its AI assistant query

### Projects

| | Project | What it is |
|---|---|---|
| 🐳 | [claudebox](https://github.com/Andres-Briones/claudebox) (fork) | Claude Code in Docker, my daily setup: rootless install without sudo, one login and shared memory across containers, self-improving agent configuration |
| 🧾 | Dolibarr for Argentina: [l10n-ar](https://github.com/Andres-Briones/dolibarr-l10n-ar), [arca](https://github.com/Andres-Briones/dolibarr-arca), [mpago](https://github.com/Andres-Briones/dolibarr-mpago), [tienda](https://github.com/Andres-Briones/dolibarr-tienda), [meli](https://github.com/Andres-Briones/dolibarr-meli) | Open-source modules for a small Argentine business: tax ids and VAT, electronic invoicing, Mercado Pago, online shop, Mercado Libre (in progress, not yet deployed) |
| 🤖 | [nabla-agent](https://github.com/Andres-Briones/nabla-agent) | Multi-agent coding orchestrator in Bun + TypeScript: role-specialised agents working in sandboxed containers (in progress) |
| 💸 | [Splitty](https://github.com/Andres-Briones/Splitty) | Command-line tool that splits group expenses and finds the fewest payments to settle up |
| 🎙️ | [TranscribeAudioWhisper](https://github.com/Andres-Briones/TranscribeAudioWhisper) | Command-line script that transcribes audio files with Whisper |
| ♠️ | [NablaPoker](https://github.com/Andres-Briones/NablaPoker), [OpenPokerTracker](https://github.com/Andres-Briones/OpenPokerTracker) | Earlier poker projects: hand replayer and statistics (unfinished) |

### Tools I use

Python (pandas, NumPy, SciPy, Flask) · Docker · Git · LLM agents and MCP

### Contact

📫 andres@briones.ch · 📍 Geneva, Switzerland
