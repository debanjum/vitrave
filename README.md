Vitrave
=============
> Use visual landmarks to simplify UI traversal in automation scripts

This repo is based on [Erikb' gist](https://gist.github.com/eirikb/ac8196beb0b57577a8fc47eb18427bd4) and [Szanni's findimage](https://szanni.org/findimage/)<br />
It integrates sensing of visual landmark to simplify creating automation scripts.<br />
We use `findimage` to identify the visual landmarks on screen and `xdotool` for actually traversing the GUI.


DEPENDENCIES
---------------
1. Xdotool
3. Scrot
2. OpenCV


QUICK-START
---------------
```sh
git clone https://github.com/debanjum/vitrave.git   # clone repository
cd findimage && make && sudo make install           # compile and install findimage
cd ../demo && chmod +x demo.sh && ./demo.sh         # run sample automation script
```


DEMO
---------------
![](http://i.imgur.com/1BpMKpe.gif)

##About
The demo is meant to show how to make an automated answer to a hn comment, translated from Norwegian to English with these steps:

1. Click on Chrome address bar.
2. Type translate.google.com and press enter.
3. Click on input field.
4. Type the text for translation and wait for it to translate.
5. Click "Copy"-button to copy text to clipboard.
6. Open new tab.
7. Type hn comment url and press enter.
8. Click on input field.
9. Paste translated text.


##Images

1.png  
![](http://i.imgur.com/yXwDmsx.png)
---
2.png  
![](http://i.imgur.com/DzJVEE3.png)
---
3.png  
![](http://i.imgur.com/hM2lXzw.png)
---
4.png  
![](http://i.imgur.com/M6wZ7QX.png)
---
5.png  
![](http://i.imgur.com/Vtmivlj.png)


CONTRIBUTING
---------------
Fork, Edit and Submit [pull request](https://github.com/debanjum/vitrave/pulls)


BUGS
---------------
Please file bug reports at [issues](https://github.com/debanjum/vitrave/issues)
