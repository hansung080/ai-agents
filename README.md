# AI Agents
Various AI agents

## Prerequisites
- Python 3.12

## Runtime Environment
### Create Virtual Environment and Install Dependent Packages
```sh
$ python3 -m venv .venv
$ source .venv/bin/activate
(.venv) $ pip3 install -r requirements.txt
(.venv) $ deactivate
```

## Usage
### Run a General Application
```sh
$ ./<python-file> [arguments]
```

### Run a Streamlit Application
```sh
(.venv) $ streamlit run <python-file> [arguments]
```

## Agents
- gpt: gpt_basic, one_shot, few_shot, single_turn, multi_turn, streamlit_basic 
