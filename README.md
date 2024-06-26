# install manim in Linux

## Create and activate virtual env

### create

```
python3 -m venv myenv
```

### activate 

```
source myenv/bin/activate
```

## Install dependencies

```
sudo apt update
sudo apt install build-essential python3-dev libcairo2-dev libpango1.0-dev ffmpeg
```

## Install manim

```
pip3 install manim
```

## Optional dependencies - Latex

```
sudo apt install texlive texlive-latex-extra
```




