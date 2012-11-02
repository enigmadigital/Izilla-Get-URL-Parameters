Izilla Get URL Parameters
===========================

### Gets "true" url parameters and adds them as classes to the html tag and to the izilla_gup object

eg. ``article.html?lightbox=true&mqdebug=true``

---

**Usage**

*CSS*

```
html.param {
	/* conditional styling */
}
```

*JavaScript*

```
if (izilla_gup.param) {
	// conditional scripting
}
```