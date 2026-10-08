Updated site structure

Files:
- index.html        Landing page
- research.html     Research page
- projects.html     Projects page
- styles.css        Shared styling
- script.js         Shared JavaScript
- assets/           Images + CV

For your portrait:
1. Put a portrait image at assets/portrait.jpg
2. In index.html replace:

<div class="portrait placeholder">
  <span>Add portrait photo</span>
</div>

with:

<div class="portrait">
  <img src="assets/portrait.jpg" alt="Robert Pitu">
</div>

For project/research images, replace placeholder divs with <img> tags in the same way.
