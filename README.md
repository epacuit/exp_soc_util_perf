# The Social Utility of Voting Revisited

This repository contains the code and data for the paper "The Social Utility of Voting Revisited" by [Wes Holliday](https://sites.google.com/site/wesholliday/) and [Eric Pacuit](https://pacuit.org/). 

This repository contains the following files: 

1. expected_social_utility_performance.ipynb: This notebook contains the code for the main simulation presented in the paper. 

2. tournaments_from_real_elections.ipynb: This notebook contains the code to create the statistics about the frequencies of different types of majority graphs for four candidates generated from real election data. 
    * real_elections/: This folder contains the data for the real elections discussed in the paper.

4. tournaments_from_spatial_profiles.ipynb: This notebook contains the code to create the statistics about the frequencies of different types of majority graphs for four candidates generated from sampling spatial profiles.

3. graphs.ipynb: This notebook contains the code to create the graphs displayed in the paper.

4. data/: This folder contains the generated data for the paper.
**Note**: The data files for the main simualation are too large to be stored on GitHub.  They will be downloaded from the Google cloud storage when the notebook is run.  

5. webapp/: This folder contains the code for the web application that allows users to interact with the simulation.  To run this web application locally, you need to have ``streamlit`` installed.  You can install it by running ``pip install streamlit``.  Then, you can run the application from the directory ``webapp`` by running ``streamlit run Expected_Utility_Performance.py``.  The application will then be available at ``http://localhost:8501``.  An online version of the application is available at [https://exp-soc-util-perf.pacuit.org/](https://exp-soc-util-perf.pacuit.org/).