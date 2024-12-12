Install instructions:
Open terminal and run the following commands:
git clone https://github.com/meqaniqal/grocerykiosk.git

#2. navigate to the repo:
cd grocerykiosk

#3. create a virtual conda environment called grocerykiosk
conda create -n grocerykiosk python=3.9

#4. activate the environment
conda activate grocerykiosk

#5. todo: install the requirements
pip install -r requirements.txt

#5. adding dependencies:
conda install flask flask-socketio pymongo
#6. create requirements.txt
pip freeze > requirements.txt
