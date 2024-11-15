# cintel-04-local
cintel-04-local
How to Run Locally
To run this app on your local machine, follow these steps:

# Prerequisites
Make sure you have Python installed and that you’re familiar with virtual environments. You will also need the required packages listed in the requirements.txt file.

Setup
Clone the Repository
First, clone the repository to your local machine:
git clone https://github.com/dineshgurum8/cintel-04-local.git
# 2. Create a Virtual Environment
It's recommended to use a virtual environment to manage your project's dependencies. To create one, run the following command:

# python -m venv .venv
# 3. Activate the Virtual Environment
Once the virtual environment is created, you need to activate it:

.\.venv\Scripts\activate
# 4. Install Dependencies
After activating the virtual environment, install the necessary Python packages by running:

pip install -r requirements.txt
# 5. Run the App
Now that everything is set up, you can run the app by using the following command:

shiny run --reload --launch-browser penguins/app.py
