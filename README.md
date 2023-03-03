<b>

```python
from dataclasses import dataclass


@dataclass
class Profile:
    summary: str = "I am a novelist whose readers are computers. I specialize in writing 'backend' and 'python' style stories, currently."
    languages: tuple[str, ...] = ("Python", "JavaScript", "PHP", "Java")
    databases: tuple[str, ...] = ("MySQL", "Redis", "MongoDB")
    misc: tuple[str, ...] = ("Git", "Docker", "NeoVim", "Flask")
```

</b>
