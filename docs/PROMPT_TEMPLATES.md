# Prompt Templates for Scientific Literature & Writing

Structured prompt templates designed for academic researchers, graduate students, and postdocs.

---

## 1. Paper Abstract Condensation

```text
Task: Summarize this academic manuscript draft into a 150-word structured abstract.
Structure required:
- Background: 1-2 sentences stating the core problem.
- Gap / Limitation: 1 sentence explaining why existing baselines fail.
- Methodology: 1-2 sentences specifying the architecture and mathematical constraints.
- Results: 1-2 sentences highlighting concrete quantitative metrics (e.g. AUROC, latency).
- Conclusion: 1 sentence summarizing broader implications.
Draft:
[Paste manuscript draft]
```

---

## 2. Peer Review Rebuttal Formulation

```text
Task: Draft an objective, respectful rebuttal point addressing Reviewer 2's comment.
Reviewer Comment:
"[Paste reviewer critique regarding experimental sample size / baseline comparison]"
Author Findings:
- We conducted additional 5-fold cross-validation with N=1,440.
- AUROC improved from 0.891 to 0.934 with p < 0.01.
Tone: Collegial, scientifically rigorous, and appreciative of reviewer feedback.
```

---

## 3. LaTeX Equation Proofreading

```text
Task: Verify mathematical notation consistency across this section.
Checklist:
- Ensure all vectors are bolded (\mathbf{v}) and matrices are uppercase (\mathbf{W}).
- Verify that summation indices match equation bounds.
- Ensure all variables are defined in the text immediately following the equation.
LaTeX Snippet:
[Paste LaTeX math block]
```
