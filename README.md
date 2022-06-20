```
class Alex(Minimalist):
  def __init__(self):
    self.professional_status = {
      "role" : "Senior Machine Learning Engineer", 
      "company" : "Scale AI",
    }
    self.degree_status = {
      "level" : "MSE", 
      "subject" : "Biomedical Data Science",
      "institution" : "Johns Hopkins University",
    }
    self.languages = ["python", "java", "LaTeX"]
    self.py_datasci_stack = ["jupyter", "pandas", "scikit-learn", "keras", "pytorch"]
    self.tools = ["docker", "git"]
    
  def main(self):
    if not self:
      self = self.__init__()
 ```
