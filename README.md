<h2 align="center">About Me </h2>

```python
from typing import Tuple, List, Dict

class rimaout:
    pass

class Attributes(rimaout):

    @property
    def contact(self) -> Tuple[str, str]:
        matrix   = "@rimaout:matrix.org"
        email    = "oettam.do@tuta.io"
        telegram = "@rimaout"
        
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
            'intermediate': ['Python', 'java'],
            'learning'    : ['Rust']
        }
        tools = ['nvim', 'Obsidian']

        return skills, tools

    @property
    def public_work(self) -> Dict[str, str]:
        work_links = {
                'uni_notes'      : 'https://notesinpublic.xyz',
                'latest_project' : 'https://github.com/rimaout/flac2mp3'
            }

        return work_links

```
