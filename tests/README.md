# Running pytest for Velocitas vehicle Model Generator
Execute the following commands in the base directory of the repository:

1. Create a python virtual environment and activate it (if not already done):
   ```bash
   python3 -m venv ./venv
   source ./venv/bin/activate
   ```


2. Install the necessary dependencies in your python virtual environment
   ```bash
   pip3 install -r tests/requirements.txt
   ```

3. Execute the test
   ```bash
     PYTHONPATH=$(pwd)/src python3 -m pytest
   ```
