<b>

```python
from dataclasses import dataclass


@dataclass
class Profile:
    languages: tuple[str, ...] = ("Python", "JavaScript", "PHP", "Java")
    databases: tuple[str, ...] = ("MySQL", "Redis", "MongoDB")
    misc: tuple[str, ...] = ("Git", "Docker", "NeoVim", "Flask")
```

</b>
