### TikZ animation


![Animated SWS](images/SWS.gif)


To convert the .pdf to an animated .gif file, I used:
```
convert -density 400 -delay 13 -loop 0 -background white -alpha remove animateSWS.pdf images/SWS.gif
```
