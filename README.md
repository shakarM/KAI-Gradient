# KAI Gradient System

An internal tool for creating on-brand Kurdistan AI Initiative gradients and exporting them as PNG or PDF.

The whole tool is one file, `index.html`. Fonts (PP Telegraf, Archivo), the KAI logos and the PDF library are built in, so it makes no outside requests and works offline.

## Publish on GitHub Pages

1. Create a new repository on GitHub (private is recommended for internal use).
2. Upload the three files from this folder: `index.html`, `README.md` and `.nojekyll`.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute the tool is live at `https://<your-account>.github.io/<repository-name>/`.

Private repositories need a paid GitHub plan to use Pages. On a free plan, use a public repository or host the same `index.html` on any internal web server.

## Using it

1. **Style:** Mesh Flow, Abstract Field, Velvet Gradient, Atmospheric Grain or Atmospheric Motion.
2. **Colours:** white is on by default; click it to turn it off. Add KAI colours; the numbers show their order.
3. **Direction:** drag the dial, type a value from 0° to 359°, or use the 0°/90°/180°/270° buttons. With the dial focused, the arrow keys change it by 1° (hold Shift for 15°).
4. **Fine-tune:** grain and softness sliders, Still or Motion, and four shuffle buttons (colours, shape, style, everything).
5. **Format:** 12 sizes, from social posts to A4, A3, posters, roll-ups and billboards.
6. **Brand layer:** centre logo (logomark or full lockup), header and footer (each optional, logo on the left and text on the right), optional headline, black or white ink.
7. **Export:** PNG, or PDF. Print sizes export as PDFs at real paper size.

Favourites are saved in the browser on that computer only.

## Requirements

A current browser with WebGL turned on (the default in Chrome, Edge, Safari and Firefox).

## Internal use

This is an internal KAI tool. Keep it on an internal or access-controlled location.

Built with Archivo (SIL Open Font License) and jsPDF 2.5.1 (MIT License).
