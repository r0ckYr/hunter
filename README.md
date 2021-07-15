# hunter
A simple python script for fetching urls. Inspired by Tomnomnom's meg. It just stores the pages in a different format.It saves the output in a directory called **./out** all the text in a directory named **text** and headers in **headers** inside **out**. It also extract all the javascript file names/links from the page.

**Example:**

![hunter-data](https://user-images.githubusercontent.com/73944333/125824700-ed315199-11ed-40aa-be1f-698e5791eb51.png)


# Install
```
git clone https://github.com/r0ckYr/hunter
cd hunter
python3 hunter.py urls.txt
```

# Basic usage:

urls.txt
```
https://www.example.com
https://www.example.com/robot.txt
https://www.example.com/all.js
http://example.com
https://example.com
http://example.net
```

```
python3 hunter.py urls.txt
```
