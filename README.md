[![](./data/splash.png)](https://youtu.be/xgLnS2IFCQQ)

# GUTS Sandbox

## Installation

```bash
git clone git@github.com:rislab/guts-sandbox.git --recursive
cd guts-sandbox/
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install colcon-common-extensions numpy matplotlib
./build.sh
```

## Running the program
```bash
source workon
cd wet/src/guts_utils_py/test
python test_multirobot_and_tracks.py
```

## Supported Operating Systems
This software was tested on Ubuntu 20.04.
