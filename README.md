```python
class Alex(Parents):
    def __init__(self, **kwargs):
        super().__init__(**kwargs)
        self.professional_status = {
            "role" : "Data Scientist", 
            "company" : "Creyon",
        }
        self.degree_status = {
            "level" : "MSE", 
            "degree": "Biomedical Engineering"
            "concentration" : "Biomedical Data Science",
            "institution" : "Johns Hopkins University",
        }
        self.personal_status = {
            "girlfriend": "Aina",
            "mood": "Inquisitive",
        }
        self.languages = ["python", "R", "rust", "bash"]
        self.favorite_packages = ["pytorch", "numpy", "scipy", "pandas", "scikit-learn", "matplotlib", "seaborn"]
        self.tools = ["docker", "git", "linux", "aws", "photoshop", "jupyter"]
    
    def work(self, *tasks):
        while self.focus(*tasks):
            self.enjoy()
 ```
