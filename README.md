[README.md](https://github.com/user-attachments/files/31062668/README.md)
# chickendrumsticks.net

A little webcomic / sketch gallery. Static site (plain HTML, CSS, and vanilla JS), hosted on GitHub Pages at [chickendrumsticks.net](https://chickendrumsticks.net).

## Adding a new sketch

1. Drop the image into the `comics/` folder.
2. Add a new object to the top of the `COMICS` array in `data.js`:

   ```js
   {
     id: 2,                             // next number up
     title: "My New Sketch",
     img: "comics/your-image.jpg",
     alt: "Short description for accessibility",
     hover: "Hover text / caption joke",
     date: "2026-03-01"                 // YYYY-MM-DD
   },
   ```

That's it — `index.html` and `archive.html` update themselves from the array.
