# Non-ASCII anchor bug (Firefox)

Summary: Unwanted scroll back to non-ASCII anchor on reload

Steps to reproduce:

1. Get the attached `anchors.html`
2. Open `file:///path/to/anchors.html#中文` in Firefox
3. Scroll away from the "Non-ASCII anchor" heading
4. Reload the page

Expected behaviour:
- Page preserves the new scroll position on reload

Observed behaviour:
- Page scrolls back to the "Non-ASCII anchor" heading

---

Note: the expected behaviour is observed for `file:///path/to/anchors.html#ascii`.
