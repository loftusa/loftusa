```python
class Alex(Minimalist):
    def __init__(self):
        self.professional_status = {
            "role" : "Machine Learning Engineer", 
            "company" : "Blue Halo",
        }
        self.degree_status = {
            "level" : "MSE", 
            "degree": "Biomedical Engineering"
            "concentration" : "Biomedical Data Science",
            "institution" : "Johns Hopkins University",
        }
        self.languages = ["python", "R", "rust"]
        self.favorite_packages = ["jupyter", "numpy", "pandas", "seaborn", "scikit-learn", "pytorch"]
        self.tools = ["docker", "git"]
    
    def work(self, *tasks):
        self.sit()
        self.focus(*tasks)
        self.enjoy()
 ```
