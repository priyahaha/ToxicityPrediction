Operating System : Windows

Python : Version 3 and above

Libraries Required :

pandas
rdkit
scikit-learn
xgboost
imblearn
deepchem
tensorflow

Running the Code with DOCKER:

Simply run the 'run.sh' file that executes Docker Commands
    - Dockerfile automatically installs the required libraries

Docker Commands:

docker build -t toxicity -f Dockerfile .

docker images

docker run toxicity

Run in Local:

Install the above libraries using
    pip install {library}
Run the python command
    python toxicityPrediction.py
