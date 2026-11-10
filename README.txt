SEVEN YEARS OF US — how to edit
================================

1. Open index.html in VS Code (or any text editor).
2. Scroll to the <script> part and find "const CONFIG = {".
   Every word on the page lives there: his name, the start date,
   the 7 island memories, the wish banner lines, the letter, and
   the co-op request. You don't need to touch anything else.
3. Save, then double-click index.html to open it in a browser.

Adding photos (optional)
- Put pictures in the "photos" folder, e.g. photos/year1.jpg
- In CONFIG, set that year's photo:  photo: "photos/year1.jpg"
- Leave photo: "" to show no picture.

Wish banner
- fourStar  = the common pulls (puns)
- fiveStar  = the rare pulls (sweet ones)
- fiveStarChance and pityLimit control how rare the 5-stars are.

Sending it to him
- Keep index.html and the photos folder together.
- To send one link, you can upload the folder to Netlify Drop
  (app.netlify.com/drop) or GitHub Pages.
