# Workshop materials

## Links to the recommended resources
[Good enough practices in scientific computing](https://doi.org/10.1371/journal.pcbi.1005510 "Good enough practices in scientific computing."). Wilson G, Bryan J, Cranston K, Kitzes J, Nederbragt L, et al. (2017) Good enough practices in scientific computing. PLOS Computational Biology 13(6): e1005510. https://doi.org/10.1371/journal.pcbi.1005510

[Ten Simple Rules for Reproducible Computational Research](https://doi.org/10.1371/journal.pcbi.1003285 "Ten Simple Rules for Reproducible Computational Research."). Sandve GK, Nekrutenko A, Taylor J, Hovig E (2013) Ten Simple Rules for Reproducible Computational Research. PLOS Computational Biology 9(10): e1003285. https://doi.org/10.1371/journal.pcbi.1003285

[The Practice of Reproducible Research: Case Studies and Lessons from the Data-Intensive Sciences](https://www.gitbook.com/book/bids/the-practice-of-reproducible-research/details "The Practice of Reproducible Research: Case Studies and Lessons from the Data-Intensive Sciences."). Kitzes, J., Turek, D., & Deniz, F. (Eds.). (2018). Oakland, CA: University of California Press. https://www.gitbook.com/book/bids/the-practice-of-reproducible-research/details

## Exercises

### Organization

#### Exercise 1:
* Candy trade
    * Review your selection of candy. Rate how happy you are with your selection on a scale from 1 (unhappy) to 10 (very happy). Record it on your green sticky note and label it as "pre-trade".
    * Find one trading partner. Trade the candy you don't like for candy you do like with that partner only. Rate how happy you are with your selection on a scale from 1 (unhappy) to 10 (very happy). Record it on your green sticky note and label it as "trade 1".
    * Now trade with everyone in the room. Trade candy you don't like for candy you do like. Rate how happy you are with your selection on a scale from 1 (unhappy) to 10 (very happy). Record it on your green sticky note and label it as "trade 2".

#### Exercise 2: 

* Create one repository or directory that holds all related research files.
* Organize your research to separate data, code, and results.
    * Import your data via the Github link: https://github.com/aprilcs/candy_trade  
* Resource on reproducible organization:
  * Karl Broman: [http://kbroman.org/steps2rr/pages/organize.html](http://kbroman.org/steps2rr/pages/organize.html) 

### Documentation

#### Exercise 3:

* Use literate programming to document your analyses.
    * Configure the environment for Jupyter Notebook: 
        *  Base Environment: Python 3 with Anaconda
        *  conda installer: jupyter, numpy, pandas
    * Run -> Launch interactive Jupyter Session.
    * Analyze your data!
        * Load your libraries.
        * Load your data.
        * Create a line graph showing each individual's change in happiness over the trades.
        * Create a box plot comparing the distribution of happiness over trades.
        * Download your notebook "as Notebook".

#### Exercise 4:
* Use nbconvert to render your notebook.
    * Upload your notebook into the code subdirectory.
    * In your run.sh script, use nbconvert to render your notebook.
    * Check the rendering by hitting "Run".

#### Exercise 5:
* Share your code.
    * Create two python code files: one for each figure you created (line graph & box plot).
    * Configure your run.sh file to run them in order.
    * Save the figures in the results subdirectory.
    * Check the configuration by hitting "Run"

#### Exercise 6

* Make a codebook or data dictionary.
* Resources on making a great codebook or data dictionary:
  * DataONE: [https://www.dataone.org/best-practices/create-data-dictionary](https://www.dataone.org/best-practices/create-data-dictionary)
  * McGill Codebook Cookbook: [http://www.medicine.mcgill.ca/epidemiology/joseph/pbelisle/CodebookCookbook.html](http://www.medicine.mcgill.ca/epidemiology/joseph/pbelisle/CodebookCookbook.html)
  * UPenn: [https://guides.library.upenn.edu/datamgmt/documentation](https://guides.library.upenn.edu/datamgmt/documentation)
  * Karl Broman: [http://kbroman.org/dataorg/pages/dictionary.html](http://kbroman.org/dataorg/pages/dictionary.html)
* Example codebook:
  * AJPS Replication Package: [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/EZSJ1S](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/EZSJ1S)  

#### Exercise 7:

* Create a README.txt or README.md.
* Resource on making a great README file:
  * Cornell (includes a template): [https://data.research.cornell.edu/content/readme](https://data.research.cornell.edu/content/readme)
* Resource on using markdown:
  * GitHub: [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

#### Exercise 8:

* Choose a license for your data and your code.
* Resource on choosing a data licence:
  * Digital Curation Center: [Digital Curation Centre](http://www.dcc.ac.uk/resources/how-guides/license-research-data) 
* Resource on choosing a code licence:
  * Karl Broman: [http://kbroman.org/steps2rr/pages/licenses.html](http://kbroman.org/steps2rr/pages/licenses.html)
  * Open Source Initiative: [https://opensource.org/licenses](https://opensource.org/licenses)

#### Exercise 9:

* Specify your environment and package versions.
* Example of documenting packages in your README:
  * AJPS Replication Package: [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/EZSJ1S](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/EZSJ1S) 
* Example of documenting dependencies:
  * Binder: [http://mybinder.readthedocs.io/en/latest/using.html#preparing-a-repository-for-binder](http://mybinder.readthedocs.io/en/latest/using.html#preparing-a-repository-for-binder)

### Automation

#### Exercise 10:

* Change absolute paths to relative paths.
* Resource explaining paths:
  * Karl Broman: [http://kbroman.org/steps2rr/pages/organize.html](http://kbroman.org/steps2rr/pages/organize.html)

#### Exercise 11:

* Make a master script (aka driver or controller script) and set it as main.
  * Resource on automation using a driver script: [https://www.practicereproducibleresearch.org/core-chapters/3-basic.html](https://www.practicereproducibleresearch.org/core-chapters/3-basic.html)

### Dissemination

#### Exercise 12:
* Share your code and data!