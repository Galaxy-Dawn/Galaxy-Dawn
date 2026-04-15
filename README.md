# Hi, I'm Gaorui Zhang

I'm a PhD student at Zhejiang University working on **neural decoding**, **scientific tooling**, and **reliable AI systems for research**.

## What I work on

- **Neural decoding**: EEG / sEEG, speech-related brain signals, cross-subject modeling, and brain signal understanding
- **Scientific tooling**: open-source tools for publication-ready figures, tables, and research workflows
- **AI for research**: semi-automated systems for literature review, project memory, and scientific assistance

## Selected Research and Tools

These projects reflect my two main directions: **neural decoding research** and **tools for reproducible, publication-oriented scientific workflows**.

### Research

- [speech-decoding](https://github.com/Galaxy-Dawn/speech-decoding)  
  A research codebase for **brain-to-text decoding across both speech production and perception**.  
  Unlike many speech-decoding repos that focus on a single setting or a single model, this project organizes the **full workflow** from neural data preprocessing and channel analysis to decoder training, LLM-based reconstruction, and post-hoc analysis within one reproducible pipeline.

- [NeuroSketch](https://github.com/Galaxy-Dawn/NeuroSketch)  
  An effective framework for **neural decoding via systematic architectural optimization**.  
  Rather than proposing a model through isolated design choices, NeuroSketch is built from a **large-scale empirical study** spanning 5,000+ experiments across modalities, signal types, and decoding tasks, with the goal of identifying which architectural choices consistently matter for neural decoding.

### Tooling

- [claude-scholar](https://github.com/Galaxy-Dawn/claude-scholar)  
  A **semi-automated research assistant** for literature review, coding, experiments, reporting, writing, and project knowledge management.  
  Its key difference from generic coding assistants or “autonomous scientist” systems is that it keeps **human decision-making at the center**, while providing a structured workflow across the research lifecycle and supporting multiple agent environments including Claude Code, Codex CLI, and OpenCode.

- [pubfig](https://github.com/Galaxy-Dawn/pubfig)  
  A Python library for **publication-style scientific figures** with paper-ready defaults, clean export, and panel-first Figma assembly.  
  Unlike general plotting libraries that stop at figure generation, pubfig is designed around the **last mile of paper figures**: consistent aesthetics, journal-aware export, and a workflow for assembling multi-panel figures without redrawing them manually.

- [pubtab](https://github.com/Galaxy-Dawn/pubtab)  
  A tool for **bidirectional Excel↔LaTeX table conversion** with stable roundtrip behavior, style preservation, and preview support.  
  Its main focus is not only exporting tables, but making table editing and publishing more reliable in real research workflows, especially when users need to move repeatedly between spreadsheet editing, LaTeX formatting, and publication-ready output.

## Current interests

- Cross-subject neural decoding
- Brain-to-text decoding
- Reliable agent systems for scientific research
- Reproducible and maintainable research software

## Links

- Homepage: [galaxy-dawn.github.io](https://galaxy-dawn.github.io/)
- GitHub: [@Galaxy-Dawn](https://github.com/Galaxy-Dawn)
- Email: gaoruizhang@zju.edu.cn
