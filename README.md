# DispAnalysisModel-SEB

## Running the Notebook:

1. Run `pip install -r requirements.txt`. This will install all necessary python libraries to run the notebooks for analysis.
2. Configure your python environment. You may use a `Conda` environment or another to your liking. I personally used the 3.11.4 global env kernel.

## To Do List:

- X and Y standard deviation from a. the Center of landing site, and b. the launch site
- Confidence interval (start with 95 and 99.5) of rocket landing distance to the launch site. Ideally this includes direction, cuz a lot of the rockets land in the bottom right corner, and not the top left, so having that in consideration
- Take the 300 samples (or more if you think is necessary), and use that to estimate the population mean within a CI (say 95%)
- Ultimate goal is to have a heat map overlaid over the FAR map with different probabilities of landing at that spot
