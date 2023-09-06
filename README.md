### Hi there

```python

from dataclasses import dataclass
from typing import Tuple


class Meta(type):
    def __new__(cls, name, bases, attrs):
        new_cls = super().__new__(cls, name, bases, attrs)
        return dataclass(unsafe_hash=True, frozen=True)(new_cls)


class Bio(metaclass=Meta):
    name        : str = "Pemba Tamang"
    designation : str = "Django Developer"
    company     : str = "Pemba T. Tech"
    base        : str = "Kathmandu, Nepal"
    website     : str = "pembatamang.com.np"

class Stack(metaclass=Meta):
    languages   : Tuple[str, ...] = ("Python", "HTML", "CSS", "JavaScript")
    databases   : Tuple[str, ...] = ("MySQL", "PostgreSQL")
    misc        : Tuple[str, ...] = ("Docker", "Celery")
    ongoing     : Tuple[str, ...] = ("Python", "Django")

```

#

### ☎️ With Me

[<img alt="pemba.portfolio" width="80px" src="gifs/internet.gif" />](https://www.pembatamang.com.np)
[<img alt="Pemba Tamang | LinkedIn" width="107px" src="https://i.pinimg.com/originals/de/b4/6f/deb46f02a59e3b3a2aa58fac16290d63.gif" />](https://www.linkedin.com/in/pemba-tamang)
[<img alt="Pemba T. Tech | Twitter" width="80px" src="gifs/twitter1.gif" />](https://www.twitter.com/pembattech)
[<img alt="titungpemba | Instagram" width="107px" src="https://thumbs.gfycat.com/OrnateOrneryFoal-max-1mb.gif" />](https://www.instagram.com/titungpemba)
[<img alt="Pemba T. Tech | YouTube" width="92px" src="gifs/youtube.gif" />](https://www.youtube.com/c/pembattech)

#

### 🧰 Languages and 🔧🔨✂️

<img align="left" alt="Python" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-plain.svg" />
<img align="left" alt="Django" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/npm/simple-icons@3.13.0/icons/django.svg" />
<img align="left" alt="HTML" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain.svg" />
<img align="left" alt="CSS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain.svg" />
<img align="left" alt="JavaScript" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" />
<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
<img align="left" alt="GitHub" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />
<img align="left" alt="Linux" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" />

<br />
<br />

#

#### Fun fact: I once solved the world's oldest question with a single line of Python

```python
# Which came first: the chicken or the egg?
print(sorted(['🥚', '🐣', '🐥', '🐔']))

>>> [ '🐔', '🐣', '🐥', '🥚' ]
```
#
<details>
<summary>
<font size= "3">📊 Stats </font>
</summary>

![Pemba's GitHub stats](https://github-readme-stats.vercel.app/api?username=pembattech&show_icons=true&theme=slateorange)

![GitHub Streak](https://streak-stats.demolab.com?user=pembattech&theme=slateorange&border_radius=4.5)

</details>


#
