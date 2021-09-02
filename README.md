# gee_examples
Repository that contains example using the Google Earth Engine Python API

## Requirements

1. Python 3.8.10
2. pip 20.0.2

## Install

1. We need to create an dev environment (Use venv):

```shell
sudo apt install -y python3-venv
```

2. Create env folder:
```shell
python3 -m venv .env
```

3. Activate environment:
```shell
source .env/bin/activate
```

Note: To deactivate env run:
```shell
deactivate
```

4. Install dependencies:
```shell
pip install -r requirements.txt
```

5. Authenticate in GEE:
```shell
earthengine authenticate
```
Follow the link and login in your account. Paste the text in the terminal.