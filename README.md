### Welcome to my GitHub! 😎
&darr;&darr; You can find a little bit about me below &darr;&darr;
```python
from datetime import datetime

class AboutMe():
    @staticmethod
    def socials() -> tuple:
        twitter = ["/JoshFalkiner"]
        linkedin = ["/in/joshua-falkiner"]
      
        return twitter, linkedin
    
    @staticmethod
    def about() -> tuple:
        langs = ['English', 'French', 'Danish']
        nationalities = ['English', 'Irish']
        age = 24    
        
        return langs, nationalities, age
    
    @staticmethod
    def coding() -> tuple:
        langs = {
            'expert':   ['Python', 'R'],
            'intermediate': ['SQL', 'JavaScript', 'HTML', 'CSS'],
            'learning': ['Scala', 'C++']
        }
        specialities = ['data science', 'web development', 'building applications', 'data viz']
        interests = ['InfoSec', 'Network and graph analysis', 'Finance', 'Building great products']
        
        return langs, specialities, interests
    
    @staticmethod
    def projects() -> tuple:
        twitter = ['TwitterBotDetect (down due to API changes)($$$)', 'TweetViz']
        website = ['sourcery-intel.com']
        
        return twitter, website
    
    @staticmethod
    def sourcery() -> tuple:
        position = 'Co-Founder'
        start = datetime(2022, 6, 1).strftime('%Y/%m/%d')
        end = None
        current = True
    
        return position, start, end, current
  
    @staticmethod
    def cannot_reveal_name() -> tuple:
        position = 'Data Scientist'
        start = datetime(2021, 2, 1).strftime('%Y/%m/%d')
        end = datetime(2023, 1, 1).strftime('%Y/%m/%d')
        current = False

        return position, start, end, current
   
    @staticmethod
    def trucksters() -> tuple:
        position = 'Data Science intern'
        start = datetime(2020, 6, 1).strftime('%Y/%m/%d')
        end = datetime(2022, 2, 1).strftime('%Y/%m/%d')
        current = False

        return position, start, end, current

```

**DISCLAIMER**: Most of my previous work is not on GitHub due to the confidential nature of the company employing me. *Feel free to get in touch!*
