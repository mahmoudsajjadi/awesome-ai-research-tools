# Publication-Grade LaTeX Best Practices

Checklist for preparing camera-ready conference and journal submissions:

### Typography & Tables
- Always use `booktabs` (`\toprule`, `\midrule`, `\bottomrule`) with zero vertical lines (`|`).
- Use `\resizebox` or `tabularx` to keep wide benchmark tables inside column boundaries.
- Ensure all numbers use math mode with units (e.g., `$35.7\,\text{mW/cm}^2$`).

### Cross-Referencing
- Never hardcode figure or table numbers; use `Figure~\ref{fig:arch}`, `Table~\ref{tab:bench}`, `Eq.~\eqref{eq:loss}`.
- Use tilde (`~`) before references to prevent line breaks between the label and reference number.

### BibTeX Sanitization
- Wrap acronyms and proper nouns in braces in `.bib` titles to preserve capitalization (e.g., `{EEG}`, `{PyTorch}`, `{LSTM}`).
- Provide full author lists rather than relying on automated `et al.` truncations in `.bib` databases.
