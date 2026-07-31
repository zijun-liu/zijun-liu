## Zijun Liu

Data scientist working on generative AI at Merck. Before that, four years of clinical trial statistics at the UCSF Proctor Foundation.

My through line is measurement. Deciding whether a system is good enough to act on is an experimental design problem, and that is true whether the system is a mass drug administration strategy or a language model. At UCSF I worked on the adaptive randomization design for AVENIR, a cluster randomized trial covering more than two million people in Niger, and on the interim analyses behind its treatment decisions. The primary results were published in the New England Journal of Medicine in 2024. At Merck I build GenAI applications for enterprise decision making, where the question I keep coming back to is the one most demos skip: how do you know the output is any good?

**Tools and methods**

Python, R, SQL. Causal inference, adaptive experimental design, bootstrap and permutation methods, survival analysis, power analysis. LLM pipelines, agent workflows, and evaluation design for LLM systems.

**What I am thinking about**

Evaluation as measurement science. Checking an LLM judge against human labels is the same problem as checking two clinical graders against each other, and the statistics carry over: agreement coefficients rather than raw accuracy, confidence intervals on scores, and an honest answer to how many eval examples a comparison needs before you can trust it.

**Selected work here**

- [forex-trading](https://github.com/zijun-liu/forex-trading): USD/JPY advisory agent. All numbers computed deterministically, LLM confined to three reasoning steps, with a backtest path that replays signals without any model calls.
- [matcha-alert](https://github.com/zijun-liu/matcha-alert): restock monitor running on GitHub Actions, with state committed back to the repo so alerts never repeat.
- [zipair-tracker](https://github.com/zijun-liu/zipair-tracker): fare tracker for SFO to Tokyo, same pattern, with the data source limitations written down rather than glossed over.

**Elsewhere**

- Publications: [PubMed](https://pubmed.ncbi.nlm.nih.gov/?term=Liu+Zijun%5BAuthor%5D+AND+Proctor%5BAffiliation%5D) (21 papers from the UCSF years, including NEJM, JAMA Network Open, and Clinical Infectious Diseases)
- [LinkedIn](https://www.linkedin.com/in/zijun-liu)
- zijunliu2015@gmail.com
