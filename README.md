### Linux Teaching Modules Homepage Repository

##### The following files are meant to be the homepage for people to navigate to and register for a particular workshop

Below this line is a rehashing of the README from the main teaching modules location

##### The following teaching modules were developed for use at Van Andel Research Institute (VARI) and include content that is both original work and reused/modified from publically available sources. 


The modules are modeled after Software/Data Carpentry-esque workshops but in an abbreviated format targeting researchers at VARI. This is *meant* to be an evolving set of documents that are updated constantly and consistently. This includes both the content and the teaching/learning objectives.

##### IMPORTANT: 

Any modifications to the documentation **MUST** be kept under version control in the event of any errors or breaking the rendering of the documention on readthedocs.io. Additionally, it serves as a nice paper trail for where we have been and what does/doesn't work in the classroom.

##### Modifying the documentation

The best way to work on the documentation is to fork (copy) the repository to your own space and commit changes to the forked repo. From there you can create a pull request to incorporate your changes into the master brach (what is rendered on readthedocs.io). **Please avoid editing and changing files directly on the master branch without a pull request unless absolutely necessary.**

##### Syntax for documentation

The documentation file trees and structuring is built using Sphinx (v1.5.1) and re-structured text. Each time modifications are made, the html can be rendered to locally view changes to the documentation. This requires downloading and installing Sphinx, which requires Python (v2+).

If you have Anaconda:

````

# If you are using a specific virtual environment
source activate your_env

# Download and install Sphinx and associated dependencies
# This is for version 1.5.1
# Change the version to the most recent version if necessary
conda install -c anaconda sphinx=1.5.1

````

If you have base Python with pip installed:

````

# Install the latest version of Python
# Do not use just the base version provided with Mac or Linux
# pip pulls from the latest version in the Python Package Index
pip install Sphinx

````

##### Homepage

This will need to be updated (links, docs, etc. for each workshop given)

##### Licensing

The documents generated within this repository is largely composed of original work but does contain open source material. Therefore, the documentation is meant to be open to the public and outside input is always welcome. No license restricting access to the content should be placed here. Open FTW!

