```python
from typing import Tuple, List, Dict

class rimaout:
    pass

class Attributes(rimaout):

    @property
    def contact(self) -> Tuple[str, str]:
        matrix  = "@rimaout:matrix.org"
        email   = "oettam.do@tuta.io"
        
        return matrix, email

    @property
    def life(self) -> Tuple[List[str], List[str], int]:
        uni   = ['Sapienza Rome', 'Computer Science'] 
        langs = ['English', 'Italian']
        age   = 21
        
        return uni, langs, age
    
    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str]]:
        skills = {
            'expert'      : [None],
            'intermediate': ['Python'],
            'learning'    : ['Java', 'Rust']
        }
        tools = ['Visual Studio Code', 'Obsidian']

        return skills, tools

    @property
    def public_work(self) -> Dict[str, str]:
        work_links = {
                'uni_notes'    : 'https://notesinpublic.xyz',
                'lates_projct' : 'https://github.com/rimaout/flac2mp3'
            }

        return work_links

```

