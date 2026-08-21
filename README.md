# gitayon.github.io

Personal website of **Ayon** — philosophy undergraduate, apolitical writer, and open-source/Linux enthusiast.

Built as a lightweight, bloat-free static site hosted on **GitHub Pages**, inspired by traditional minimalist personal web pages.

---

## 📌 Features

* **Zero-Bloat Design:** Pure HTML with fast load times and no heavy JavaScript frameworks.
* **Mobile-Responsive:** Uses standard viewport scaling for optimal reading on screens of any size.
* **Automated Timeline:** A GitHub Actions workflow logs every site commit automatically into the homepage timeline.
* **Automated Article Directory:** Custom workflows parse HTML metadata to automatically update index listings when new posts are committed.

---

## 📁 Repository Structure

```text
.
├── index.html              # Main landing page
├── .nojekyll               # Disables Jekyll processing for static HTML
├── posts/                  # Written articles, essays, and notes
│   ├── example.html
│   └── more_example.html
└── .github/
    └── workflows/          # Automation scripts for timeline & post listings
