# SanskritiVibes book images

Product images for the SanskritiVibes catalogue: the source site's corner
watermark removed and the SanskritiVibes logo applied.

Files are named by product **Barcode** (SKU), lowercased — `IDL031` becomes
`books/idl031.jpg`.

## Using these in Shopify

Put the raw URL in the product CSV's `Image Src` column. Shopify fetches each
image during the import and then serves it from its own CDN, so these links only
need to work while the import runs.

```
https://raw.githubusercontent.com/retailmaharaj/ShaheerFiverr/main/books/idl031.jpg
```

A CDN-backed alternative, better if anything hotlinks these directly rather than
copying them:

```
https://cdn.jsdelivr.net/gh/retailmaharaj/ShaheerFiverr@main/books/idl031.jpg
```

Both forms are **case-sensitive** and the file names are lowercase. Note that
`github.com/.../blob/...` is a web page, not an image — it will not work in an
image field.
