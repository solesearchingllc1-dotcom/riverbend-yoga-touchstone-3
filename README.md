# North Star Bakery — Touchstone 4

Student demonstration website based on the North Star Bakery client and provided media.

## Pages
- index.html — home
- products.html — product favorites saved with localStorage
- about.html — bakery introduction and provided media
- contact.html — validated inquiry form with remembered email and request type

## Preview and publishing
Open index.html in a browser or run `python -m http.server 8000` in this directory and visit http://localhost:8000. To get a public link, upload these files to a public GitHub repository and enable GitHub Pages (Deploy from branch / main / root). Copy the published URL and repository URL into the Word template. No public URL has been created automatically.

## Testing
1. Open Products, save two favorites, refresh and confirm they remain.
2. Open Contact, submit blank form, confirm three nearby error messages.
3. Enter a malformed email and short message; confirm submission blocked.
4. Enter a valid email and choose Preorder; refresh and confirm both values return.
5. Fill valid inputs and confirm demo-only success message.
