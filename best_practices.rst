.. best_practices

Best Practices
-------------------

The CIL ingests and produces LOTS of data! That data enters the system from a variety of primary sources. You, the RAs, take that and turn it into valuable analysis. Your analysis is a data output that serves as an input into other analytical process, either internally within your research teams or to the greater CIL team and beyond. 

At any given moment there is a tremendous amount of data moving around the system. Researchers are building data sets from primary sources. Or they may be loading data from our servers on Shackleton or Griffin. Or they may be running analytical models and writing outputs to files on Shackleton or Griffin. 

Knowing the state of your data, its provenance and its purpose is important. This is true not only for your own use but anyone else who you may be working with now and in the future. 


Documentation
~~~~~~~~~~~~~~~~~~

Data and code should be documented:

1. **Any time new data enters the system.** Whichever team member creates or downloads a new dataset from anywhere is responsible for documenting the source, tracking down any relevant citations, and providing notes so others will understand the methods, use cases, and limitations of the data.

2. **When you pass data between team members.** We have a big team, and handing off undocumented data just doesn't work. Make sure you include a header!

3. **When your team is finalizing/publishing an impact function**. Documenting code and data is always good practice, but this is especially important for all of the steps, from primary sources to final outputs, that go into a publication or Monte Carlo run.

How to document
~~~~~~~~~~~~~~~

**Document your data on ingestion**

.. literalinclude:: sample.csv
   :language: yaml
   :linenos:

These headers are written in the `YAML syntax <http://pyyaml.org/wiki/PyYAMLDocumentation#YAMLsyntax>`_. For more information on ImpactLab headers see the `MetaCSV <http://metacsv.readthedocs.io/en/latest/>`_ package.
 

**Document your data on modification**
  
  * Use consistent variable names, but update the timestamp & release number
  
  * Describe the changes in this version

**Document and track your code**
  
  * Use git 
  
  * Store all code on bitbucket
  
  * Make your code shareable and worthy of being shared
  
  * Document your code: write notes so others can use it
  
  * Store code in Appropriate Repo
   
    * Organized by project (e.g GCP)
    
    * Subclassed by Team (e.g conflict, mortality, ag, labor)