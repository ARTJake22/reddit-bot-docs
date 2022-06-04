| Description      |
| ------------- |
|  RegexMatchError      | 

# Error 5


![image](https://user-images.githubusercontent.com/76000584/171999530-51d2947d-eb4b-4912-8830-1e7429445f01.png)



This error is related to the pytube module. To fix this you can either:

## 1
Go to your cipher.py file in your C:\Users\<user>\AppData\Local\Programs\Python\<PythonVersion>\Lib\site-packages\pytube and change line 30 to 
```python
var_regex = re.compile(r"^\$*\w+\W")
```

## 2
Download the background video yourself, but make sure you name the video "background" and it is saved as a .mp4 in your \RedditVideoMakerBot\assets\mp4 folder.
