# Normative Obligation Network Theory (NONT)

This repository contains the full LaTeX source for the paper:

**"Normative Obligation Network Theory (NONT): A Relational Model of Agency in Moral Space"**  
_A formal and conceptual framework for modeling moral agents as nodes in a network of directed obligations._ \
I affectionately called this _The Shape of The Soul_.

---

## 📖 Overview

**NONT** proposes a new way to think about moral agency—not as a self-contained bearer of duties and rights, but as a node embedded in a dynamic network of obligations. The model draws on insights from:

- Deontic logic
- Graph and network theory
- Metaethics and relational ethics (e.g. Scanlon, Darwall, care ethics)

Using elementary mathematics, NONT visualizes the moral structure of agents and makes relational asymmetries explicit and analytically tractable.

---

## 🗂️ Repository Structure
nont-paper/
- main.tex # LaTeX source of the paper
- bibliography.bib # BibTeX references (optional; inline in main.tex by default)
- README.md # This file
- figures/ # Directory for any diagrams or TikZ exports (optional)
- nont-diagram.tex # TikZ source for network visualizations (optional)


---

## 🧠 Key Concepts

- **Agents as Nodes**: Each moral agent is a node in a directed graph.
- **Obligations as Edges**: A directed edge from A to B represents A’s obligation to B.
- **Normative State**: The net balance of incoming and outgoing obligations.
- **Equilibrium and Injustice**: The model allows us to theorize about fairness, power asymmetries, and moral repair.

---

## 📄 Paper Structure

1. Introduction
2. Related Work (Darwall, Scanlon, deontic logic, networks)
3. Formal Model of NONT
4. Applications (contractualism, care ethics, injustice)
5. Limitations and Extensions
6. Conclusion
7. References

---

## 🔧 How to Compile

To compile the LaTeX document:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex

🏛️ Citation
If you reference or build upon this work, please cite as:

@unpublished{nont2025,
  title     = {Normative Obligation Network Theory (NONT): A Relational Model of Agency in Moral Space},
  author    = {Vynn Suren},
  year      = {2025},
  note      = {Manuscript under review},
}

🤝 Contributing
Feedback, corrections, and theoretical extensions are welcome! Please open an issue or submit a pull request if you’d like to:

Suggest clarifications or examples

Add visual diagrams of obligation networks

Propose extensions (e.g., temporal or probabilistic dynamics)

📬 Contact
For comments, questions, or collaboration:
Email: surenvynn@gmail.com
GitHub: @SurenVynn

🧾 License
This work is shared under the MIT License. You are free to share and adapt the material with attribution.

“Morality is not a substance in the soul but a current in the structure.”
— NONT Principle
