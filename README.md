# The Social Utility of Voting Revisited

This repository contains the code and data for the paper "The Social Utility of Voting Revisited" by [Wes Holliday]() and [Eric Pacuit](https://pacuit.org/). 


1. expected_social_utility_performance.ipynb: This notebook contains the code for the main simulation presented in the paper. 

2. majority_graph_statistics.ipynb: This notebook contains the code to create the statistics about the frequencies of different types of majority graphs for four candidates. 
    * real_electons/: This folder contains the data for the real elections discussed in the paper.

3. graphs.ipynb: This notebook contains the code to create the graphs in displayed in the paper.

4. data/: This folder contains the generated data for the paper.

5. webapp/: This folder contains the code for the web application that allows users to interact with the simulation.  To run this web application locally, you need to have ``streamlit`` installed.  You can install it by running ``pip install streamlit``.  Then, you can run the application by running ``streamlit run webapp/Expected_Utility_Performance.py``.