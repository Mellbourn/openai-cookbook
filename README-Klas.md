# How to configure a Visual Studio Code Jupiter Notebook environment

```sh
python -m venv venv
source venv/bin/activate
pip install jupyter
pip install numpy
pip install openai
pip install pandas
pip install tiktoken
pip install wikipedia
pip install matplotlib
pip install plotly
pip install scipy
pip install scikit-learn # note: not sklearn!
```

Always `source venv/bin/activate` before statting vscode

Set an API key and start code

```sh
source venv/bin/activate
export OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
code .
```
