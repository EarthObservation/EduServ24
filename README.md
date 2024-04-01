# Remote Sensing and Change Detection with Sentinel Time Series Data

Materials for the [*Remote Sensing and Change Detection with Sentinel Time Series Data*](https://geoclassroom.fgg.uni-lj.si/course/view.php?id=16).

Prepared by:  
Krištof Oštir, Bujar Fetai, Matej Račič, Ana Potočnik Buhvald (University of Ljubljana)

## Preparation

The repository consists of installation instructions, notebooks and practical information.


The repository can be synchronized using `git pull` or downloaded as a zip file. The data used for the practical exercise can be downloaded from [geoclassroom](https://geoclassroom.fgg.uni-lj.si/course/view.php?id=16). 

The practical has installation instructions which should be completed in advance.

## Installation instructions
We will be using [Anaconda](https://www.anaconda.com/), which can be installed from the [website](https://www.anaconda.com/products/distribution#Downloads). If you have limited resources we suggest the us of [Miniconda](https://docs.conda.io/en/latest/miniconda.html).
Once installed open Anaconda Prompt and move to the location of the extracted repository `cd Downloads/EduServ24/`. If you have downloaded it to a different drive change the location to the drive first, example `D:` and press Enter.

Here you can create a new environment for this tutorial using the provided environment.yml file:

```
conda update -n base -c defaults conda
conda env create --file environment.yml
conda activate eo
```

Alternatively, you can use pip to install the libraries using 'pip' and follow the tutorial. This will take some time. Once installed run `jupyter lab` and a browser tab will open.

## Practicals
We will be using the notebooks available in the corresponding folders. To run the notebook after the practical you will need a [Sentinel Hub](https://www.sentinel-hub.com/develop/api/ogc/standard-parameters/) account,
a free trial is available. Once registered you can follow the [instructions](https://sentinelhub-py.readthedocs.io/en/latest/configure.html) to configure access to the services or use `sentinelhub.id` with `credentials_SH.ipynb`.

## Additional resources
This tutorial is based on the [materials](https://github.com/sentinel-hub/eo-learn-workshop/) provided by Sinergise. Where you can find even more examples and resources for the [eo-learn](https://github.com/sentinel-hub/eo-learn) library.

## Acknowledgment

Preparation of the materials was part financed by the Slovenian Research Agency core funding No. P2-0406.

## License
This project is licensed under the terms of the [Apache License](LICENSE).

© Copyright 2024 University of Ljubljana, Faculty of Civil and Geodetic Engineering
