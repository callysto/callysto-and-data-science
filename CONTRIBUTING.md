# Contributing Guidelines

Contributions are very welcome, and are greatly appreciated! 

You can contribute in many ways:

## Types of Contributions

### Report Bugs, Submit Feedback or Request Features

Report bugs as a [GitHub issue](https://github.com/callysto/callysto-and-computational-thinking/issues).

If you are reporting a bug, please include:

* Your operating system name and version.
* Your browser name and version
* Any details about your local setup that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.
* This is a volunteer project, and bug fixing contributions are welcome!


If you are proposing a feature, please include:

* Explain in detail how it would work.
* Keep the scope as narrow as possible, to make it easier to implement.
* This is a volunteer project, and feature contributions are welcome!

## Contribute

If you are ready to contribute, generally, fork our repository, create a branch off of master for your task. After completing your notebook(s) and content review, make the recommended changes and open a pull request from your branch to master. 

We consider it a best practice to clear all cell outputs from Jupyter Notebooks before commiting. This can be done with 'Kernel > Restart Kernel and Clear Outputs of All Cells' (or 'Edit > Clear Outputs of All Cells') from the top menu bar. 

To set up `callysto-and-computational-thinking` Jupyter Book for local development.

1. Fork the `callysto-and-computational-thinking` repo on GitHub.
2. Clone your fork locally and install requirements:

```sh
git clone git@github.com:your_name_here/callysto-and-computational-thinking.git
pip install -r requirements.txt
```

3. Create a branch for local development:

```sh
git checkout -b name-of-your-bugfix-or-feature
```

4. Make your desired changes, test it, and push your branch to GitHub when you're ready:

```sh
git add .
git commit -m "detailed description of your changes."
git push origin name-of-your-bugfix-or-feature
```

5. Open a pull request through the GitHub website. Naming convention for pull requests -- bug fixes should be named `✨ BUG: issue number that the bug fix is associated with` and new features should be named `✨ NEW: issue number that the new feature is associated with`.

### Contribution Naming Conventions

Jupyter Notebooks should be named Module#_Unit#.ipynb where applicable. 
If your notebook is in a directory, your directory should be named Module# and have the same module number as your notebook.
All image names should be kebab-case and placed in the images folder in the root directory.
If you have files (not images) accompanying your notebook they should be in the same directory along with your notebook.

### Notebook Banners

All notebooks should include a top and bottom banner. The markdown to display the banner in the header should be

`![Callysto.ca Banner](https://github.com/callysto/curriculum-notebooks/blob/master/callysto-notebook-banner-top.jpg?raw=true)`

and in the footer

`[![Callysto.ca License](https://github.com/callysto/curriculum-notebooks/blob/master/callysto-notebook-banner-bottom.jpg?raw=true)](https://github.com/callysto/curriculum-notebooks/blob/master/LICENSE.md)`

## General Considerations

Similar to [Zen of Python](https://en.wikipedia.org/wiki/Zen_of_Python), your descriptions and code should be readable and easy to explain, and simple is better than complex.

Check that the reading level is appropriate for your audience. Assume that your readers have access to other resources on the topic, or explicitly link to other learning resources.
