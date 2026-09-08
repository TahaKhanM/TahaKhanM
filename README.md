# Taha

I’m a Computer Science undergraduate at the University of Warwick, interested in quantitative development, systems and backend engineering. I work mainly in Python, Rust, TypeScript and C.

I build trading simulations, numerical models and interactive applications. Much of the engineering work is in checking what a replay assumes, keeping asynchronous state consistent and making data and permission boundaries explicit. The projects below include implementations, tests and the reasoning behind those decisions.

## Selected work

| Project | Problem and technical work |
| --- | --- |
| [Prosperity](https://github.com/TahaKhanM/Prosperity) | Team algorithmic-trading research for IMC Prosperity. Python strategies, a Rust/Python replay backtester, options pricing and volatility analysis. The repository distinguishes submitted traders from later tooling fixes and explains where historical fills and P&L depend on simulation assumptions. |
| [LearnWithNoura](https://github.com/TahaKhanM/LearnWithNoura) | A voice tutor with a shared teaching board. My work extends a collaborative prototype with a deterministic drawing compiler, server-owned lesson scheduling, playback-aware interruption and released-event replay. The central problem is keeping what the tutor says consistent with what the learner actually sees. |
| [ZetaLog](https://github.com/TahaKhanM/zetalog) | A local-first mental-arithmetic recorder, Chrome extension and leaderboard. A shared TypeScript core replays answer telemetry; authenticated submission, database idempotency and review decisions connect an offline recorder to a shared ranking. |
| [Citadel Terminal](https://github.com/TahaKhanM/CitadelTerminal) | A tournament strategy workspace combining Python search with a Rust combat simulator. The interesting questions are simulator fidelity, candidate selection under a turn budget, opponent assumptions and evaluation against the official engine. Original tournament work and subsequent evaluation repairs are documented separately. |
| [Precedent](https://github.com/TahaKhanM/AI-Agent-Hackathon) | An incident-response and change-gate prototype. Typed plans, deterministic risk rules, approval steps, rollback and permission-aware memory constrain proposed actions. Its incident analysis explicitly separates information available at arrival from retrospective outcome labels. |
| [Neural network from scratch](https://github.com/TahaKhanM/neural-network-from-scratch) | A NumPy implementation of dense layers, sigmoid activations, minibatch SGD and backpropagation. Every parameter gradient is checked against finite differences; training, validation and held-out MNIST evaluation have explicit boundaries. A compact project for inspecting the mathematics directly. |

## Other projects worth inspecting

- [FoundersHQ](https://github.com/TahaKhanM/FoundersHQ): a fintech prototype with organization-scoped APIs, Decimal financial calculations and evidence-linked cash-flow forecasts.
- [Food-bank optimisation](https://github.com/TahaKhanM/foodbank-optimisation): integer parcel selection under nutritional, stock, exclusion and variety constraints. A runnable synthetic catalogue makes the formulation and solver checks easy to inspect alongside the collaborative paper.
- [Microfinance analysis](https://github.com/TahaKhanM/microfinance-preprint-repo): a reproducibility review of a collaborative research project, with chronological forecast validation, persistence baselines and a clear separation between observed data and noncausal scenarios.
- [LED-panel Pong](https://github.com/TahaKhanM/led-panel-pong-emulator): C game logic and a browser emulator for a 32×32 RGB panel protocol. The code makes frame encoding, input handling and the native/browser boundary easy to inspect.

## Currently building

I’m developing LearnWithNoura’s drawing and lesson runtime and ZetaLog’s recording and submission workflow. I’m also tightening the evaluation and numerical checks around my competition research, with particular attention to failure cases and reproducibility.

I tutor mathematics, enjoy chess and care about explaining why an implementation works as much as getting it to run. Collaborative projects credit their contributors and upstream tooling in their own READMEs; historical competition results are kept distinct from later engineering improvements.

[Email](mailto:contact.mtaha@gmail.com)
