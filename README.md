# SmartProposal: AI-Powered Grant Writing for Nonprofits

SmartProposal is a generative AI tool designed to help nonprofits automatically generate tailored grant proposals using their mission statement and real-time Canadian government data.

## What It Does
- Takes in a nonprofit's mission statement
- Uses Google Gemini to extract structured metadata (focus areas, region, keywords)
- Matches relevant grants from live Canadian datasets
- Generates a complete proposal (title, summary, objectives, activities, impact, funding)
- Outputs structured JSON and allows export to PDF/Word

## Live Demo
You can run the full pipeline in this [Kaggle Notebook](#) https://www.kaggle.com/code/charanyaramprasad/smartproposal-grant-writing-for-nonprofits

## Tech Stack
- [Gemini 2.0 Flash (Google AI Studio)](https://deepmind.google/technologies/gemini)
- Python (pandas, ipywidgets, json)
- Real-time grant data from [Open Canada](https://open.canada.ca/data)
- Kaggle Notebooks for UI + interactivity
- Optional: PDF/Word export using `fpdf` and `python-docx`

## Project Structure
```
SmartProposal/
├── SmartProposal.ipynb               # Main interactive notebook
├── README.md                         # This file
└── /assets                           # (optional) for screenshots or logos
```

## Setup Instructions
No installation required if using Kaggle. Just open the notebook and run it.

Set up your Google API Key using an environment variable or Kaggle Secrets.

## Screenshots
> *(Optional section: add screenshots from your notebook if desired)*

## Let's Connect
If you're a nonprofit, civic lab, or builder interested in adapting SmartProposal:

- 📬 Email: charanya.ramprasad [at] gmail [dot] com  
- 🔗 LinkedIn: https://www.linkedin.com/in/charanyaramprasad/

---

## 📄 License
MIT License — feel free to fork, modify, or use for impact-driven purposes. Attribution is appreciated!

