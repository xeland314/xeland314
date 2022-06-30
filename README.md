<div align="center">

# System.out.println("Hello, world 👋");

</div>

<p align="center"> <img src="https://komarev.com/ghpvc/?username=xeland314&label=Profile%20views&color=0e75b6&style=flat" alt="xeland314" height="20" /></p>

``` Python
class Person:
    def __init__(self, name):
        self.__name = name
    
    @property
    def name(self) -> str: return self.__name
	
    def say_hello(self):
        print(f"Hi, everybody! I'm {self.name}.", sep=" ")

class Programmer(Person):
    def __init__(self, person, alias):
        super().__init__(person.name)
        self.__alias = alias
    
    def __str__(self) -> str: return f"{self.__alias} is {self.name}."

if __name__ == "__main__":
    me = Person("Christopher Villamarín")
    me.say_hello()
    me = Programmer(me, "xeland314")
    print(me, type(me), isinstance(me, Person))
```

### Skills

- [x] ☕ OOPs in Java and swing.
- [x] 🐍 Python GUIs designed with PyQt5.
- [x] 💻 C programming with Lex & Yacc.
- [ ] 👀 I’m interested in Matplotlib, Numpy and others statistical libraries.
- [ ] 🌱 I’m currently learning database management.

<p align="center">&nbsp;

<img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=xeland314&layout=compact&theme=city_lights&langs_count=10t" alt="xeland314" />

</p>
