# Covid-19_Modeling
Exploration of how using epidemiological models to simulate the COVID-19 pandemic's dynamics affects its development in a community. The model used for this analysis was developed by the [Neherlab](https://github.com/neherlab/covid19_scenarios) group. It is a deterministic SEIR comparimental moment, with the ability for the user to input specific intervention measures. 

This code was created for the University of Edinburgh's [Senior Honours Group project](http://www.drps.ed.ac.uk/19-20/dpt/cxphys11011.htm) in my 4th year. The title of our report is: "Testing Covid-19 intervention measures against epidemiological models".

## Data
Data is downloaded from https://covid19-scenarios.org as a .tsv file.

## Usage

`python plots.py --models <directory of model 1 .tsv file> <directory of model 2 .tsv file>`

Note: Multiple models can be added and run with a single run.

Example: `python plots.py --models lock_5m_simlarge`

## Repository navigation

| Folder        | Description              |
| ------------- |-------------------------:|
| Data          | exported data (.tsv)     |
| Notebooks     | Trial stage of code      |
| Plots         | exported plots from model|
| Tables        | results from runs        |

## Sample Results

![](base_final_trajectories_nolog.png)

![](plots/lock_5m_simlarge_piechart.png)

## Acknowledgements 

I want to thank [Tom Bramwell](https://github.com/tomb2412) for his contribution in this analysis.
