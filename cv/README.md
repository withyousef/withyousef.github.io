# CV page

Live at **https://withyousef.github.io/cv/**

This folder is self-contained. The course site at the repository root is untouched by it.

| File | What it is |
|---|---|
| `index.html` | The page. Everything inline — no build step, no dependencies. |
| `photo.jpg` | Portrait. If it is missing the page falls back to a "YZ" monogram. |
| `Yousef-Zakaria-CV.pdf` | What the Download button serves. **Keep this filename.** |

## Swapping the CV for a different role

The download URL is always:

```
https://withyousef.github.io/cv/Yousef-Zakaria-CV.pdf
```

To point it at a differently tailored version, overwrite `Yousef-Zakaria-CV.pdf`
with that version's PDF — keeping the filename — then commit and push:

```bash
git add cv/Yousef-Zakaria-CV.pdf
git commit -m "swap CV"
git push
```

Every link already sent out keeps working and starts serving the new file.

Source files live locally at `D:\01_Personal\CV\site`.
