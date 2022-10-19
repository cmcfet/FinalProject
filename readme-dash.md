# Steps to follow

1. Open Google Cloud Shell

	In your home directory create a virtual environment using the command below

	python3 -m venv myenv

2. Activate the environment:

	source myenv/bin/activate

3. In the home directory make a folder called 'myapp' and drop the files contained in this zip file in that folder

4. Cd to home directory and run the below command

	pip install -r ./myapp/requirements.txt

5. After all the packages are downloaded, start the app using the command below:

	python3 main.py


6. To deploy to GCP, select the project to which you want to deploy through the dropdown box in the terminal and then run the below command:

	gcloud app deploy

# Selenimum references
* https://selenium-python.readthedocs.io/installation.html
* https://selenium-python.readthedocs.io/waits.html - refer how to wait for the element to load
