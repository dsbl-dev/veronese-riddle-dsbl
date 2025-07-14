# Solving the Veronese Riddle: A Computational Key to Medieval Semantics

[![Status: Conceptual Model](https://img.shields.io/badge/status-conceptual_model-blue.svg)](https://github.com/dsbl-dev/veronese-riddle-dsbl)

This repository provides a conceptual model and formal representation of the eighth-century Veronese Riddle using the principles of Deferred Semantic Binding Language (DSBL). It serves as a companion to the academic paper:

**Petersson, J. (2025). Solving the Veronese Riddle: A Computational Key to Medieval Semantics.** *Zenodo.*  
[DOI TODO - will be added upon publication]

## Overview

The Veronese Riddle (c. AD 800) emerged as Latin gave way to newer forms. While Classical Latin represented the visible cathedral of formal language, the riddle signals the logic of an underlying "mycelial network" of vernacular communication. It represents one of the earliest documented instances of deferred semantic binding, where meaning remains dormant until an observer supplies the context of writing. This repository formalizes that mechanism using DSBL.

## The DSBL Model of the Riddle

The core logic can be expressed as a simple DSBL program, where dormant tokens are bound to their semantics only when the correct context is supplied.

**DSBL Pseudocode:**

```
⟦CONTEXT:writing⟧ {
    ⟦ACTOR⟧  := fingers;
    ⟦SURFACE⟧:= page;
    ⟦SEED⟧   := ink;
}
print("He was driving ⟦ACTOR⟧ ...");
```

This demonstrates the fundamental principle of deferring semantic binding from design-time to runtime, contingent on a contextual key.

## Empirical Validation & Core Implementation

The DSBL principles applied here are not merely theoretical. They have been implemented and empirically validated in a large-scale, complex multi-agent system designed to study social homeostasis.

For the full implementation, underlying source code, and empirical data, please see the primary DSBL project repository:

➡️ **[dsbl-dev/clsh-core: The Core DSBL Framework](https://github.com/dsbl-dev/clsh-core)**

This `veronese-riddle-dsbl` repository serves as a conceptual bridge, applying the validated principles from `clsh-core` to a historical artifact.

## How to Cite

If you use the concepts or models from this work, please cite the main paper:

```bibtex
@misc{petersson2025veronese,
  author       = {Petersson, Joel},
  title        = {Solving the Veronese Riddle: A Computational Key to Medieval Semantics},
  year         = {2025},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.XXXXXXX},
  url          = {https://doi.org/10.5281/zenodo.XXXXXXX}
}
```

## The Tending: A Contemporary Echo

As a contemporary echo of the riddle's performative nature, this work includes the design of **The Tending**: a cryptographic seal implementing DSBL principles through Shamir's Secret Sharing. 50 fragments distributed among appointed Vestals, where any 40 suffice for reconstruction. The seal demonstrates how deferred semantic binding can operate across millennial timescales. Full specification in the paper's Coda section.

## Related Work

This work builds upon the foundational DSBL framework:

- **Core DSBL Implementation:** [dsbl-dev/clsh-core](https://github.com/dsbl-dev/clsh-core)
- **Original DSBL Paper:** Petersson, J. (2025). *Deferred Semantic Binding Language: Enabling Closed-Loop Social Homeostasis in Multi-Agent Systems.* Zenodo. [10.5281/zenodo.15742505](https://doi.org/10.5281/zenodo.15742505)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

**Joel Petersson**  
Independent Researcher

📧 echo [at] joelpetersson [dot] com  
🔗 [ORCID: 0009-0003-7002-6601](https://orcid.org/0009-0003-7002-6601)