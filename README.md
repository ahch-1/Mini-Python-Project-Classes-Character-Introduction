[OOP.py](https://github.com/user-attachments/files/24330137/OOP.py)
class enemies():
        def __init__(self, name, hp, power):
           self.name = name
           self.hp = hp
           self.power = power
        def enemy_introduction(self):
           print(f"{self.name} is an enemy with {self.hp}HP and a strength of {self.power}")
class protagonist():
        def __init__(self, name, hp, power):
            self.name = name
            self.hp = hp
            self.power = power
        def protagonist_introduction(self):
            print(f"you're {self.name}, you have {self.hp}HP and a strength of {self.power}")

bad_guy = enemies("Bad", 100, 30)
bad_guy.enemy_introduction()
you = protagonist("John", 200, 60)
you.protagonist_introduction()
