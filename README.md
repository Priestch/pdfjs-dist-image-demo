# PDF.js Node Image Example
I use the 3.x pdfjs-dist, because the latest pdf.js use esm module, which I think may not compatible with the `canvas` package.

The examples directory was copied from latest pdf.js. You can compare the difference with the `pdf2png.js` file.

# Get Started
```bash
# Make sure you use node v18.x.
npm install

node pdf2png.js
# It should show some message like this
# Warning: Cannot polyfill `Path2D`, rendering may be broken: "Error [ERR_PACKAGE_PATH_NOT_EXPORTED]: No "exports" main defined in /tmp/pdfjs-dist-image-demo/node_modules/path2d-polyfill/package.json".
# # PDF document loaded.
# Finished converting first page of PDF file to a PNG image.
```
