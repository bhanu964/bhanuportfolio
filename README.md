# Portfolio — Bhanu Prasad

Personal portfolio site. Static: one `index.html`, one image, no build step.

- **Live:** deployed on Vercel
- **Résumé:** [`resume/Bhanu_Prasad_Resume.pdf`](resume/Bhanu_Prasad_Resume.pdf)

## Contents

| Path | What it is |
|---|---|
| `index.html` | The whole site — inline CSS and JS, no dependencies |
| `bhanu.jpeg` | Portrait |
| `resume/Bhanu_Prasad_Resume.pdf` | Résumé, linked from the site's download button |
| `vercel.json` | Cache headers |

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000

## Notes

Fonts load from Google Fonts; everything else ships with the page. The site opens
in light mode for every visitor and remembers a dark-mode choice in `localStorage`.
