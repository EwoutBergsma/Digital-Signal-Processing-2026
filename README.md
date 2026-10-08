# Digital Signal Processing 2026

Course materials for Digital Signal Processing at Hanze University of Applied Sciences.

Lecturer Ewout Bergsma.

## Lectures

- [Lecture 1](lectures/01/README.md) covers signals and systems.
- [Lecture 2](lectures/02/README.md) covers convolution.
- [Lecture 3](lectures/03/README.md) covers the discrete Fourier transform.
- [Lecture 4](lectures/04/README.md) covers negative frequencies, spectral leakage and aliasing.

Each lecture folder contains HTML slides, a static PDF and exercises. Solutions are available for lectures 1–4 and are published separately from the exercise notebooks so you can complete the tasks first.

## Slides

Download the HTML file using GitHub's download button and open the saved file in a modern browser. GitHub's file view does not play the presentation. The HTML embeds its images, videos, styling and equations for offline use. Click a plot to view its Python code, then use Back to plot or Escape to return.

The PDF is a static reference. It does not play animations or show interactive code panels. Download the repository as a ZIP if you want all materials together, and preserve the lecture folder structure.

## Notebooks

Download the notebooks and open them in Jupyter. Exercise notebooks have empty answer cells. Solution notebooks contain worked code and saved outputs. Run cells from top to bottom.

Install the notebook dependencies in a Python environment.

```sh
python3 -m venv .venv
.venv/bin/python -m pip install -r requirements.txt
.venv/bin/python -m jupyter notebook
```

On Windows, use `.venv\Scripts\python.exe` instead of `.venv/bin/python`. NumPy, Matplotlib, SciPy, librosa and IPython are used by the notebooks. FFmpeg may be needed if your environment cannot decode MP3 audio.
