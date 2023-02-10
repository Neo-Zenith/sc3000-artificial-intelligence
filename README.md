# Lab Assignments

## How to Start
Run the following commands in your terminal window:

1. Create a virtual environment
```bash
python -m virtualenv venv --python=python3.7
```

2. Activate the virtual environment
```bash
venv/scripts/activate
```

3. Install all dependencies
```bash
python -m pip install -r requirements.txt
```

4. Ensure that you have also installed [MPI](https://www.microsoft.com/en-us/download/details.aspx?id=100593). Otherwise, you may get a ```DLL load failed: The specified module could not be found when doing "from mpi4py import MPI"``` error.

Note that *Python 3.7* is used in the virtual environment

## Branch Structure
* [*main*](https://github.com/Neo-Zenith/SC3000-artificial-intelligence/tree/main) branch: <b>Fail-safe</b> branch
* [*playground*](https://github.com/Neo-Zenith/SC3000-artificial-intelligence/tree/playground) branch: <b>Testing</b> ground
