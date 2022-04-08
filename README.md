# curveasjson

This is a total hack but it works for my use case. I was looking for a fast way to synthesize a PV generation profile but only found rather complex tools on the web but nothing that spits out minute-wise data. I made this little tool, it's just a single HTML file, where you modify a spline (in my case, to the shape of the generation curve) and, via a press on the `Create JSON` button, then generate minute-wise JSON data. 

![](screenshot.png)

The drawing area is 1440 pixels wide, representing the 24 * 60 = 1440 minutes of a day. The y-axis values range from 0 (at the very bottom) to 1000 (at the very top).



