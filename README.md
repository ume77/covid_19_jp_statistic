# covid_19_jp_statistic

## Abstract

Julia program of Japanese Covid-19 statistic which uses Japanese national government statistic data.

## How to run

### 1. Install Julia

[Julia Programming Language](https://julialang.org/downloads/)

### 2. Install dependent packages (Pkgs)
Start Julia REPL at first. For Windows cmd, enter this:
```
> julia
```
The prompt changes like:
```
julia>
```
Enter Pkg mode by pressing ```]``` key.
```
(@v1.8) pkg>
```
Add packages:
```
(@v1.8) pkg> add HTTP CSV DataFrames StringEncodings Plots
```
Exit by pressing ```backspace``` key.

### 3. Install JupyterLab

Install only [JupyterLab](https://jupyter.org/install) or [Anaconda](https://www.anaconda.com/products/distribution).

### 4. Start JupyterLab

Start JupyterLab from Command-Prompt or from Anaconda navigator.

### 5. Open and run Jupyter notebook file
```
covid_19_jp.ipynb
```

## How to select a different kernel

### 1. Install another version of Julia

### 2. Add IJulia Pkg
```
(@v1.8) pkg> add IJulia
```
### 3. Select kernel in JupyterLab

## Data
[Japanese government statistic data](https://www.mhlw.go.jp/stf/covid-19/open-data.html)
