This repository represents the coding conventions and other practical information for contributing to AnalogIO.

Conventions
===========
###Where to place what on the server?
Projects/repositories should be placed on the server in “/var/www/projectName/”. A roresponding .config file should then be placed in “/etc/nginx/sites-available/projectName.config” and symlinked with ```$ sudo ln -s /etc/nginx/sites-available/filename /etc/nginx/sites-enabled/filename```. To restart the nginx server now run ```$ sudo service nginx restart ```

###Workflow
All projects should be versioned properly with git and the AnalogIO github repository. It is encouraged to use the git flow workflow when working on projects with more than one contributer.

* Which DB to use?
* Coding style
* List of current projects

Perks
===========
While coding on something relevant for AnalogIO, Analog provides free coffee.
You get to work on interesting projects, using languages and frameworks of your own choice.

Meetings
===========
In the fall semester of 2014, we meet every Thursday from 16:00 until whenever.
