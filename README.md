# adarshatluriwebsite
The purpose of this documentation is to help somebody who wants to build a website/webapp using Django and has the html templates they want to use or start with. This consists of the code for my personal website [Adarsh Atluri](adarshatluri.in). The website is more comples in terms of its features where it will link to my portfolio projects and if needed be able to execute them etc... This is why i am building it rather using wordpress etc...





# Table of Contents
 * [System Setup](#systemsetup)
 * [Reference Docs ](#refdocs)

## System Setup <a id="systemsetup"></a>
1. Install python if it is not already installed. [Python Beginners Guide](https://wiki.python.org/moin/BeginnersGuide/Download)
2. Install Git. Most machines come with git inbuilt but if its not, you will need to install it. [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
3. Clone this repository on your computer at your desired location
4. Python Virtual Environment
    * Open Terminal(on mac) and navigate to the directory where you cloned the project.
    * *Replace "placeholder" in the below commands with the name of your choice*
    * Create a python virtual environment by running the command `python3 -m venv placeholder`
    * Run the following command: `source placeholder/bin/activate`
    * This will prepend that directory to your PATH, so that running python will invoke the environment’s Python interpreter and you can run installed scripts without having to use their full path
5. Since you have cloned the project, you will already have the following Django folders:
    * app
    * app/mysite
    * app/manage.py
    * *You can refer to [Django Docs](#djangodoc) to see how to create django projects and apps etc...*






## Reference Documentation <a id="refdocs"></a>
1. [GitHub Readme Formatting](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
2. [Django Docs](https://docs.djangoproject.com/en/5.1/intro/tutorial01/) <a id="djangodoc"></a>
3. [Python Virtual Environment](https://docs.python.org/3/library/venv.html)
3. [Sample Readme](https://gist.github.com/atcuno/3425484ac5cce5298932)
