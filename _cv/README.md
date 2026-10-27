# CV source

`cv.html` is the source of `assets/pdf/cv.pdf`. The original was made in Apple Pages (Oct 2026) and the `.pages` file was lost, so the CV was rebuilt as HTML. Jekyll ignores this folder (leading underscore).

Rebuild the PDF after editing `cv.html`:

```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless=new --disable-gpu \
  --no-pdf-header-footer --print-to-pdf="assets/pdf/cv.pdf" "file://$PWD/_cv/cv.html"
```
