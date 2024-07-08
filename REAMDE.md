# This is an open source version of smartdata baseline

## how to run
1. first create a python virtual environment, assuming you are using conda
```bash
conda create --name smartdata
# check the result with 
conda env list
# you should see a virtual env with a name smartdata
conda activate smartdata
```
2. then install all package needed
```bash
pip install -r requirements.txt
```
3.  run the app use streamlit 
```bash
streamlit run app.py
```
4. if you have done 1-2 once, always go to 3 to start