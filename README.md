Repository for animations built using [manim](https://github.com/ManimCommunity/manim). 

# Installation steps that work on MacOS 11.2
```
$ conda create -n manim python=3.9 pycairo=1.20 ffmpeg jupyterlab ipython 
$ conda activate manim
$ git clone https://github.com/krassowski/jupyter-manim
$ cd krassowski/jupyter-manim
$ pip install .
$ git clone https://github.com/ManimCommunity/manim
$ cd ManimCommunity/manim
$ pip install .
$ python -m ipykernel install --user --name=manim
$ jupyter lab
```
