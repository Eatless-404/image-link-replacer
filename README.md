# Image Link Replacer

A single-file local tool for replacing image URLs in WeChat article HTML/SVG without changing the surrounding markup.

## Features

- Parse image positions from original HTML, including SVG `image href`, `img src`, and `img data-src`.
- Parse new image links from pasted URLs or pasted `<img>` HTML.
- Pair old image positions with new image links visually.
- Apply replacements by character range, so the HTML/SVG structure is not reserialized or reformatted.
- Copy or download the resulting HTML.

## Usage

Open `index.html` in a browser for the standard two-column workbench.

Open `wizard.html` for the experimental three-step wizard flow.

1. Paste the original HTML into the left input area, then click `解析原图位点`.
2. Paste the new image links or image HTML into the right input area, then click `解析新图链接`.
3. Click an old image card and a new image card, then click `建立配对`.
4. Click `应用替换`.
5. Copy the generated HTML or download it.

No server or AI API is required.
