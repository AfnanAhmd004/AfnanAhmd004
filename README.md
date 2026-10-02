# Afnan Ahmed Adil

**AI & Robotics Researcher.** I build AI that works outside the lab, from autonomous robots and space systems to multi-agent systems for quantitative trading.

- 🧭 I lead AI strategy, the product roadmap and the engineering team for AI-native robotic platforms (LLMs, agentic AI, VLMs, multi-agent orchestration).
- 🤖 **Robotics & perception.** SLAM, state estimation, LiDAR and event-camera perception, multi-robot coordination, MPC, and industrial machine vision.
- 📈 **AI for quantitative trading.** Intraday ML/DL trading systems; alpha research with transformers, Bayesian models and reinforcement learning; market microstructure and execution.

---

### 🔬 Projects

**Agentic AI & multi-agent systems**
| Repo | What it shows |
|---|---|
| [agent-graph](https://github.com/AfnanAhmd004/agent-graph) | Stateful agent runtime: parallel fan-out, checkpoints with crash recovery, human-in-the-loop approvals, retries, tracing |
| [agent-swarm](https://github.com/AfnanAhmd004/agent-swarm) | Multi-agent coordination (voting, routing, cascades, debate) benchmarked on cost, accuracy and Byzantine robustness |
| [agent-evals](https://github.com/AfnanAhmd004/agent-evals) | Agent evaluation with pass@k / pass^k, trajectory checks and a CI release gate that blocks safety regressions |
| [robot-ops-agent](https://github.com/AfnanAhmd004/robot-ops-agent) | Robot-fleet operations agent: CUSUM fault detection, work orders, and a safety layer that does not trust the model |
| [deep-research-agent](https://github.com/AfnanAhmd004/deep-research-agent) | Deep research over your documents: hybrid retrieval, cited claims, claim verification and abstention |
| [agent-roster](https://github.com/AfnanAhmd004/agent-roster) | 17 specialist agents (robotics, ML, quant, CTO) as Claude Code subagents, with a router and gated playbooks |
| [n8n-ai-workflows](https://github.com/AfnanAhmd004/n8n-ai-workflows) | Production n8n workflows with LLM guardrails, unit-tested code nodes and end-to-end runs in real n8n |
| [agentic-trading-lab](https://github.com/AfnanAhmd004/agentic-trading-lab) | Trading-firm agents: quant, LLM and news analysts, bull/bear debate, risk committee, lookahead-safe backtest |
| [llm-agent-orchestrator](https://github.com/AfnanAhmd004/llm-agent-orchestrator) | Testable multi-agent orchestration: typed tools, JSON action protocol, planner/workers and reviewer patterns |
| [rag-paper-assistant](https://github.com/AfnanAhmd004/rag-paper-assistant) | Retrieval-augmented QA over research papers with hybrid retrieval and citations |
| [awesome-agentic-ai](https://github.com/AfnanAhmd004/awesome-agentic-ai) | Curated, link-checked map of agentic AI for robotics, industry and quant, with a failure-mode playbook |

**LLMs, VLMs & alignment**
| Repo | What it shows |
|---|---|
| [lora-finetuning-lab](https://github.com/AfnanAhmd004/lora-finetuning-lab) | LoRA and QLoRA (NF4) from scratch against full fine-tuning; measures catastrophic forgetting and fixes it with replay |
| [llm-compression](https://github.com/AfnanAhmd004/llm-compression) | int8/int4 quantization, knowledge distillation and ONNX Runtime export, with size/speed/quality trade-offs |
| [llm-inference-server](https://github.com/AfnanAhmd004/llm-inference-server) | KV cache, continuous batching and speculative decoding behind an HTTP API, packaged with Docker |
| [preference-alignment](https://github.com/AfnanAhmd004/preference-alignment) | Reward modelling, DPO and RLHF compared end to end, including mode collapse and reward hacking |
| [clip-ablation-study](https://github.com/AfnanAhmd004/clip-ablation-study) | Contrastive vision–language training with 8 controlled ablations and compositional generalisation tests |

**Robotics, perception & control**
| Repo | What it shows |
|---|---|
| [pose-graph-slam](https://github.com/AfnanAhmd004/pose-graph-slam) | SE(2) pose-graph SLAM with sparse Levenberg–Marquardt and robust kernels that survive false loop closures |
| [lidar-perception-cpp](https://github.com/AfnanAhmd004/lidar-perception-cpp) | Real-time C++17 LiDAR pipeline (ground segmentation, clustering, traversability) with CMake, CI and Python bindings |
| [multi-robot-coordination](https://github.com/AfnanAhmd004/multi-robot-coordination) | Leader–follower teams, RRT\* planning and dynamic re-planning |
| [event-vision-toolkit](https://github.com/AfnanAhmd004/event-vision-toolkit) | Event-camera simulation, voxel grids and time surfaces, denoising, and tracking of space objects |
| [ekf-sensor-fusion](https://github.com/AfnanAhmd004/ekf-sensor-fusion) | GNSS/INS extended Kalman filter with bias estimation, outage handling and NIS consistency |
| [robot-control-mpc](https://github.com/AfnanAhmd004/robot-control-mpc) | LQR cart-pole balancing and constrained LTV-MPC trajectory tracking |
| [multi-object-tracker](https://github.com/AfnanAhmd004/multi-object-tracker) | SORT-style tracking: Kalman filter, Hungarian matching, CLEAR-MOT metrics |

**Industrial automation**
| Repo | What it shows |
|---|---|
| [vision-pokayoke](https://github.com/AfnanAhmd004/vision-pokayoke) | Machine-vision error-proofing station: defect checks, line-stop interlock and part-level traceability |
| [predictive-maintenance-ts](https://github.com/AfnanAhmd004/predictive-maintenance-ts) | Industrial anomaly detection: PCA residual, isolation forest, autoencoder, lead-time metrics |

**Quantitative research & ML for finance**
| Repo | What it shows |
|---|---|
| [lob-microstructure](https://github.com/AfnanAhmd004/lob-microstructure) | Limit-order-book simulator, order-flow imbalance and microprice, and TWAP/VWAP/Almgren–Chriss execution measured by implementation shortfall |
| [bayesian-signals](https://github.com/AfnanAhmd004/bayesian-signals) | Online Bayesian regression and GP-ARD for weak signals, with probabilistic and deflated Sharpe ratios against selection bias |
| [tsformer-forecast](https://github.com/AfnanAhmd004/tsformer-forecast) | Transformer forecasting with walk-forward evaluation against honest baselines |
| [alpha-factor-lab](https://github.com/AfnanAhmd004/alpha-factor-lab) | Cross-sectional factor research: IC, decay, quantile portfolios, IC-weighted combination |
| [quant-backtester](https://github.com/AfnanAhmd004/quant-backtester) | Event-driven backtester with next-bar fills, stops, costs and risk metrics |
| [purged-cv](https://github.com/AfnanAhmd004/purged-cv) | Purged K-fold and combinatorial purged CV to prevent label leakage |
| [rl-trading-agent](https://github.com/AfnanAhmd004/rl-trading-agent) | Double DQN agent in a Gymnasium-style trading environment |
| [market-regime-detection](https://github.com/AfnanAhmd004/market-regime-detection) | From-scratch Gaussian HMM with causal regime filtering |

---

### 🏗️ How I build
- **Evidence over demos.** Every repo ships tests, a reproducible experiment and a README that reports failures alongside wins: forgetting, mode collapse, reward hacking, false loop closures, overfit backtests, agents that look better but fail safety cases.
- **Built to be deployed.** Latency and memory budgets, quantization, C++ where it matters, CI, Docker, and safety interlocks on anything that touches hardware. Agents get least-privilege tools, human approvals and audit logs.
- **Research to product.** I turn papers into tested components a team can own, and choose the simplest method that beats an honest baseline.

### 🧰 Stack
`Python` `C++` `PyTorch` `ONNX Runtime` `ROS 2` `OpenCV` `CMake` `MATLAB/Simulink` `Docker` `Linux` `GitHub Actions` · LLMs & agentic systems · Multi-agent orchestration · MCP · n8n · Agent evaluation · VLMs · RLHF/DPO · Transformers · Reinforcement learning · SLAM & state estimation · Event-based vision · MPC · Bayesian inference · Market microstructure

### 📫 Connect
[LinkedIn](https://www.linkedin.com/in/afnan-ahmed-adil-o28a781b3) · afnanahmed2773@gmail.com
