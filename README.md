[README-1.md](https://github.com/user-attachments/files/27762640/README-1.md)

# Bootstrap Calculator

A calculator I built as a frontend practice project using Bootstrap 5 and vanilla JS. Went with a retro dark theme because I wanted to try something different from the usual clean white style.

![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?logo=bootstrap&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)

---

## About

This started as a simple calculator exercise but I ended up spending more time on the styling than the logic honestly. The whole thing is one HTML file — no build tools, no npm, just Bootstrap loaded from CDN and some custom CSS/JS.

The display shows your current expression as you type, which I found really useful compared to calculators that just show the current number.

---

## What it can do

- Basic math: add, subtract, multiply, divide
- Chain operations without hitting equals each time
- Toggle positive/negative with the ± button
- Quick percentage with %
- Handles divide-by-zero without breaking (shows an error and resets)
- Works with your keyboard too, not just mouse clicks

---

## Try it out

Clone the repo and just open `calculator.html` in your browser — that's it, no setup needed.

```bash
git clone https://github.com/YOUR_USERNAME/calc-9000.git
cd calc-9000
# open calculator.html in your browser
```

Or check the live version on GitHub Pages:
https://YOUR_USERNAME.github.io/calc-9000/calculator.html

---

## Keyboard shortcuts

| Key | What it does |
|-----|--------|
| `0` – `9` | Type a digit |
| `+` `-` `*` `/` | Operators |
| `Enter` or `=` | Get the result |
| `Backspace` | Delete last digit |
| `Escape` | Clear everything |
| `%` | Percent |

---

## Stack

Just the basics:

- Bootstrap 5.3 (CDN)
- Vanilla JS — no jQuery or anything extra
- Google Fonts (Bebas Neue + Share Tech Mono for the retro display look)

---

## What I learned

Mostly practiced CSS custom properties and grid layout for the button pad. The hardest part was handling chained operations correctly — getting `3 + 5 × 2` to chain properly took a few tries.

---

## License

MIT, do whatever you want with it.
