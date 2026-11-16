# Templates

Empty starting files I copy for every new topic. Headings only, the content is written after studying the topic.

| Template | Copy to |
|----------|---------|
| `note.md` | `notes/XX-section/topic-name.md` |
| `lab-README.md` | `labs/XX-section/topic-name/README.md` |
| `lab-main.py` | `labs/XX-section/topic-name/main.py` |
| `lab-notebook.ipynb` | `labs/XX-section/topic-name/topic-name.ipynb` |
| `paper.md` | `papers/YYYY-short-name.md` |

Quick start for a new topic (example: convolution in 01-fundamentals):

```bash
T=convolution; S=01-fundamentals
cp templates/note.md notes/$S/$T.md
mkdir -p labs/$S/$T/results
cp templates/lab-README.md labs/$S/$T/README.md
cp templates/lab-main.py labs/$S/$T/main.py
cp templates/lab-notebook.ipynb labs/$S/$T/$T.ipynb
```
