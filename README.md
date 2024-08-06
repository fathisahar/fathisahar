# <img src="https://raw.githubusercontent.com/iampavangandhi/iampavangandhi/master/gifs/Hi.gif" width="30px">

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class Sahar:
    def __init__(self):
        self.name = "Sahar Fathi"
        self.role = "Software Engineering Student"
        self.university = "McGill University"
        self.pronouns = ["she", "her"]
        self.programming_languages = [
            "Java", "JavaFX", "JavaScript", "TypeScript", "Python", "C", "VB", "VBA", "Bash", "OCaml"
        ]
        self.frameworks_libraries = [
            "React Native", "Vue.js", "Flask-SQLAlchemy", "Flask", "Spring", "JUnit", "Cucumber", "Gherkin", "Umple"
        ]
        self.web_technologies = [
            "HTML", "CSS"
        ]
        self.databases = [
            "MySQL", "PostgreSQL", "MariaDB"
        ]
        self.tools = [
            "Git", "GitHub", "Linux/Unix", "GNU Toolchain"
        ]

    def say_hi(self):
        print(f"hi, i'm sahar and i like to code. thanks for dropping by :P")


me = Sahar()
me.say_hi()
