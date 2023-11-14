# Documentation-on-GitHub

## Steps

1. Create a default github repository and clone it on local machine.
2. Create a python virutal environment and activate it.
    
    python -m venv venv
    venv\Scripts\activate

3. Install mkdocs library using pip

    pip install mkdocs-material

4. Create a new mkdocs file. This will create a folder known as docs and mkdocs.yml file on the base folder. All the configuration setting is done on yml file and all the documentation is done in docs folder. Each markdown file in docs folder is treated as a new page.

    mkdocs new .

5. Create a local mkdocs server to check the content. This will create a locally hosted static website. Address will be shown in terminal.

    mkdocs serve
