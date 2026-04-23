<div align="center">

# Shafiq Ahmed

### PhD Candidate in Computer Science and Electronic Engineering
### Applied Cryptography | Cybersecurity | Artificial Intelligence | Smart Grid and V2G Security

I design and analyse security protocols for systems where trust is scarce, mobility is high, and delay budgets are unforgiving.
My current research sits around AI-based provably secure authentication, post-quantum cryptography, federated learning, and privacy-preserving security for Smart Grid, V2G, IoT, and Industrial Cyber-Physical Systems.

[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Research%20Profile-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=8ghaRpf3pOEC&hl=en)
[![DBLP](https://img.shields.io/badge/DBLP-Bibliography-004F9F?style=for-the-badge)](https://dblp.org/pid/261/8518)
[![University of Essex](https://img.shields.io/badge/University%20of%20Essex-Profile-741B47?style=for-the-badge)](https://www.essex.ac.uk/people/AHMED59100)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-csshafiqahmed-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/csshafiqahmed/)
[![Email](https://img.shields.io/badge/Email-csshafiqahmed%40gmail.com-8A2BE2?style=for-the-badge&logo=gmail&logoColor=white)](mailto:csshafiqahmed@gmail.com)

</div>

---

## Research identity

My work is motivated by a fairly practical question: how can a small device prove the right thing, at the right time, without leaking more than it should?

- PhD Candidate, School of Computer Science and Electronic Engineering, University of Essex, United Kingdom.
- Research focus: AI-based provably secure and cost-effective authentication protocols for demand response power management in the Vehicle-to-Intelligent-Grid paradigm.
- Core domains: Smart Grid, Vehicle-to-Grid communication, high-mobility IoT, Industrial CPS, VANETs, wireless sensor networks, and edge-assisted security.
- Cryptographic lens: ECC, signcryption, zero-knowledge authentication, PUFs, threshold cryptography, post-quantum primitives, and formal security reductions.
- AI security lens: reinforcement learning, federated learning, predictive token learning, adversarial robustness, and intrusion detection.

I tend to start from simple protocol logic first, then push it toward a formal model. A useful sketch is:

```math
L_{auth} = L_{comp} + L_{comm} + L_{sync}
```

and, for an authentication experiment with security parameter \lambda:

```math
Pr[break] \le Adv_{A}^{CDH}(\lambda) + Adv_{A}^{SIG}(\lambda) + negl(\lambda)
```

That inequality is not decoration. It is the basic research habit: name the adversary, name the assumption, and make the cost visible.

---

## Current research threads

These threads describe the direction of my recent work and the code I am actively shaping into reproducible research artifacts.

| Thread | What I am studying | Representative work |
| --- | --- | --- |
| Zero-knowledge mobility authentication | Compact proofs for high-speed IoT and V2G roaming without exposing long-term identity or movement patterns. | [AI-enhanced ZK authentication](https://github.com/csshafiqahmed/AI-Enhanced-Zero-Knowledge-Authentication-for-High-Mobility-IoT-Using-Predictive-Token-Learning) |
| Post-quantum V2G security | Authentication and federated trust under quantum-capable adversarial models. | [PQ-V2G](https://github.com/csshafiqahmed/PQ-V2G) |
| Federated learning security | Byzantine-resilient aggregation, trust scoring, and adaptive defence under poisoning attacks. | [tars-fl-sim](https://github.com/csshafiqahmed/tars-fl-sim) |
| AI-assisted vehicle security | Intrusion detection and authentication for autonomous and connected vehicle environments. | [AIDAS implementation](https://github.com/csshafiqahmed/AIDAS-Implementation) |
| Secure cyber-physical energy systems | Blockchain, access control, and AI-supported authentication for multi-domain V2G networks. | [lqap_project](https://github.com/csshafiqahmed/lqap_project) |
| UAV and command security | Authenticated command pipelines for UAV and high-mobility environments, including LLM-facing control interfaces. | [uav-llm-command](https://github.com/csshafiqahmed/uav-llm-command) |

---

## Selected publications

The list below is deliberately short. For the complete and live scholarly record, please use Google Scholar or DBLP.

1. S. Ahmed and M. H. Anisi, "AI-Enhanced Zero-Knowledge Authentication for High-Mobility IoT Using Predictive Token Learning," *IEEE Internet of Things Journal*, vol. 13, no. 5, pp. 9068-9077, 2026. [DOI](https://doi.org/10.1109/JIOT.2025.3644599)
2. S. Ahmed and M. H. Anisi, "A Post-Quantum Secure Federated Learning Framework for Cross-Domain V2G Authentication," *IEEE Transactions on Consumer Electronics*, vol. 71, no. 3, pp. 8433-8440, 2025. [DOI](https://doi.org/10.1109/TCE.2025.3580338)
3. S. Ahmed and M. H. Anisi, "AIDAS: AI-Enhanced Intrusion Detection and Authentication for Autonomous Vehicles," *IEEE Transactions on Intelligent Transportation Systems*, vol. 26, no. 8, pp. 12548-12557, 2025. [DOI](https://doi.org/10.1109/TITS.2025.3562919)
4. S. Ahmed and M. H. Anisi, "Optimizing V2G Dynamics: An AI-Enhanced Secure Protocol for Energy Management in Industrial Cyber-Physical Systems," *IEEE Transactions on Industrial Cyber-Physical Systems*, vol. 2, pp. 312-320, 2024. [DOI](https://doi.org/10.1109/TICPS.2024.3432851)
5. S. Ahmed et al., "Signcryption Based Authenticated and Key Exchange Protocol for EI-Based V2G Environment," *IEEE Transactions on Smart Grid*, vol. 12, no. 6, pp. 5290-5298, 2021. [DOI](https://doi.org/10.1109/TSG.2021.3102156)
6. S. Ahmed et al., "Anonymous Key-Agreement Protocol for V2G Environment Within Social Internet of Vehicles," *IEEE Access*, vol. 8, pp. 119829-119839, 2020. [DOI](https://doi.org/10.1109/ACCESS.2020.3003298)

---

## Technical stack

I use tools that let me move between proof, simulation, and implementation without pretending those are separate worlds.

**Formal verification and protocol analysis**  
ProVerif, AVISPA, Scyther, Tamarin, Random Oracle Model analysis, informal attack modelling.

**Cryptography and security**  
ECC, signcryption, key agreement, zero-knowledge proofs, PUFs, Kyber, Dilithium, XMSS, threshold cryptography, privacy-preserving authentication.

**AI and systems**  
Python, C, C++, Java, JavaScript, MATLAB, federated learning, reinforcement learning, intrusion detection, blockchain access control.

**Writing and research workflow**  
LaTeX, Git, GitHub, VS Code, reproducible experiments, paper-to-code translation.

---

## Featured repositories

These repositories show the research shift in my GitHub profile from teaching and application development toward security protocol research.

| Repository | Focus |
| --- | --- |
| [AI-Enhanced-Zero-Knowledge-Authentication-for-High-Mobility-IoT-Using-Predictive-Token-Learning](https://github.com/csshafiqahmed/AI-Enhanced-Zero-Knowledge-Authentication-for-High-Mobility-IoT-Using-Predictive-Token-Learning) | Zero-knowledge authentication, predictive token learning, high-mobility IoT |
| [PQ-V2G](https://github.com/csshafiqahmed/PQ-V2G) | Post-quantum identity, privacy, and resilience for V2G communication |
| [AIDAS-Implementation](https://github.com/csshafiqahmed/AIDAS-Implementation) | AI-enhanced intrusion detection and authentication for autonomous vehicles |
| [tars-fl-sim](https://github.com/csshafiqahmed/tars-fl-sim) | Trust-aware reinforcement selection for secure federated learning |
| [lqap_project](https://github.com/csshafiqahmed/lqap_project) | Blockchain-based federated learning architecture for secure multi-domain V2G |
| [NSRG](https://github.com/csshafiqahmed/NSRG) | Network Security Research Group code and experiments |

---

## GitHub activity

Numbers are useful, but they are only a partial signal. I care more about whether a repository makes a claim reproducible.

<div align="center">

![Shafiq Ahmed's GitHub stats](https://github-readme-stats.vercel.app/api?username=csshafiqahmed&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github)

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=csshafiqahmed&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## Collaboration

I am interested in research collaborations where the goal is clear: design a protocol, prove what it claims, and test whether it survives the limits of real systems.

- Secure authentication for Smart Grid, V2G, IoT, UAV, and cyber-physical systems.
- Post-quantum and zero-knowledge protocol design.
- Federated learning security under non-IID data and adaptive adversaries.
- AI-assisted security mechanisms that remain auditable rather than mysterious.

For research contact, email me at **csshafiqahmed@gmail.com**.
