# TemplatePage – Machine Knowledge Hub

**Live Site**: [https://jhherre3.github.io/Machine-Knowledge/](https://jhherre3.github.io/Machine-Knowledge/)

---

## 🛠 Purpose

TemplatePage is a lightweight internal documentation system built for machine operators, engineers, and manufacturing teams.

It enables fast access to:
- Job setup guides
- Tooling offsets
- Maintenance procedures
- Troubleshooting documentation

Designed for on-the-floor usability with a searchable UI and modular folder system. This template currently supports the **Mill Machine**.

---

## Folder Structure

```bash
/overview/
  ├─ specs.html              # Machine specifications (e.g., RPM, spindle type)
  └─ controls.html           # Control panel functions and layout

/jobs/
  ├─ setup-threading.html    # Setup instructions for M6 thread drilling
  └─ setup-bore.html         # Setup for Ø10mm precision bore

/tooling/
  ├─ tool-list.html          # Tool ID list with functions
  └─ offsets.html            # Tool offset values and zeroing instructions

/maintenance/
  ├─ daily-checklist.html    # Pre/post shift checklist
  └─ preventive.html         # Preventive maintenance tasks and intervals

/forum/
  ├─ common-errors.html      # Known machine errors and fixes
  └─ operator-notes.html     # Notes, tips, and logs from operators
