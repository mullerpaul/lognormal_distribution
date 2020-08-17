# produce data with a lognormal distribution using Python
After listening to a Taleb podcast where he talked about lognormal and other "fat-tailed" distributions, I thought I'd like to try my hand at generating some data like that, then looking at its attributes (mean, histograms, etc).  I first thought about using my go-to tool of choice, a relational database; but then realized that this is a perfect opportunity to try something new - python running in a jupyter notebook.  I had to first get my python environment in order, installing pip, pandas, numpy, matplotlib, and jupyter.



create a new repo
```
git init lognormal_dist
cd lognormal_dist/
```

I needed to install pip so I could then install pandas, notebook, and then matplotlib
```
pip --version
sudo apt update
sudo apt install python3-pip
pip3 --version
pip3 install pandas
```

Install notebook into python environment and jupyter executable in OS.  I don't really understand this yet.
```
pip3 install notebook
sudo apt install jupyter-core
jupyter notebook
```

Now add python script location to path
```
export PATH="$HOME/.local/bin:$PATH" >> .bashrc
source .bashrc
```

finally inistall matplotlib for histogram graphs
```
pip3 install matplotlib
```
