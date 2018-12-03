# micro.bit

from microbit import *

# declare counter: set to 0
counter = 0

#forever
while True:
    if button_a.is_pressed():
        counter += 1
        display.scroll(str(counter),100)
