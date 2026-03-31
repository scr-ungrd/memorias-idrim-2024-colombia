# Memorias de la 14° Conferencia Internacional IDRIM 2024 - Colombia

Welcome to the official repository for the digital book of the **14th International IDRIM Conference**, held in Colombia.

## Project Overview

This project is a **Quarto-based digital book** designed to provide an interactive and immersive experience for conference attendees and researchers. Unlike a standard static PDF, this digital version highlights:

- **Multimedia Content:** Integrated conference videos and presentations.
- **Interactive Elements:** Dynamic links, searchable indices, and responsive design.
- **Accessibility:** Optimized for web viewing on desktop and mobile devices.

The content focuses on **"Resilient Communities to Disasters for Life"**, capturing the essence of the discussions, plenaries, and sessions held during the event.

---

## Repository Structure

Descriptions of the `.qmd` files and folders (most content is in **Spanish**):

```text
.
├── .github/workflows/   # CI/CD pipelines (GitHub Actions for auto-deployment)
├── docs/                # Built files for GitHub Pages and the project PDF
├── plenarias/           # Plenary sessions content
├── sesiones-especiales/ # Special thematic sessions
├── sesiones-paralelas/  # Parallel research and technical sessions
├── _quarto.yml          # Core project configuration and sidebar definitions
├── index.qmd            # Digital book cover and main title page
├── introduccion.qmd     # Official introduction and conference context
├── indice.qmd           # Comprehensive interactive index
├── styles.css           # Global CSS styling
├── theme.css            # Base theme styles
└── theme.scss           # Advanced SASS-based theme customizations
```

---

## Getting Started

### Prerequisites

You need [Quarto](https://quarto.org/docs/get-started/) installed on your system.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/scr-ungrd/memorias-idrim-2024-colombia.git
   cd memorias-idrim-2024-colombia
   ```

2. **Render the book:**
   To build the complete project and generate the `docs/` folder:

   ```bash
   quarto render
   ```

3. **View locally:**
   To launch a live preview of the digital book in your browser:
   ```bash
   quarto preview
   ```

---

## Tech Stack

- **Framework:** [Quarto](https://quarto.org/)
- **Markup:** [Markdown](https://daringfireball.net/projects/markdown/)
- **Styling:** CSS & SASS
- **Automation:** GitHub Actions (Deployment to GitHub Pages)

---

## Supporting Organizations

This project is made possible thanks to the collaboration and support of the following organizations:

- **UNGRD** (Unidad Nacional para la Gestión del Riesgo de Desastres)
- **IDRIM Society** (International Society for Integrated Disaster Risk Management)
- **Supporting Universities and Research Centers**

---

_All content files (`.qmd`) are written in Spanish to maintain fidelity to the conference proceedings._
