```bash
import datetime

class ReadMe:
    def __init__(self, username):
        self.username = username
        self.name = 'Rohan Shaw'
        self.education = {
            'programming': ['Data Science', 'Machine Learning', 'Deep Learning', 'Android Development', 'Backend']
        }
        self.employment = {
            'developer': ['College Fresher', 'Kolkata, India'],
            'projects': {
                'current': ['MedBuddy AI', 'Computer-Vision based application for disease detection from medical scans'],
                'previous': ['StockSense', 'Real-time stock prediction (Completed in Aug 2023)']
            }
        }

    def github_stats_badge(self):
        return {
            'GitHub stats': f'https://github-readme-stats.vercel.app/api?username={self.username}&show_icons=true&theme=radical'
        }

    def doing(self, year):
        today = datetime.datetime.now().year

        if year == today:
            current_study = self.education['programming']
            return f"""
            Hi there! 👋 I'm {self.name}, a college fresher currently diving into {', '.join(current_study)}.
            Currently studying NLP and Computer-Vision.
            """

        elif year > today:
            current_project = self.employment['projects']['current']
            return f"""
            I'm currently working on {current_project[0]}, a {current_project[1]}.
            Looking forward to collaborating on Android Development, Data Science, or Machine Learning projects.
            """

        else:
            return """
            ### Hi there 👋
            """

me = ReadMe("rohnsha0")
