# slide-clean-standalone

### Used to create standalone python environment to run script for anonymizing WSI  

## Run Script  
1.)	Copy 1 or more slides into WSI folder in project folder  
2.)	Open CMD prompt  
3.)	Run anonymize-slide.py script in the project folder  
  *  C:\path\to\python.exe <path to script> <path to WSI>    
    *  To anonymize more then one slide, simply add multiple paths to the ARGS  
  *  For example (in current folder): D:\slide-clean-standalone\python27\python D:\slide-clean-standalone\anonymize-slide.py D:\slide-clean-standalone\WSI\test-1.svs  


### Notes:  
TODO - upgrade to python3  
Python 3 Setup - need to modify 2 dependencies  
- Download slide-anonymize script  
  https://github.com/DeepPathology/AnonymizeSlide  
- Download embeddable python (ver 3.8.9)
  https://www.python.org/downloads/windows/  
- Download get-pip.py from PIP (to enable installation of packages) (https://www.christhoung.com/2018/07/15/embedded-python-windows)  
  https://pip.pypa.io/en/stable/installation/  
- Run `python get-pip.py`
- Install dependencies
