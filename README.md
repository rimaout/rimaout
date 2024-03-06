```python
from typing import Tuple, List, Dict

class rimaout:
    pass

class Attributes(rimaout):
    @property
    def contact(self) -> Tuple[str, str, str, str]:
        discord  = "YourDiscordUsername"
        telegram = "YourTelegramUsername"
        linkedin = "YourLinkedInProfile"
        email    = "YourEmail"
        
        return discord, telegram, linkedin, email

    @property
    def personal(self) -> Tuple[List[str], List[str], int]:
        uni = ['Sapienza Rome', 'Computer Science'] 
        languages = ['English', 'Italian']
        age   = 21
        
        return uni, languages, age
    
    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str]]:
        skills = {
            'expert'      : [None],
            'intermediate': ['Python'],
            'learning'    : ['Java', 'Rust']
        }
        environment = ['Visual Studio Code', 'NVIM']

        return skills, environment

```

