```python
class Alex(Explorer):
    def __init__(self):
        self.professional_status = {
            "role" : "Machine Learning Research Engineer", 
            "company" : "Blue Halo",
        }
        self.degree_status = {
            "level" : "MSE", 
            "degree": "Biomedical Engineering"
            "concentration" : "Biomedical Data Science",
            "institution" : "Johns Hopkins University",
        }
        self.languages = ["python", "R", "rust", "bash"]
        self.favorite_packages = ["pytorch", "numpy", "scipy", "pandas", "sklearn", "matplotlib", "seaborn"]
        self.tools = ["docker", "git", "linux", "aws", "photoshop", "jupyter"]
    
    def work(self, *tasks):
        while self.focus(*tasks):
            self.enjoy()
 ```
