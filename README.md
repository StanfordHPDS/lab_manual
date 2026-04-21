Lab manual for Health Policy Data Science Lab members working with Sherri Rose at Stanford University.

### Package environment setup

Python packages are managed with [uv](https://docs.astral.sh/uv/), and R packages are managed with [renv](https://rstudio.github.io/renv/index.html).

For Python, run:

```bash
uv sync
```

For R, first install R 4.5.3 with [rig](https://github.com/r-lib/rig):

```bash
rig add 4.5.3
```

rig will tell you the specific name for the installation (or you can check `rig list`), which you can set to the default R version with `rig default <name>`.

Then, in R:

```r
renv::restore()
```

### Rendering

We use [Quarto](https://quarto.org/) to render this manual:

```bash
quarto preview
```
