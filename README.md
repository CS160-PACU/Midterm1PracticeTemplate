
### To export to PDF
https://nbconvert.readthedocs.io/en/latest/install.html#installing-tex

```sudo apt-get install texlive-xetex texlive-fonts-recommended texlive-plain-generic

python -m pip install nbconvert
python -m pip install nbconvert[webpdf]

sudo apt-get update
sudo apt-get install texlive-xetex texlive-fonts-recommended texlive-plain-generic
```

matplotlib widgets (this is unnecessary now):

https://ipywidgets.readthedocs.io/en/stable/user_install.html#installing-in-jupyterlab-3-x

```conda install -c conda-forge jupyterlab_widgets
conda install -c conda-forge ipywidgets```
