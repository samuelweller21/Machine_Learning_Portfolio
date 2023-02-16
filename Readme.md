# Readme

## Install Venv
```
# If not yet installed
pip install --user virtualenv
pip install --user ipykernel

# Otherwise
myenv\Scripts\activate
python -m ipykernel install --user --name=myenv

# Use
pip freeze | Out-File -Encoding UTF8 requirements.txt
install -r requirements.txt
```