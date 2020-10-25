Title: Python
Date: 2020-10-25 15:39
Author: Valentin
Tags: wiki, pelican, python, machine learning, unix

## Notes et projets

Superposer deux images avec pillow

```python
from PIL import Image

background = Image.open("image1.png")
front = Image.open("image2.png")
background.paste(front, (0, 0), front)
background.save('image1+2.png',"PNG")
```
