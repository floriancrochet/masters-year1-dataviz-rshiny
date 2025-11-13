# Legislative Elections 2024 — Shiny Web Application  
*A pedagogical R Shiny app for exploring and understanding the French legislative elections.*

---

## 📘 Overview
This project is an **interactive R Shiny application** designed to **inform users about the French legislative elections of 2024** through interactive visualizations, tables, and textual explanations.  

Developed as part of an academic **Shiny training project**, it combines web interactivity with data analysis and visualization to improve understanding of electoral mechanisms and party programs.

**Objectives**
- Present the functioning and importance of legislative elections in France  
- Visualize electoral results by city and constituency  
- Provide summaries of political parties’ programs  
- Allow users to explore information dynamically via maps, tables, and modals  

---

## ⚙️ Features
- Interactive navigation through multiple tabs (`navbarPage`)  
- Integrated **maps** with `leaflet` for exploring constituencies  
- **Dynamic tables** built with `DT`, including row color coding by political party  
- **Modal windows** displaying detailed party programs and downloadable PDF files  
- **Textual explanations** and **HTML content rendering** for contextual education  
- **Interactive graphics** rendered with `ggiraph`  

---

## 🧰 Tech Stack
**Language:** R  
**Framework:** Shiny  
**Libraries:**  
- `shiny`, `shinythemes`, `shinyjs`  
- `leaflet` (interactive maps)  
- `DT` (dynamic tables)  
- `stringi`, `dplyr`, `tidyr` (data manipulation)  
- `ggiraph` (interactive plots)  
- HTML and CSS integration for styling  

---

## ⚙️ Installation
To run the application locally:

```bash
# Install required packages if not already installed
install.packages(c("shiny", "shinythemes", "shinyjs", "leaflet", "DT", "stringi", "dplyr", "tidyr", "ggiraph"))

# Launch the app
library(shiny)
runApp("path/to/app")
```

> À compléter : Add GitHub repository URL or deployment instructions if available.

---

## 📚 Usage Example

```r
# Run the app locally
shiny::runApp("path/to/legislatives2024_app")
```

The application opens in a browser window.  
Users can navigate through tabs to:
- Read contextual information on elections  
- Search for a city and visualize its results  
- Display party programs and download associated PDFs  
- Explore interactive tables and maps  

---

## 📂 Project Structure

```
legislatives2024_app/
│
├── www/                 # Static assets (images, CSS, PDFs)
├── data/                # Electoral datasets (local and national)
├── app.R                # Main Shiny app file
├── server.R             # Server logic (if separated)
├── ui.R                 # User interface (if separated)
└── README.md
```

> À compléter : Confirm exact structure and file organization.

---

## 📊 Results
The application produces:
- **Interactive maps** of constituencies with tooltips and dynamic zoom  
- **Candidate tables** filtered by city or constituency, color-coded by party  
- **Downloadable party programs** as PDF files  
- **Dynamic modals** summarizing each party’s main policy proposals  

Example visualization:

> À compléter (insert screenshot or GIF of the app interface)

---

## 🧠 References
- *support_formation_rshiny.pdf* — Training material on R Shiny structure, UI/server logic, and reactivity  
- Posit Shiny Gallery — https://shiny.posit.co/r/gallery/  
- Official Shiny documentation — https://shiny.posit.co/  
- Data sources for the 2024 French legislative elections (to be specified)  
> À compléter : Specify data provenance and bibliography if applicable.

---

## 📜 License
This project is released under the **MIT License**.  
© 2025 Juliette Grison and Florian Crochet

---

## 👤 Authors
**Juliette Grison**  
[GitHub Profile](https://github.com/juliette-grison)  

**Florian Crochet**  
[GitHub Profile](https://github.com/floriancrochet)

*Master 1 – Econometrics & Statistics, Applied Econometrics Track* 

---

## 💬 Acknowledgments
Based on training resources from *support_formation_rshiny.pdf* and developed as part of an academic project on interactive data applications using R Shiny.  
Special thanks to the R and Shiny open-source communities.
