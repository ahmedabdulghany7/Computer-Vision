# Computer Vision

Notes and hands-on labs from my computer vision learning path, building toward 3D vision, sensor fusion, and autonomous vehicles perception.

## Why This Repo

The goal is deep understanding before moving into autonomous vehicles perception. Every concept is studied first, explained in my own words, then implemented in code by hand. Mistakes and failed attempts stay in the repo, because they are part of learning.

## Structure

```
computer-vision/
├── README.md
├── ROADMAP.md          # Progress table
├── requirements.txt
├── data/               # Shared sample images used by the labs
├── templates/          # Empty starting files for notes, labs, and papers
├── papers/             # Reading list and notes on key CV papers
├── notes/              # Concept explanations, math, and theory (my own words)
│   ├── 01-fundamentals/
│   ├── 02-image-processing/
│   ├── 03-features/
│   ├── 04-camera-geometry/
│   ├── 05-motion/
│   └── 06-3d-vision/
└── labs/               # Hands-on implementations, same numbering and names as notes/
    ├── 01-fundamentals/
    ├── 02-image-processing/
    ├── 03-features/
    ├── 04-camera-geometry/
    ├── 05-motion/
    └── 06-3d-vision/
```

Every concept gets a matching note and lab with the same name:

```
notes/01-fundamentals/convolution.md
labs/01-fundamentals/convolution/
├── README.md            # What I built, results, what went wrong
├── convolution.ipynb    # Step by step exploration with plots
├── main.py              # Clean final version, runs from the terminal
└── results/             # Output images
```

## How to Use This Repo

1. Pick a topic from [ROADMAP.md](ROADMAP.md).
2. Read the note first for the idea and the math.
3. Open the notebook to follow the implementation step by step.
4. Run `main.py` to see the final version in one go.

## Setup

```bash
git clone https://github.com/ahmedabdulghany7/Computer-Vision.git
cd Computer-Vision
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Run a lab:

```bash
python labs/01-fundamentals/convolution/main.py
jupyter lab labs/01-fundamentals/convolution/convolution.ipynb
```

No local setup? Every notebook has an **Open in Colab** badge at the top.

## Roadmap

Fundamentals → Image Processing → Feature Detection → Camera Geometry → Motion & Optical Flow → Stereo & Depth → 3D Vision

Progress is tracked in [ROADMAP.md](ROADMAP.md). Papers are tracked in [papers/](papers/). This repo is a living log. It grows as I go.

## Resources

- *Computer Vision: Algorithms and Applications*, Richard Szeliski (2nd edition)
- *First Principles of Computer Vision*, Shree Nayar (Columbia, YouTube)
- CMU 16-385 Computer Vision, Kris Kitani

## Background

Background in AI/ML (TensorFlow, PyTorch, CUDA, OpenCV), now focused on building a solid computer vision foundation for perception-focused autonomous vehicles work.

## Author

**Ahmed Abdulghany**

[GitHub](https://github.com/ahmedabdulghany7) · [LinkedIn](https://www.linkedin.com/in/ahmedabdulghany)

All notes, code, and notebooks in this repo are written by me.

## License

[MIT](LICENSE) © Ahmed Abdulghany
