
This is the source code for the project FACTORY  [https://projectfactory.github.io/](https://projectfactory.github.io/)

#### Structure 
The complete site's content is based on a json/xml file per section (e.g., ```contact.json```, ```projects.json```, ```publications.json```, ```talks.json```, and ```teaching.json```) as well as the pages ```_config.yml``` information. 


* Each section has is own file in the root folder.
* *_includes/* contains the html + liquid snippets that will fill the pages of the site.

* *_data/* contains the .json files with some content (publications, contact information, team members...) to be read by, e.g., the snippets in _includes/

* *_layouts*: layouts are to be used from the different pages. A layout says what goes before and after a page content (e.g.: headers, footers, navigation bars...)

A page in the root, for instance, uses a layout from *_layouts* and generates some content. The content can be generated using the snippets in *_includes/*

#### About this template
This site is based on the templated provided by  [Daniel Limberger](http://www.daniellimberger.de). Original source code and instructions can be found [here](https://github.com/cboettig/labnotebook)
