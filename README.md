# laptop-price-predictor-regression-project
A ML based laptop price predictor

## How to run the app
1. In your Python environment, install **streamlit** library
- Open Anaconda Prompt, go to your environment that has necessary libraries like numpy, pandas, matplotlib, seaborn, sklearn
- Type `pip install streamlit` to install it to your environment
- To check installation, type `streamlit hello`, a new browser tab with streamlit introduction is openned, you can close it
2. Open project folder in IDE like VS Code, open a terminal and type
`streamlit run app.py`

## IMPORTANT
You need to train the model first, by running all cells in Jupyter notebook. By doing this, it will export 2 .pkl (pickle) files (the trained model), which will be used by app.py later
