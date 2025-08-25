(base) C:\Users\marku>cd handson-mlp

(base) C:\Users\marku\handson-mlp>conda update -n base -c defaults conda
3 channel Terms of Service accepted
Retrieving notices: done
Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done


==> WARNING: A newer version of conda exists. <==
    current version: 25.5.1
    latest version: 25.7.0

Please update conda by running

    $ conda update -n base -c defaults conda



# All requested packages already installed.
(base) C:\Users\marku\handson-mlp>conda env create -f environment.yml
3 channel Terms of Service accepted
Channels:
 - conda-forge
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: failed

PackagesNotFoundError: The following packages are not available from current channels:

  - torchaudio

Current channels:

  - https://conda.anaconda.org/conda-forge

To search for alternate channels that may provide the conda package you're
looking for, navigate to

    https://anaconda.org

and use the search bar at the top of the page.
