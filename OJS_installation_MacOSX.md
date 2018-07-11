* Install [Mamp](https://www.mamp.info/en/)
* Download [OJS](https://pkp.sfu.ca/ojs/ojs_download/)
* Unzip the file downloaded from the OJS site with an extension `.tar.gz` (ie. `ojs-3.1.1-1.tar.gz`) in this address `/Applications/MAMP/htdocs`
* Rename the default name of the folder (ie. `OJS`) to the desired name (ie. `TemasMedievales`).
* Open Terminal (`Finder` --> `Go` --> `Utilities` --> `Terminal`)
* Run this command:
     ```
     cd /tmp && ln -s /Applications/MAMP/tmp/mysql/mysql.sock
     ```
* Close Terminal
* Launch `Mamp`
* Click on `Start Servers`
* Go to `Tools`
* Click on `PhpMyAdmin`
* Click in the upper section `Databases`
* On `Create database` enter the name for the brand new database. Then click on `Create`
* Once created, in the upper menu, click on `Server: localhost:8889`
* Click on `Databases`
* Choose your recently created database and select it. Then click on `Check privileges`
