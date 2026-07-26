# Angelina's Nail and Beauty Salon

A small, multi-page website for a fictional nail and beauty salon, built with
plain HTML and CSS. No frameworks, no build step.

The site has four pages: a home page, an about page, a services listing, and a
contact form.

## Links

GitHub repo link: https://github.com/TamaraEverett/Beauty-Salon.git
GitHub live link: https://tamaraeverett.github.io/Beauty-Salon/

## Contents

| File             | Purpose                                                       |
| ---------------- | ------------------------------------------------------------- |
| `index.html`     | Home page — salon name, hero image, address and opening hours |
| `aboutus.html`   | About the salon and its services                              |
| `services.html`  | Card grid of the six treatments offered                       |
| `contactus.html` | Contact form (name, email, message)                           |
| `style.css`      | Shared stylesheet for all four pages                          |
| `manicures.jpgb` | Hero image used on the home page                              |

## Requirements

None. Any modern web browser will do.

## Installation

```bash
git clone https://github.com/TamaraEverett/Beauty-Salon.git
cd Beauty-Salon
```

## Usage

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

## Notes

The contact form has no `action` attribute and no backend, so submitting it
reloads the page rather than sending anything. Add a server-side handler or
point `action` at a form service to make it functional.

## Author

Tamara Everett
