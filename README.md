# OLD GOOGLE SEARXNG STYLE
<img width="1920" height="944" alt="image" src="https://github.com/user-attachments/assets/7332c977-ce09-4169-a936-9522f6f5811a" />
<img width="1920" height="946" alt="image" src="https://github.com/user-attachments/assets/cd5cebaa-eec1-415a-97b1-ac0cbf96b52e" />

# instructions

### 1
add theme to stylus:

1) click extensions icon on your browser
2) click stylus
3) click manage
4) click to add style
<img width="304" height="243" alt="image" src="https://github.com/user-attachments/assets/098bbdec-fcc0-4765-88f7-4222593a94eb" />
5) copy the css in main.css
6) go back to the css editor
7) do ctrl+a and ctrl+v to paste
8) change the urls like below:
```
url-prefix("http://127.0.0.1:8888/search")
url("http://127.0.0.1:8888/")
url-prefix("http://127.0.0.1:8888/")
```
to:
```
url-prefix("\<the url you will use\>/search")
url("\<the instance url will use\>/")
url-prefix("\<the url you will use\>/")
```

### be happy
