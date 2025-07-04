# SmS_Spam_Classifier

The step-by-step instructions for setting up and running the application using a virtual environment for Python 3.9:

1. **Setup Virtual Environment**:
   - Open the terminal.
   - Install the virtual environment package if you haven't already: `conda create -p venv python=3.9 -y`.
   - Create a virtual environment: `virtualenv venv`.
   - Activate the virtual environment:
    conda activate venv/


2. **Install Requirements**:
   - Install the requirements: `pip install -r requirements.txt`.

3. **Set Up the Jupyter Notebook**:
   - Open the Jupyter Notebook in your virtual environment.
   - pip install ipykernel
   - pip install jupyter notebook

4. **Run Application.py**:
   -python appl.py

5. **Let's Deploy it at Render.com**:
   -go to this website: https://dashboard.render.com/web
   -then click on new and choose web serivces
   -choose this :Build and deploy from a Git repository and click on next
   -then in settings :![image](https://github.com/vishwaspw/Spam_Classifier/blob/main/assets/IMAGE3.png)


6. **So click on manual Deploy and select deploy with latest commit**
   -and wait 2-3 mint after that your website will be published.
   -https://spam-classifier-d15y.onrender.com/

   ![image](https://github.com/vishwaspw/Spam_Classifier/blob/main/assets/IMAGE1.png)

   The output:
   ![image](https://github.com/vishwaspw/Spam_Classifier/blob/main/assets/IMAGE2.png)


By following these steps, you can set up a virtual environment, install necessary requirements, and run the `app.py` script in the Jupyter Notebook environment. This process helps ensure a clean and isolated development environment for your application.
