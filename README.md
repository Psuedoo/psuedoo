![Views Badge](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2F{psuedoo}1212%2Fhit-counter)

```py
class Psuedoo:

  def __init__(self):
    self.username = 'psuedoo'
    self.stack = {
        'frontend': ['NextJS', 'Tailwind CSS'],
        'backend': ['Python', 'FastAPI', 'Django', 'Scala'],
        'database': ['PostgreSQL', 'SQLite3'],
        'devops': ['Docker', 'Nginx'],
        'tools': ['GIT', 'GitHub', 'GitLab', 'SQLAlchemy'],
    }
    self.socials = {
        'Discord': '_psuedo',
    }
    
    def __str__(self):
      return self.username

if __name__ == '__main__':
  me = Psuedoo()
```
