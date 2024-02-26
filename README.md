## shinykasabot
### a telegram bot to control tp-link smart bulbs
- controls bulbs with (python-kasa)[https://github.com/python-kasa/python-kasa]
- written in python using (pyTelegramBotAPI)[https://pypi.org/project/pyTelegramBotAPI/]
- (singlecolorimage.com)[https://singlecolorimage.com/api.html] to fetch color previews

#### commands:
  * `/status`: show current bulb status
  * `/rgb`: set bulb to color (`r` `g` `b`)
  * `/brightness`: set bulb brightness (`1-100`)
  * `/preset`: set bulb to color preset (`default`, `white`, `red`, `orange`, `yellow`, `green`, `blue`, `purple`, `pink`)
  * `/off`: turn bulb off
