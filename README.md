```python
class AboutMe(object):
    def __init__(self) -> None:
        self.name: str = "Felipe Alves"
        self.role: str = "Software Developer"
        self.spoken_languages: list = [
            "pt_BR",
            "en_US",
        ]

        self.daily_knowledge: list = [
            # Front-End
            "HTML",
            "CSS",
            "JavaScript",
            "Vue.js",
            # Back-End
            "PHP",
            "Python",
            "Flask",
            "Django",
            # Database
            "MySQL",
            "SQLite",
            # Operating System
            "Linux",  # Using Fedora
            "Windows",  # Using Windows 11
            "macOS",  # Not using
        ]

        self.fun_fact: str = "I healed from OCD a few days ago."

        self.goals: dict = {
            "Personal": "Make up for the time I lost due to OCD.",
            "Professional": "Solve problems and help people.",
        }
```
