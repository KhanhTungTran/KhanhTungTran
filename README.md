### Hi 👋

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class DataScientist: # More like my goal than my current title :)
    def __init__(self):
        self.name = "Tung Tran" # My first name actually is Tung (not Khanh or Tran)
        self.role = "Teaching Assistant | Freelancer | AI Intern | Student"
        self.location = "Ho Chi Minh City"
        self.github = "https://github.com/KhanhTungTran"
        self.knowledge_base = [
            "Machine Learning",
            "Deep Learning",
            "Software Engineering",
        ]
        self.knowledge_base.insert(0, "Computer Vision")

    def say_hi(self):
        print(
            """Hello there, thanks for dropping by <3!

This is {name}, I live in {location}. I work as a {role} and recently I am focusing on {focus} for my personal growth.

It is true that I'm a little brag about all the roles that I showed, but yeah, I do be on multiple jobs these days, I would love to learn new things everyday :D.

I have wide interests, but most of them are {knowledge_base}.

You can find most of my work here, in my github: {github}""".format(
                name=self.name,
                location=self.location,
                role=self.role,
                focus=self.knowledge_base[0],
                knowledge_base=", ".join(self.knowledge_base[1:]),
                github=self.github,
            )
        )


me = DataScientist()
me.say_hi()

```

## 🔧 Technologies & Tools

![](https://img.shields.io/badge/OS-Windows-informational?style=for-the-badge&logo=windows&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Editor-VS_Code-informational?style=for-the-badge&logo=visual-studio-code&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-Python-informational?style=for-the-badge&logo=python&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-PyTorch-informational?style=for-the-badge&logo=pytorch&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-Keras-informational?style=for-the-badge&logo=keras&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-Jupyter-informational?style=for-the-badge&logo=jupyter&logoColor=white&color=6aa6f8)

## &#x1f4c8; GitHub Stats

<a href="https://github.com/KhanhTungTran/KhanhTungTran">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=KhanhTungTran&show_icons=true&hide=c%2B%2B,c,html&title_color=6aa6f8&text_color=8a919a&icon_color=6aa6f8&bg_color=0e1116" alt="Tung's GitHub Stats" />
</a>

<a href="https://github.com/KhanhTungTran/KhanhTungTran">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=KhanhTungTran&show_icons=true&line_height=27&count_private=true&title_color=6aa6f8&text_color=8a919a&icon_color=6aa6f8&bg_color=0e1116" alt="Tung's GitHub Stats" />
</a>

## 🙇 Special Thanks
- [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme): for giving me the ideas
- [Zhenye Na](https://github.com/Zhenye-Na): Most of the stuffs on this readme is taken and modified from his
