# CyberGIS-HIV-Documentation

This repository holds all Read the Docs & Sphinx codes and images for the CyberGIS-Vis technical documentation.
- [CyberGIS-HIV GitHub Repository](https://github.com/cybergis/CyberGIS-HIV )
- [CyberGIS-HIV Documentation Website](https://cybergis.github.io/CyberGIS_HIV_document/)

# For editing: 
The documentation in this repo is created using [sphinx-doc](https://www.sphinx-doc.org/en/master/). The information below are the guide to edit the content of the documentation. 


The source code for this documentation are in [docs/source/](https://github.com/cybergis/CyberGIS_HIV_document/tree/main/docs/source) folder. The folder content are as follows:

### Folders:
**images**: image resources 
**videos** : all videos used on the document website


### Page templates 
**index.rst**: template for the [Get Started](https://cybergis.github.io/CyberGIS_HIV_document/build/html/index.html) of the documentation  
**parameters.rst**: template of the [Customizing Parameters](https://cybergis.github.io/CyberGIS-Vis-Documentation/build/CyberGISX.html) page  
**showcase.rst**: template of the [Showcase Gallery](https://cybergis.github.io/CyberGIS-Vis-Documentation/build/QuantDataVis.html) page  

### Configurations 

**conf.py**: sphinx configurations file.   
**requirements.txt**: the required libraries for sphinx to build the documents. This can be used to create the environment for sphinx-doc using "pip install -r requirements.txt"  

# To update documentation content 

## Preapre the enviroenment
1. Clone the repo. 
2. With command line, go to "docs/source/"
3. run the command below 

    `pip install -r requirements.txt`

4. Go back to "docs/" folder
5. test your sphinx with the command below. 

    `sphinx-build -ab html ./source ./build`

You should see the results like: 

> The HTML pages are in build.

## Edit the page content 

1. Switch the branch to "gh-pages" 
2. Open the template of the page that you want the edit. 
3. Edit the content as you want, then, save the file. 
4. You can see the changes by building the documentation locally with the command below:

    `cd docs/`   
    `sphinx-build -ab html ./source ./build`

5. The built HTML files will be located at "docs/build/". You can open the HTML file directly to see the changes. 

## To update the GITHUB page 

You just have to push the new code to gh-pages branch. There is a github workflow that will automantically build the new HTML from your updated files. 

