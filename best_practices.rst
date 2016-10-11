.. best_practices

Best Practices
-------------------

Document your data on ingestion::

  oneline: One-line description or title for the file
  version: PROJECT.DESCRIPTIVE_VARIABLE_NAME.YYYY-MM-DD.NUMBER

  author: your name
  contact: your email

  dependencies:
    - Dependency 1 Version
    - Dependency 2 Version

  variables:
    column 1 name: 
        long_name: Variable description
        unit: Units
        source: source
    column 2 name: 
        long_name: Variable description
        unit: Units
        source: source

  description: Anything else you’d like to say.

  important rules:
    - Spaces only - NO TABS!
    - ALWAYS INCLUDE A VERSION NUMBER!

* Document your data on modification:
  
  * Version of previous data 
  
  * Description of Version

* Document and track your code 
  
  * Use git 
  
  * Store all code on bitbucket
  
  * Make your code shareable and worthy of being shared
  
  * Document your code: write notes so others can use it
  
  * Store code in Appropriate Repo
   
    * Organized by project (e.g GCP)
    
    * Subclassed by Team (e.g conflict, mortality, ag, labor)