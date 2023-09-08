# Hackathon flier

## Setup

* Install Pandoc, LaTeX, etc
* Acquire [Eisvogel template](https://github.com/Wandmalfarbe/pandoc-latex-template/tree/master) and place template file in local Pandoc templates folder

## Generate

```
pandoc pamphlet.md -o pamphlet.pdf --from markdown --template eisvogel --listings
```