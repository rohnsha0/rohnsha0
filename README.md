```bash
class RohanShaw:
    def __init__(self):
        self.name = "Rohan Shaw"
        self.role = "Data Science Fresher"
        self.education = {
            "degree": "B.Tech. in Computer Science & Engineering",
            "specialization": "Data Science",
            "institution": "Future Institute of Engineering & Management",
            "duration": "Sept 2022 - Ongoing"
        }
        self.contact = {
            "email": "rohnsha0@gmail.com",
            "website": "rohanshaw.me/",
            "github": "rohnsha0",
            "linkedin": "rohnsha0",
            "twitter": "@rohnsha0"
        }
        self.skills = [
            "Python", "TensorFlow", "Keras", "Scikit-Learn",
            "NumPy", "Pandas", "Matplotlib", "Seaborn", "Plotly",
            "Android Development"
        ]
        self.tech_stack = [
            "Data Science", "Artificial Intelligence",
            "TensorFlow", "Python", "FastAPI",
            "Serverless AWS", "Google Cloud Platform",
            "Kotlin", "MVVM", "Jetpack Compose",
            "Android Development"
        ]

    def projects(self):
        return [
            {
                "name": "StockSense: Analyze & Predict",
                "description": "One-stop solution for stock predictions using LSTM and Python",
                "technologies": ["Python", "LSTM", "FastAPI", "AWS Serverless", "Android"],
                "duration": "May 2023 - July 2023"
            },
            {
                "name": "SwasthAI",
                "description": "Uses Computer Vision to predict diseases from medical images",
                "technologies": ["Computer Vision", "NLP", "Android", "GCP Cloud Run", "FastAPI"],
                "duration": "Oct 2023 - Ongoing"
            }
        ]

if __name__ == "__main__":
    rohan = RohanShaw()
```
