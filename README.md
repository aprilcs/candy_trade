# Tutorial materials

## Links to the recommended resources
[Good enough practices in scientific computing](https://doi.org/10.1371/journal.pcbi.1005510 "Good enough practices in scientific computing."). Wilson G, Bryan J, Cranston K, Kitzes J, Nederbragt L, et al. (2017) Good enough practices in scientific computing. PLOS Computational Biology 13(6): e1005510. https://doi.org/10.1371/journal.pcbi.1005510

[Ten Simple Rules for Reproducible Computational Research](https://doi.org/10.1371/journal.pcbi.1003285 "Ten Simple Rules for Reproducible Computational Research."). Sandve GK, Nekrutenko A, Taylor J, Hovig E (2013) Ten Simple Rules for Reproducible Computational Research. PLOS Computational Biology 9(10): e1003285. https://doi.org/10.1371/journal.pcbi.1003285

[The Practice of Reproducible Research: Case Studies and Lessons from the Data-Intensive Sciences](https://www.gitbook.com/book/bids/the-practice-of-reproducible-research/details "The Practice of Reproducible Research: Case Studies and Lessons from the Data-Intensive Sciences."). Kitzes, J., Turek, D., & Deniz, F. (Eds.). (2018). Oakland, CA: University of California Press. https://www.gitbook.com/book/bids/the-practice-of-reproducible-research/details

[Jupyter Notebooks and reproducible data science](https://markwoodbridge.com/2017/03/05/jupyter-reproducible-science.html). Woodbridge M, Sanz D, Mietchen D, & Mounce R (2017). 

## Exercises

#### Exercise 1:
* Candy trade
    * **Pre-trade** Review your selection of candy. Rate how happy you are with your selection on a scale from 1 (unhappy) to 10 (very happy). 
        * In [**this google form**](https://goo.gl/forms/Mxi2fKrOYc9UCB9j1), record your first name, your candy happiness rating, and select trade number "0".
    * **Trade 1** Find one trading partner. Trade the candy you don't like for candy you do like with that partner only. Rate how happy you are with your selection on a scale from 1 (unhappy) to 10 (very happy). 
        * In [**this google form**](https://goo.gl/forms/Mxi2fKrOYc9UCB9j1), record your first name, your candy happiness rating, and select trade number "1".
    * **Trade 2** Now trade with everyone in the room. Trade candy you don't like for candy you do like. Rate how happy you are with your selection on a scale from 1 (unhappy) to 10 (very happy). 
        * In [**this google form**](https://goo.gl/forms/Mxi2fKrOYc9UCB9j1), record your first name, your candy happiness rating, and select trade number "2".

### Organization

#### Exercise 2: 

* Create one repository that holds all related research files: data, code, notebooks, documentation, etc.
    * Example: import your research materials via the Github link: https://github.com/aprilcs/candy_trade 

#### Exercise 3:
* Organize your research to separate code + notebooks from data. 
* Resource on reproducible organization:
  * Karl Broman: [http://kbroman.org/steps2rr/pages/organize.html](http://kbroman.org/steps2rr/pages/organize.html) 

### Documentation

#### Exercise 4:

* Configure the run environment for your Jupyter Notebook using a container technology.
     *  Example: Base Environment: Python 3 with Anaconda
     
#### Exercise 5:

* Specify your packages and dependencies with versions.
    * Example: conda installer: jupyter, numpy, pandas
    * pip freeze > ../code/requirements.txt
    * conda list --export > ../code/requirements.txt
* Resource on documenting dependencies:
  * Binder: [http://mybinder.readthedocs.io/en/latest/using.html#preparing-a-repository-for-binder](http://mybinder.readthedocs.io/en/latest/using.html#preparing-a-repository-for-binder)
  
#### Exercise 6:

* Create a README.txt or README.md.
* Resource on making a great README file:
  * Cornell (includes a template): [https://data.research.cornell.edu/content/readme](https://data.research.cornell.edu/content/readme)
* Documenting packages in your README:
  * AJPS Replication Package: [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/EZSJ1S](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/EZSJ1S) 
* Resource on using markdown:
  * GitHub: [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) 

#### Exercise 7:

* Create a data dictionary.
* Resources on making a great data dictionary:
  * DataONE: [https://www.dataone.org/best-practices/create-data-dictionary](https://www.dataone.org/best-practices/create-data-dictionary)
  * McGill Codebook Cookbook: [http://www.medicine.mcgill.ca/epidemiology/joseph/pbelisle/CodebookCookbook.html](http://www.medicine.mcgill.ca/epidemiology/joseph/pbelisle/CodebookCookbook.html)
  * UPenn: [https://guides.library.upenn.edu/datamgmt/documentation](https://guides.library.upenn.edu/datamgmt/documentation)
  * Karl Broman: [http://kbroman.org/dataorg/pages/dictionary.html](http://kbroman.org/dataorg/pages/dictionary.html)
* Example codebook:
  * AJPS Replication Package: [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/EZSJ1S](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/EZSJ1S)  

### Automation

#### Exercise 8:

* Create a master script that executes your notebooks in order.
   * Create a file in the code directory.
   * Name the file "run.sh".
* Use nbconvert to render your notebook.
   * In your run.sh script, use nbconvert to execute your notebook into the results directory.
* Resource on automation using a driver script: [https://www.practicereproducibleresearch.org/core-chapters/3-basic.html](https://www.practicereproducibleresearch.org/core-chapters/3-basic.html)

#### Exercise 9:

* Change absolute paths to relative paths.
* Resource explaining paths:
  * Karl Broman: [http://kbroman.org/steps2rr/pages/organize.html](http://kbroman.org/steps2rr/pages/organize.html)

### Dissemination

#### Exercise 10:

* Specify a license for your data and your code + notebooks.
* Resource on choosing a data licence:
  * Digital Curation Center: [Digital Curation Centre](http://www.dcc.ac.uk/resources/how-guides/license-research-data) 
* Resource on choosing a code licence:
  * Karl Broman: [http://kbroman.org/steps2rr/pages/licenses.html](http://kbroman.org/steps2rr/pages/licenses.html)
  * Open Source Initiative: [https://opensource.org/licenses](https://opensource.org/licenses)

#### Exercise 11:
* Share your notebooks!
    * Check whether your container is ready to publish by hitting "Run". 
    * Following the dropdown next to "Run", start an interactive Jupyter session.
