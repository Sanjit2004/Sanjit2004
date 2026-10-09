### Sanjit Saji

I build AI agents and the services around them: the APIs, data handling, tests, and deployment that make them usable inside real systems.

[LinkedIn](https://www.linkedin.com/in/sanjit-saji-b525921b5/) · [sanjitsaji2004@gmail.com](mailto:sanjitsaji2004@gmail.com)

#### Selected work

**[PriorAuth Preflight](https://github.com/agents-assemble/priorauth-agent)** · Python, Google ADK, FastMCP, FHIR, Gemini, Fly.io

Checks a patient's FHIR chart against Cigna and Aetna lumbar MRI criteria before a prior-authorization request goes out. Each request lands in one of four outcomes: ready for human review, needs info, do not submit, or red-flag fast-track. Deterministic rules run before the model, every criterion cites the chart evidence it used, and nothing is auto-submitted. I led the agent layer: an orchestrator with three sub-agents, FHIR token handling, synthetic patient bundles, and the Fly.io deployment.

205 tests · CI runs ruff, mypy (strict), and pytest on every PR · two services on Fly.io · [Demo video](https://www.youtube.com/watch?v=pBmYClgg194) · *built with [@kevinsgeo](https://github.com/kevinsgeo)*

**[Ally](https://github.com/Sanjit2004/ally)** · TypeScript, Expo / React Native, Express, OpenAI

Mobile AI companion with a consistent persona, on-device memory ranked by importance, a mood engine that adapts to the user, and voice calls with text-to-speech. The Express backend separates the chat, memory, and speech services behind a small REST API.

*Built with [@Adnanfaz](https://github.com/Adnanfaz)*

**[Sports analytics](https://github.com/Sanjit2004/sports-analytics-portfolio)** · R, XGBoost, Monte Carlo, GitHub Actions

IPL ball-by-ball win probability, comparing logistic regression, random forest, and XGBoost on a held-out 2025 season. XGBoost gave the best-calibrated probabilities, while its AUC was effectively tied with the logistic baseline. The repo also has a Bradley–Terry model replayed over 20,000 simulated seasons. CI re-downloads the data and re-runs both notebooks on every pull request that changes them.

[Win probability](https://sanjit2004.github.io/sports-analytics-portfolio/ipl-win-probability.html) · [Full analysis](https://sanjit2004.github.io/sports-analytics-portfolio/ipl-win-probability-full.html) · [Tournament simulation](https://sanjit2004.github.io/sports-analytics-portfolio/ipl-bradley-terry-tournament-simulation.html)

#### Stack

Python, TypeScript, React Native, R · Google ADK, MCP, A2A, FHIR · OpenAI, Gemini · Docker, Fly.io, GitHub Actions
