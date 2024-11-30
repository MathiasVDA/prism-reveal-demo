# Prism Reveal Demo

This project demonstrates the use of Prism.js with Reveal.js to create beautiful presentations with syntax highlighting.

## Getting Started

To get started with this project, follow the instructions below.

### Prerequisites

None (or just a browser..)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/mathiasvda/prism-reveal-demo.git
   ```
2. Open index.html with your favorite browser

### Particularities

[A lot of options](https://prismjs.com/download.html) exist on how to download Prism js and css file. The prism installation in this repo is very minimal, only the sparql/turtle language and no plugins.

If you look in the prism/prism.css file, you will see:

```css
code[class*="language-"],
pre[class*="language-"] {
  display: block;
  overflow-x: auto;
  padding: 0.5em;
  background: #272822;
  color: #ddd;
}
```

And no other margins or paddings defined. This is not how you will download the css file from the prism website. So you'll need to adapt the file a little bit in order to make the code block look nice on a reveal presentation. The code block above comes from the highlight.js [built-in plugin of reveal](https://revealjs.com/code/).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
