```py

#!/usr/bin/python
# -*- coding: utf-8 -*-

class n9rd:
  
  def __init__(self):
    self.name = "Nick"
    self.role = "Student"
    self.age = 13
    self.language = ["en_US"]
   
  def welcome(self):
    print(f"""
      Welcome to my GitHub profile! 😁👋

      I'm {self.name} and I'm currently a {self.role}.
      I'm {self.age} years old and I only speak {self.language[0]}.
      
      I hope you enjoy your stay, have a nice day!
    """)
    
me = n9rd()
me.welcome()

```
