# messy-notes-clean-ledger
GenAI app that converts messy expense notes into a clean ledger using an open-source LLM

**Output**
- 4 expense items
- Categorized (Transport, Food, Rent)
- Split logic inferred
- Confidence per row
- Warnings for missing dates
- CSV download

---

## Limitations

- Natural language ambiguity can reduce confidence
- Dates and currencies may be inferred if missing
- Model accuracy depends on clarity of input
- Designed for small personal inputs (not enterprise scale)

These limitations are **explicitly surfaced** to the user.

---

## Future Improvements

- Editable table with re-balancing (“Reconcile” mode)
- Receipt image input (OCR)
- Persistent storage (database)
- Mobile-friendly UI
- Multi-currency support

---

## Why this matters

This project demonstrates:
- Practical GenAI engineering (not just prompting)
- Handling unreliable model outputs safely
- Deploying a usable AI system without paid APIs
- Clear separation between generation and validation

It’s a small project — intentionally — but built with real-world GenAI patterns.

---

## Author

Built by **Abhishree**  
Graduate-level engineering student exploring applied ML & GenAI systems.
