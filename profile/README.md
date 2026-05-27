# DISTA-HCAI · Human-Centric AI Research

> **Dipartimento di Scienze Teoriche e Applicate — Università degli Studi dell'Insubria, Varese, Italy**

We are a research group working at the intersection of **trustworthy AI**, **neural language models**, and **ethical AI engineering**. Our work focuses on making large-scale language models safer, more aligned with human values, and robust against misuse — while keeping the research open and accessible to the broader community.

---

## 🔬 Research Focus

### Alignment & Human-Centric Language Models
We study the design and evaluation of **helpful, honest, and harmless** neural language models across the full size spectrum — from small and mid-size models to large-scale ones. Our survey work maps the landscape of open-source alignment techniques, covering:

- **Parameter-efficient fine-tuning** (LoRA, adapters, prefix tuning)
- **Specialised prompting frameworks** for value alignment
- **Case-specific knowledge injection**
- **Adversarially robust training**
- Progress on **commonsense reasoning**, **factuality**, and **abstract reasoning**

The goal is to lower the barrier of entry for researchers and practitioners who want to build human-centric AI systems responsibly.

### Language Model Immunisation
A core theme in our recent work is **language model immunisation**: making open-weights models resistant to fine-tuning or inference-time manipulation that steers them toward harmful, toxic, or dual-use behaviours. Concretely, we investigate:

- **Inference-Time Interventions (ITI)** as a low-cost, increasingly accessible attack surface
- **Ethical Treatment (E.T.)** — our proposed defence strategy, which trains layer-wise **low-rank adaptors** to locally neutralise ITI-attacks at the decoder-block level of Transformer architectures
- Empirical evaluation on **Llama-3-8B-Instruct** using the **TinyBenchmarks** suite, demonstrating strong preservation of commonsense reasoning and world knowledge

---

## 📄 Selected Publications

| Paper | Venue | Links |
|-------|-------|-------|
| **Open-Ethical AI: Advancements in Open-Source Human-Centric Neural Language Models** — Sicari S., Cevallos M. J.F., Rizzardi A., Coen-Porisini A. | *ACM Computing Surveys* | [ACM DL](https://dl.acm.org/doi/10.1145/3703454) |
| **Ethical Treatment of Language Models Against Harmful Inference-Time Interventions** — Cevallos-Moreno J.F., Rizzardi A., Sicari S., Coen-Porisini A. | *Engineering Applications of Artificial Intelligence* | [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0952197626005981) |

---

## 👥 Team

| | |
|---|---|
| **Sabrina Sicari** | Associate Professor |
| **Jesús F. Cevallos-Moreno** | PhD Researcher |
| **Alessandra Rizzardi** | Researcher |
| **Alberto Coen-Porisini** | Full Professor |

*Dipartimento di Scienze Teoriche e Applicate (DISTA), Università degli Studi dell'Insubria — Varese, Italy*

---

## 🧭 Our Principles

- **Openness** — we prioritise open-source code, data, and models
- **Safety by design** — alignment and robustness are first-class research goals, not afterthoughts
- **Reproducibility** — all our published work shares code and data wherever possible
- **Human-centricity** — AI systems should augment and respect human values
