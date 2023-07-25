![Views Badge](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2F{psuedoo}1212%2Fhit-counter)

```py
class Psuedoo:

  def __init__(self):
    self.username = 'psuedoo'
    self.stack = {
        'frontend': ['React', 'VueJS', 'JavaScript', 'Bootstrap'],
        'backend': ['Python', 'Go', 'Flask', 'FastAPI', 'Django'],
        'database': ['PostgreSQL', 'MySQL', 'SQLite3', 'MariaDB'],
        'devops': ['Docker', 'Nginx', 'Terraform', 'Ansible'],
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
