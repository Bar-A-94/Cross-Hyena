# Cross-Hyena

Welcome to **Cross-Hyena**, a collaborative project exploring how cross attention mechanisem for Hyena (a multi-domain extension of Hyena) can improve fusion of different domains. We leverage the State-Space Model (SSM) paradigm from Hyena to handle large context inputs and effectively fuse multiple input streams.

## Table of Contents
- [Background](#background)
- [Project Goals](#project-goals)
- [Features](#features)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Background
**Hyena** is a specialized SSM-based architecture designed to handle extremely long sequence contexts more efficiently than standard Transformers. 

**Cross-Hyena** extends Hyena by introducing cross-attention between multiple input domains (e.g., text, images, or other feature streams). 

	Our first goal is to integrate this approach to improve ChatNT’s results for genomic Q&A tasks.

---

## Project Goals
1. **Implement Cross-Hyena**: Adapt the existing Hyena codebase to allow parallel processing of multiple modalities (e.g., user queries, external knowledge bases) and fuse them via cross-attention.
2. **Enhance ChatNT**: Integrate Cross-Hyena within ChatNT’s architecture, replacing or supplementing the existing attention mechanism for better performance.
3. **Benchmark & Evaluate**: Compare the new Cross-Hyena–powered ChatNT against baseline models in terms of:
   - Accuracy / Relevance of responses  
   - Ability to handle long contexts  
   - Computation efficiency and scalability

---

## Features
- **Multi-Domain Fusion**: Demonstrates how to incorporate text from multiple sources into a single ChatNT response pipeline.
- **Extended Context Handling**: Leverages Hyena’s SSM to handle longer conversation threads or large knowledge bases.

---

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YourUsername/Cross-Hyena-ChatNT.git
   cd Cross-Hyena-ChatNT
   ```
2. **Create / Activate a Virtual Environment (recommended):**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Linux/Mac
    # or
    venv\Scripts\activate      # On Windows
    ```
3. **Install Requirements**:
    ```bash
    pip install -r requirements.txt
    ```

## Contributing
We welcome contributions from everyone! Here’s how you can help:
- **Issues**: Submit bug reports, feature requests, or questions.
- **Pull Requests**: Fork this repo, create a feature branch, implement your changes, and open a PR.
- **Discussions**: Start a new discussion in the GitHub “Discussions” tab if you have broader ideas or suggestions.

## License
    TBW

## Contact
- **Maintainers**: Bar, Taimoor

Thanks for checking out Cross-Hyena! We’re excited to see how this work evolves and look forward to collaborating with others in the community.

