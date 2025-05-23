# Generative Energy: Protecting and Restoring the Wholeness of Life

<div align="center">
  <img src="https://github.com/user-attachments/assets/9048c107-b0d3-43b6-be82-ff6f911c5b52" width="270" height="420" alt="Book Cover">
  
  <br>
  <br>

  [![Follow @ibuybooks](https://img.shields.io/badge/Follow%20%40ibuybooks-000000?logo=X&logoColor=white&style=for-the-badge)](https://x.com/ibuybooks)
  [![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)](#)
  [![Lua](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)](#)
  [![License](https://img.shields.io/badge/Free%20for%20Non--Commercial%20Use-007bff?style=for-the-badge&logo=github&logoColor=white&labelColor=282828&color=007bff)](#)
  ![Made with ❤️ by Gavin](https://img.shields.io/badge/Made_with_❤️_by-Gavin-red?style=for-the-badge)
      
  [![Stars](https://img.shields.io/github/stars/ibuybooks/generative-energy?style=for-the-badge&color=2F323A)](https://github.com/ibuybooks/generative-energy/stargazers)
  [![Size](https://img.shields.io/github/repo-size/ibuybooks/generative-energy?style=for-the-badge&color=2F323A)](https://github.com/ibuybooks/generative-energy)
  [![Downloads](https://img.shields.io/github/downloads/ibuybooks/generative-energy/total?style=for-the-badge&color=2F323A)](https://github.com/ibuybooks/generative-energy/releases)

  <br>

  >*Energy is the Only Life, and is from the Body... Energy is Eternal Delight.*
  >
  > — William Blake
</div>

<br>

<div align="center">
  <h2>⚡ Quick Start</h2>
  <h3>Download Latest Release</h3>
  <p>Download the Latest Pre-Built PDF Release</p>
  
  [![Download][Download-Badge]][Download-Link]

  [Download-Badge]: https://img.shields.io/badge/Download_Latest_Release-2563eb?style=for-the-badge&logo=github&logoColor=white&labelColor=1e40af
  [Download-Link]: https://github.com/ibuybooks/generative-energy/releases/latest/
  
  <sup>📖 See README for More Information</sup>
</div>

<div align="center">
  <h2>📌 README</h2>
</div>

<h3>📎 About:</h3>

This Project Is a Faithful LuaLaTeX Remaster of Dr. Raymond F. Peat, Ph.D.'s *Generative Energy* (Originally Published in 1994), Which Attempts to Restore the Original Low-Quality Book to a Clean and High-Quality Format While Maintaining the Look and Feel of the Original Book.

<h3>📏 Improvements:</h3>

- Consistent Font Sizes, Kerning, and Weights
- Standardized Figure Labeling Style
- Standarized Reference Styles
- Normalized Spacing Between Paragraphs and Elements
- Fixed Grammar Mistakes
- Normalized Image Rotation and Centering
- Brand New Figures
- Higher Quality Images
- Clean Graphs

<h3>🔖 Notes:</h3>

- 135×210mm Paper Size
- 164 Pages
- PDF/A-2u Compliant

<h3>🧮 Project Structure:</h3>

```
.
├── Chapters/                    # Book Content
│   ├── Part-{One,Two,Three}.tex # Parts
│   └── Chapter-*.tex            # Chapters
│
├── Font/Times New Roman/        # Font files
│   └── *.ttf                    # Regular, Bold, Italic, BoldItalic
│
├── FrontBack/                   # Front and Back Matter
│   ├── {Front,Back}-Cover.pdf   # Cover Files
│   ├── Blake.tex                # Blake Artwork Page
│   ├── Introduction.tex         # Introduction
│   ├── Peat.tex                 # Books and Newsletter Ad
│   ├── Title.tex                # Title Page
│   ├── ToC.tex                  # Table of Contents
│   └── Vernadsky.tex            # V. I. Vernadsky Page
│
├── Images/                      # Images
│   ├── Drawings/                # Drawings
│   ├── Graphs/                  # Graphs
│   ├── Maps/                    # Maps
│   │   └── Data/                # Geographical Data (from PST-GEO)
│   └── Pictures/                # Photographs and Figures
│
└── GenerativeEnergy.tex         # Main Document
```

<div align="center">
  <h2>⚒️ Building from Source</h2>
</div>

<h3>📄 Instructions:</h3>

```bash
# Install TeX Dependencies
tlmgr install fontspec geometry microtype fancyhdr tocloft parskip \
              graphicx titlesec pdfpages luacode pdfx tikz \
              varwidth pgfplots pst-geo etoolbox

# Clone the Project
git clone https://github.com/ibuybooks/generative-energy.git
cd generative-energy

# Compile the Book (Run Twice for Table of Contents)
lualatex GenerativeEnergy
lualatex GenerativeEnergy
```
