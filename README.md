# Meng Hao — Academic Homepage

Single-page static site hosted on GitHub Pages.

- `index.html` — all content (About, Research, Publications, Services)
- `styles.css` — black/blue theme
- `images/` — portrait

### Updating publications

Publications are listed inside `index.html` under `#pub-by-topic`,
grouped into four topic sections. Entry format:

```html
<div class="pub year-YYYY">
  <p class="title">TITLE <span class="details">[<a href="...">paper</a>, <a href="...">code</a>]</span></p>
  <p class="author"><u>Student</u>, Meng Hao, ...</p>
  <p class="venue">Venue, Year</p>
</div>
```

Ordering: newest year first; within a year, conferences before journals.
`<u>Underlined</u>` marks a student co-supervised by Meng Hao.
