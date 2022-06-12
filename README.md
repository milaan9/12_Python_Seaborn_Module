<p align="center"> 
<a href="https://github.com/milaan9"><img src="https://img.shields.io/static/v1?logo=github&label=maintainer&message=milaan9&color=ff3300" alt="Last Commit"/></a> 
<img src="https://badges.pufler.dev/created/milaan9/12_Python_Seaborn_Module" alt="Created"/>
<a href="https://github.com/milaan9/12_Python_Seaborn_Module/graphs/commit-activity"><img src="https://img.shields.io/github/last-commit/milaan9/12_Python_Seaborn_Module.svg?colorB=ff8000&style=flat" alt="Last Commit"/> </a> 
<a href="https://github.com/milaan9/12_Python_Seaborn_Module/pulse" alt="Activity"><img src="https://img.shields.io/github/commit-activity/m/milaan9/12_Python_Seaborn_Module.svg?colorB=teal&style=flat" /></a> 
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmilaan9%2F12_Python_Seaborn_Module&count_bg=%231DC92C&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=views&edge_flat=false"/></a>
<a href="https://github.com/milaan9/12_Python_Seaborn_Module/stargazers"><img src="https://img.shields.io/github/stars/milaan9/12_Python_Seaborn_Module.svg?colorB=1a53ff" alt="Stars Badge"/></a>
<a href="https://github.com/milaan9/12_Python_Seaborn_Module/network/members"><img src="https://img.shields.io/github/forks/milaan9/12_Python_Seaborn_Module" alt="Forks Badge"/> </a>
<img src="https://img.shields.io/github/repo-size/milaan9/12_Python_Seaborn_Module.svg?colorB=CC66FF&style=flat" alt="Size"/>
<a href="https://github.com/milaan9/12_Python_Seaborn_Module/pulls"><img src="https://img.shields.io/github/issues-pr/milaan9/12_Python_Seaborn_Module.svg?colorB=yellow&style=flat" alt="Pull Requests Badge"/></a>
<a href="https://github.com/milaan9/12_Python_Seaborn_Module/issues"><img src="https://img.shields.io/github/issues/milaan9/12_Python_Seaborn_Module.svg?colorB=yellow&style=flat" alt="Issues Badge"/></a>
<img src="https://img.shields.io/github/languages/top/milaan9/12_Python_Seaborn_Module.svg?colorB=996600&style=flat" alt="Language"/></a>
<a href="https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blueviolet.svg" alt="MIT License"/></a>
</p> 
<!--<img src="https://badges.pufler.dev/contributors/milaan9/01_Python_Introduction?size=50&padding=5&bots=true" alt="milaan9"/>-->

<p align="center"> 
<a href="https://mybinder.org/v2/gh/milaan9/12_Python_Seaborn_Module/HEAD"><img src="https://mybinder.org/badge_logo.svg" alt="binder"/></a>
<a href="https://githubtocolab.com/milaan9/12_Python_Seaborn_Module"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="colab"/></a>
</p>   
 
# 12_Python_Seaborn_Module


## Introduction 👋

From the website, “Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informational statistical graphs.”

Seaborn excels at doing Exploratory Data Analysis (EDA) which is an important early step in any data analysis project. Seaborn uses a “dataset-oriented” API that offers a consistent way to create multiple visualizations that show the relationships between many variables. In practice, Seaborn works best when using Pandas dataframes and when the data is in tidy format. 

## What’s New?
In my opinion the most interesting new plot is the [relationship](https://seaborn.pydata.org/generated/seaborn.relplot.html#seaborn.relplot) plot or `relplot()` function which allows you to plot with the new `scatterplot()` and `lineplot()` on data-aware grids. Prior to this release, scatter plots were shoe-horned into seaborn by using the base matplotlib function `plt.scatter` and were not particularly powerful. The `lineplot()` is replacing the `tsplot()` function which was not as useful as it could be. These two changes open up a lot of new possibilities for the types of EDA that are very common in Data Science/Analysis projects.

The other useful update is a brand new [introduction](https://seaborn.pydata.org/introduction.html) document which very clearly lays out what Seaborn is and how to use it. In the past, one of the biggest challenges with Seaborn was figuring out how to have the “Seaborn mindset.” This introduction goes a long way towards smoothing the transition.
 
 ---
 
 ## Table of contents 📋

| **No.** | **Name** | 
| ------- | -------- | 
| 01 | **[Seaborn_Loading_Dataset](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/001_Seaborn_Loading_Dataset.ipynb)** |
| 02 | **[Seaborn_Controlling_Aesthetics](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/002_Seaborn_Controlling_Aesthetics.ipynb)** |
| 03 | **[Seaborn_Matplotlib_vs_Seaborn](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/003_Seaborn_Matplotlib_vs_Seaborn.ipynb)** |
| 04 | **[Seaborn_Color_Palettes](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/004_Seaborn_Color_Palettes.ipynb)** |
| 05 | **[Seaborn_LM Plot_&_Reg_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/005_Seaborn_LM%20Plot_%26_Reg_Plot.ipynb)** |
| 06 | **[Seaborn_Scatter_Plot_&_Joint_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/006_Seaborn_Scatter_Plot_%26_Joint_Plot.ipynb)** |
| 07 | **[Seaborn_Additional_Regression_Plots](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/007_Seaborn_Additional_Regression_Plots.ipynb)** |
| 08 | **[Seaborn_Categorical_Data_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/008_Seaborn_Categorical_Data_Plot.ipynb)** |
| 09 | **[Seaborn_Dist_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/009_Seaborn_Dist_Plot.ipynb)** |
| 10 | **[Seaborn_Strip_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/010_Seaborn_Strip_Plot.ipynb)** |
| 11 | **[Seaborn_Box_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/011_Seaborn_Box_Plot.ipynb)** |
| 12 | **[Seaborn_Violin_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/012_Seaborn_Violin_Plot.ipynb)** |
| 13 | **[Seaborn_Bar_Plot_and_Count_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/013_Seaborn_Bar_Plot_and_Count_Plot.ipynb)** |
| 14 | **[Seaborn_TimeSeries_and_LetterValue_Plot](XXX)** |
| 15 | **[Seaborn_Factor_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/015_Seaborn_Factor_Plot.ipynb)** |
| 16 | **[Seaborn_PairGrid_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/016_Seaborn_PairGrid_Plot.ipynb)** |
| 17 | **[Seaborn_FacetGrid_Plot](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/017_Seaborn_FacetGrid_Plot.ipynb)** |
| 18 | **[Seaborn_Heat_Map](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/018_Seaborn_Heat_Map.ipynb)** |
| 19 | **[Seaborn_Cluster_Map](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/019_Seaborn_Cluster_Map.ipynb)** |
|    | **[datasets](https://github.com/milaan9/12_Python_Seaborn_Module/tree/main/datasets)** |
| 11 | **[Python Seaborn Statistical Data Visualization.pdf](https://github.com/milaan9/12_Python_Seaborn_Module/blob/main/Python%20Seaborn%20Statistical%20Data%20Visualization.pdf)** |

These are online **read-only** versions. However you can **`Run ▶`**  all the codes **online** by clicking here ➞ <a href="https://mybinder.org/v2/gh/milaan9/12_Python_Seaborn_Module/HEAD"><img src="https://mybinder.org/badge_logo.svg" alt="binder"/></a>

 
 ---

## Install Seaborn Module:

Open your [![Anaconda](https://img.shields.io/badge/Anaconda-342B029.svg?&style=flate&logo=anaconda&logoColor=white)](https://www.anaconda.com/products/individual) Prompt <img alt="propmt" src="https://img.shields.io/badge/-__-000000?style=flat-square&logo=Plex&logoColor=white"> and type and run the following command (individually):

 -       pip install seaborn  
 

Once Installed now we can import it inside our python code.

---   

## Frequently asked questions ❔

### How can I thank you for writing and sharing this tutorial? 🌷

You can <img src="https://img.shields.io/static/v1?label=%E2%AD%90 Star &message=if%20useful&style=style=flat&color=blue" alt="Star Badge"/> and <img src="https://img.shields.io/static/v1?label=%E2%B5%96 Fork &message=if%20useful&style=style=flat&color=blue" alt="Fork Badge"/> Starring and Forking is free for you, but it tells me and other people that it was helpful and you like this tutorial.

Go [**`here`**](https://github.com/milaan9/12_Python_Seaborn_Module) if you aren't here already and click ➞ **`✰ Star`** and **`ⵖ Fork`** button in the top right corner. You will be asked to create a GitHub account if you don't already have one.

---

### How can I read this tutorial without an Internet connection? <img alt="GIF" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/hmm.gif" width="20" />

1. Go [**`here`**](https://github.com/milaan9/12_Python_Seaborn_Module) and click the big green ➞ **`Code`** button in the top right of the page, then click ➞ [**`Download ZIP`**](https://github.com/milaan9/12_Python_Seaborn_Module/archive/refs/heads/main.zip).

    ![Download ZIP](img/dnld_rep.png) 

2. Extract the ZIP and open it. Unfortunately I don't have any more specific instructions because how exactly this is done depends on which operating system you run.
    
3. Launch ipython notebook from the folder which contains the notebooks. Open each one of them
  
    **`Kernel > Restart & Clear Output`**
    
This will clear all the outputs and now you can understand each statement and learn interactively.

If you have git and you know how to use it, you can also clone the repository instead of downloading a zip and extracting it. An advantage with doing it this way is that you don't need to download the whole tutorial again to get the latest version of it, all you need to do is to pull with git and run ipython notebook again.

---

## Authors ✍️

I'm Dr. Milaan Parmar and I have written this tutorial. If you think you can add/correct/edit and enhance this tutorial you are most welcome🙏

See [github's contributors page](https://github.com/milaan9/12_Python_Seaborn_Module/graphs/contributors) for details.

If you have trouble with this tutorial please tell me about it by [Create an issue on GitHub](https://github.com/milaan9/12_Python_Seaborn_Module/issues/new). and I'll make this tutorial better. This is probably the best choice if you had trouble following the tutorial, and something in it should be explained better. You will be asked to create a GitHub account if you don't already have one.

If you like this tutorial, please [give it a ⭐ star](https://github.com/milaan9/12_Python_Seaborn_Module).

---

## Licence 📜

You may use this tutorial freely at your own risk. See [LICENSE](./LICENSE).
