# Python Series 02: Sinusoids, from math to code

Jupyter notebook that generates and plots sinusoidal signals with NumPy and
Matplotlib. The notebook combines the theory (Markdown cells) and the
implementation (code cells), and was improved in three successive stages.

## Development history

Each stage was developed on its own branch, reviewed by a teammate through a
pull request, and merged into `main` only after approval. The branches are kept
so that each stage of the work stays visible.

| Branch | What it adds | Why |
|---|---|---|
| `first-version` | Theory of the sine wave and a first plot, saved as PNG | Get a working result before worrying about quality |
| `better-version` | Cosine curve on a second y-axis, legend, PDF export | Compare two signals on one figure; PDF is a vector format, better for reports |
| `final-version` | `sinusoid` function, two frequencies, docstrings, checks, references | Remove the duplicated formulas and make the code reusable and readable by others |

## Why branches

Each branch isolates one stage of improvement, so `main` always holds a working
version while a new idea is being tried out. It also makes each pull request
easy to review, since it contains only the changes of a single stage.
Each branch was created from the previous one, so improvements build on each
other rather than diverging.

## Code review

The notebook was reviewed by Tuba in the
three pull requests above.

## Author

Alexis Lagarde - IEAP, Python series 02, September 2026
