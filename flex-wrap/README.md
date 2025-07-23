## How to use flex wrap or if you want The cards are arranged horizontally, but wrap to multiple lines when they run out of room on the page.

So here’s the magic trick 🎩 — all you gotta do is make the container a flex box, set flex-direction to row (which is actually the default), and add a little flex-wrap: wrap;. This tells your flex container, “Hey, if things get too tight in here, feel free to break the line and start a new row!” 

We’re applying this to the .cards container so that when the screen gets squishy (like when you shrink the browser), the cards don’t stubbornly stay in one row — they gracefully wrap onto the next line, like pros. 

Seriously, try it! Run your HTML file in the browser and slowly shrink the window. Watch the flex-wrap magic unfold in real time.