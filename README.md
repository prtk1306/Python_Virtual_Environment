## Multiple Python environment on a single local machine

### Pre-requisites:
* python version >= 3.3
* All the commands will be run on Command prompt
* Run command prompt as administrator


Run the below command to create virtual environment onto your machine
* python -m venv [VirtualEnvName]

Activate virtual environment
* [VirtualEnvDirectoryPath]\Scripts\activate

After activating the virtual environment, you will see ([VirtualEnvName]) at the starting of the command prompt line.

You can install specific python libraries for your virtual environment. It will not create issues with your system python libraries.

Deactivate virtual environment
* deactivate

Note: Don't use '[' ']' in the above commands.
