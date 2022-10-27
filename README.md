```py
from toutch_grass import grass
from requests import get

class answers:
    def __init__(self):
        self.grass = grass.com

    def request(self):
        req = get(self.grass)
        if req.json()["Toutched_Grass"] == True:
            print("Lying")

        if req.json()["Toutched_Grass"] == False:
            print("Truth")

    def media(self) -> tuple:
        instagram = "sokisa.dev"
        discord   = "Sokisa#1382"
        server    = "https://discord.gg/2s59xkx8Yu"

        return instagram, discord, server

    def platforms(self) -> tuple:
        Project_Platforms = ["Tiktok", "Xbox", "Twitch", "Discord"]
        Lang              = ["Python"]

        return Project_Platforms, Lang
```





<h3 align="left">Language:</h3>
<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=sokisa&show_icons=true&locale=en" alt="sokisa" /></p>
[![Discord Presence](https://lanyard.cnrad.dev/api/986309129683492894)](https://discord.com/users/986309129683492894)
