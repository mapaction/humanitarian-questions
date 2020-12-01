The Humanitarian Questions project
---

## Project objectives

This project is a structured exploration into the needs of humanitarian actors. This exploration is divided into domain areas split across **preparedness** and **response** efforts. For this exploration to accurately reflect the needs of such a diverse sector, our hope is to engage with a wide range of individuals, organizations, and communities who can provide feedback and contribute content.

The longer term goal is for this work to inform technical support organizations, such as MapAction. We hope that the insights from this work can help MapAction and others in their efforts to leverage data and technology to create products and services that support the humanitarian sector.

## Contributing with GitHub

The content for this project is published as a Jupyter Book. We have chosen to host the content for this book on GitHub to effectively manage version control and allow for smooth collaboration across a wide range of contributors. Of course, we acknowledge that contributing through GitHub isn't for everyone. We are currently preparing material that will describe alternative contribution pathways.  

These instructions below assume prior experience with Git/GitHub (as well as having a GitHub account). These steps describe the process for building a local copy of this book, upon which you can make and propose changes. This Jupyter book is deployed through GitHub pages (on the ```gh-pages``` branch), and will automatically be rebuilt and redeployed when the ```main``` branch is updated. 

1. Fork this repository on GitHub and clone this fork locally. 

2. From the main project directory, create a pip or conda virtual environment and download the package dependencies. Note that there is a known incompatibility with Python 3.8 on Windows. See [this guidance](https://jupyterbook.org/advanced/advanced.html#working-on-windows) if you are working on Windows.

```
pip install requirements.txt
```

3. Make local changes to the project files (located within the ```humbook``` folder). This will largely entail editing in [Markdown](https://daringfireball.net/projects/markdown/). 

4. View your edits by building a local copy of the book

```
jupyter-book build humbook/
```