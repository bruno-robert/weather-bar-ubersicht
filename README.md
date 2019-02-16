# weather-bar-ubersicht
A weather widget


The screenshot contains other widgets, this repo is for the weather widget only
![weather](https://github.com/uranium78/weather-bar-ubersicht/raw/master/Screenshot%202019-02-16%20at%2011.52.55.png)

# Setup

Your going to want to head over to [weatherwidget.io](https://weatherwidget.io), from here you can customise your weather widget. Once you are done, press the "get code button". It's going to give you a bunch of code but for this widget you only need a small part, namely the `<a>` tag that is located at the start of teh given code (example: ```<a class="weatherwidget-io" href="https://forecast7.com/en/40d71n74d01/new-york/" data-label_1="NEW YORK" data-label_2="WEATHER" data-theme="original" >NEW YORK WEATHER</a>```). 

Once you have your `<a>` tag, just head over to the code and replace the current `<a>` tag, located in the "render" function, with yours (you can also add multiple `<a>` tags to have multiple locations).
