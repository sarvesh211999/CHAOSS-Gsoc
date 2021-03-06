# CHAOSS-Gsoc

To Launch the repository in Real Time (For running notebooks in realtime) <br>
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sarvesh211999/CHAOSS-Gsoc/master)

Microtasks for the Perceval Project in GSOC
Hello! I am interested in the Perceval GSOC Project in CHAOSS. As required, I have completed Microtasks 0 - Microtasks 5

OmegaUp with 4202 commits , 910 pull requests and 1472 issues.
Specifically, for each task

### [Microtask 0](./Microtask-0):

- 2 JSON file were generated by using perceval once using Git and another using Github.
- The file generated by git i.e git-commits.json show all the commit history and all different metrics were shown in Jupyter Notebook
- The file generated by github i.e data_source_issues.json show all the issues and pull request history and all different metrics were shown in Jupyter Notebook
- Analysis Done on Git Commits and Issues of the repository
- For this Microtask use the JSON file inside the Microtask 0 folder.

---------------------------------------------
### [Microtask 1](./Microtask-1):

- Notebook showing (and producing) a list with the activity per quarter: number of new committers, submitters of issues, and submitters of pull/merge requests, number of items (commits, issues, pull/merge requests) as a table and as a CSV file. Used Plain Python 3.
- For this Microtask use the JSON file inside the root folder with name data_source.json.

---------------------------------------------
### [Microtask 2](./Microtask-2):

- Same Analysis as Microtask 1 but use of Pandas is done. 
- For this Microtask use the JSON file inside the root folder with name data_source.json.

---------------------------------------------
### [Microtask 3](./Microtask-3):

- Notebook with charts showing the distribution of time-to-close for issues already closed, and opened during the last year. Used Pandas for this, and Pandas charting library.
- For this Microtask use the JSON file inside the root folder with name data_source.json.

---------------------------------------------
### [Microtask 4](./Microtask-4):

- Notebook, with the number of commits authored, issues opened, and pull/merge requests opened, during the last three months, ordered by the total number (commits plus issues plus pull requests) for listing of repositories. Used plain Python3.
- For this Microtask use the JSON file inside the root folder with name data_source2.json.

---------------------------------------------
### [Microtask 5](./Microtask-5):

- Same as Microtask 4 only difference Pandas is used.
- For this Microtask use the JSON file inside the root folder with name data_source2.json.

---------------------------------------------
### Microtask 6:

Currently Working on it.

---------------------------------------------
### Microtask 7:

Pull Request Merged in chaoss/grimoirelab-tutorial

-https://github.com/chaoss/grimoirelab-tutorial/pull/74

---------------------------------------------
### Microtask 8:

Pull Request Merged in chaoss/wg-gmd

-https://github.com/chaoss/wg-gmd/pull/125

-https://github.com/chaoss/wg-gmd/pull/116

---------------------------------------------
##### Note: Used git-lfs for uploading data source JSON files to GitHub
---------------------------------------------
---------------------------------------------

How to run the notebook

- git clone https://github.com/sarvesh211999/CHAOSS-Gsoc.git
- cd CHAOSS-Gsoc
- Open terminal and run juypter-notebook
- Open jupyter-notebook and change directory to the microtask you want to run 
- In Menu Bar click Cell-> Run All
