# Non-ASCII anchor bug (Firefox)

Steps to reproduce:

1. Open `file:///path/to/anchors.html#中文` in Firefox
2. Scroll away from the "Non-ASCII anchor" heading
3. Refresh the page

Expected behaviour:
- Page preserves the new scroll position on refresh

Observed behaviour:
- Page scrolls back to the "Non-ASCII anchor" heading

---

Note: the expected behaviour is observed for `file:///path/to/anchors.html#ascii`.
