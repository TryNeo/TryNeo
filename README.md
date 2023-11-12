```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class TechnologistSoftwareDevelopment:

    def __init__(self):
        self.name = "Josue Lopez"
        self.role = "software development technologist"
        self.language_spoken = ["es_ES"]
        self.work = ['Credimatic']
        self.hobbies = ['Gym','Games','Memes']
        self.age = 23

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")

if __name__ == "__main__":
   me = TechnologistSoftwareDevelopment()
   me.say_hi()
```
