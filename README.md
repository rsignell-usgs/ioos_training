# IOOS Training

"A Free System for Visualization and Analysis of Distributed Model Output in Your Browser"

[PDF of Slides](https://speakerdeck.com/rsignell/a-free-system-for-visualization-and-analysis-of-distributed-model-output-in-your-browser)

If you have any problems, see the [issues page](https://github.com/rsignell-usgs/ioos_training/issues) and click the green "New Issue" button.

### 1: Set up the IOOS environment
Install Anaconda python using Miniconda and set up the IOOS environment following these [instructions](
https://github.com/ioos/conda-recipes/wiki/Setting-up-the-IOOS-Python-environment)

### 2: Download this repo:
Two options:
* Use git: `git clone https://github.com/rsignell-usgs/ioos_training.git`
* [Download zipfile](https://github.com/rsignell-usgs/ioos_training/archive/master.zip)

### 3: Try running the notebooks!
 I've created a short youtube video (3 minutes long) that shows how to run the notebook:
https://www.youtube.com/watch?v=QvpUHQqCvV0

If you type launcher and the command is not recognized, type conda install launcher to install the launcher and try again.


### 4: Check out TerriaJS
* TerriaJS running on the IOOS Coastal Ocean Modeling Testbed: http://comt.sura.org/proxy_3001/
* My TerriaJS config file on github: https://raw.githubusercontent.com/rsignell-usgs/ehzrap/master/testing/nfwf.json
* My TerriaJS config on the IOOS testbed instance: http://comt.sura.org/proxy_3001/#https://raw.githubusercontent.com/rsignell-usgs/ehzrap/master/testing/nfwf.json
* Try searching data.gov, selecting `Formats` as `Esri REST`, `WMS` or `WFS` and add the endpoint using the `Add data` button.
* Cool introductory [webinar on TerriaJS](https://www.youtube.com/playlist?list=PLwZr38uPmCbTn8BxpRXaipBmycYL21hCI)
* Cool introductory [webinar on Cesium](https://www.youtube.com/watch?v=cEXneKlofbc) (which TerriaJS uses)

