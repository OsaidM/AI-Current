## Getting Started

1. **Check that you have an appropriate version of Python 3** You want to make sure that you have a [compatible version](https://docs.wagtail.org/en/stable/releases/upgrading.html#compatible-django-python-versions) installed:

   ```sh
   python --version
   # Or:
   python3 --version
   # **On Windows** (cmd.exe, with the Python Launcher for Windows):
   py --version
   ```

2. **Create a Virtual Environment**: Set up a virtual environment to isolate your project dependencies. These instructions are for GNU/Linux or MacOS, but there are [other operating systems in the Wagtail docs](https://docs.wagtail.org/en/stable/getting_started/tutorial.html#create-and-activate-a-virtual-environment).

   ```bash
   python -m venv myproject/env
   source myproject/env/bin/activate 
   # or this on windows
   .\env\scripts\activate 
   ```

3. **Navigate to Project Directory**: Move into the newly created project directory.

   ```bash
   cd myproject
   ```

4. **Install Project Dependencies**: Install the project's dependencies into a virtual environment.

   ```bash
   pip install -r requirements.txt
   ```

5. **Run Server**: Run The Server while the environment is activated

   ```bash
   python manage.py runserver
   ```

6. **Access the Site and Admin**: Once the server is running, you can view the site at `localhost:8000` and access the Wagtail admin interface at `localhost:8000/admin`. Log in with the default credentials provided by :

    - Username: admin
    - Password: password
