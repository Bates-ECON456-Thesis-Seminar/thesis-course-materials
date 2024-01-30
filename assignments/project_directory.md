# ECON 456: Senior Thesis Seminar

## Create a GitHub Repository and Project Directory

### GitHub Repository

1. Create a new repository on GitHub.  I recommend using the same name as your project directory: `senior_thesis_project_name`.

2. Add a README file to your repository.  This is where you will write basic information about your project.

3. Add a .gitignore file to your repository.  This is where you will list all of the files you do not want to push to GitHub.  For example, you do not want to push your raw data files to GitHub because they are often very large.  You can write the name of your data file into your .gitignore file or use a wildcard to ignore all files of a certain type.  For example, `*.csv` means ignore all files that end in `.csv`.

4. Add a LICENSE file to your repository.  This is where you will write the license you want to use for your project.  I recommend using the MIT License.

5. Use GitHub Desktop (or your preferred Git client) to clone your repository to your local machine.  This will create a local copy of your repository on your computer.

### Project Directory

The project directory helps you stay organized. I've provided a basic [template](https://github.com/Bates-ECON456-Thesis-Seminar/thesis-sample).

1. Navigate to the project directory you just cloned off GitHub. This is where you will store all of your project files.

2. Within the project directory, create a subdirectory called `data`.  This is where you will store all of your data files.  You can create additional subdirectories within `data` if you wish.  For example, you might create a subdirectory called `raw` to store the raw data files you download from the web, and a subdirectory called `clean` to store the cleaned data files you create.

3. Within the project directory, create a subdirectory called `code`.  This is where you will store all of your code files.  You can create additional subdirectories within `code` if you wish.  For example, you might create a subdirectory called `build` to store your Python scripts, and a subdirectory called `analysis` to store your Jupyter notebooks.

4. Within the project directory, create a subdirectory called `output`.  This is where you will store all of your output files.  You can create additional subdirectories within `output` if you wish.  For example, you might create a subdirectory called `figures` to store your figures, and a subdirectory called `tables` to store your tables.

5. Within the project directory, create a subdirectory called `references`.  This is where you will store all of your reference files.  You can create additional subdirectories within `references` if you wish.  For example, you might create a subdirectory called `bibliography` to store your bibliography files.

6. Within the project directory, create a subdirectory called `presentation`.  This is where you will store all of your presentation files.  You can create additional subdirectories within `presentation` if you wish.  For example, you might create a subdirectory called `slides` to store your presentation slides.

7. Within the project directory, create a subdirectory called `writing`.  This is where you will store all of your submission files.  You can create additional subdirectories within `writing` if you wish.  For example, you might create a subdirectory called `paper` to store your paper files.

### Commit/Push/Pull

Create a test file in your project directory.  Commit the file to your local repository.  Push the file to your remote repository on GitHub.  Pull the file from your remote repository to your local repository.  Delete the file from your local repository.  Commit the deletion to your local repository.  Push the deletion to your remote repository on GitHub.  Pull the deletion from your remote repository to your local repository.  If you can do all of this, you are ready to start working on your project.

If you need help, see [GitHub's documentation](https://docs.github.com/en/desktop/adding-and-cloning-repositories/cloning-a-repository-from-github-to-github-desktop).