<h1>Flight_Deal_Finder</h1>

<h2>Description</h2>

In this challenge we're going to be using a combination of different APIs to create a cheap flight finder. This program is going to find amazing flight deals just for ourselves.

So here's how my program works. First, we have a Google sheet which keeps track of the locations that we want to visit and a price cutoff. So a historical low price. So we take this data from our Google sheet with lots of different locations and their lowest prices and we feed that into a flight search API, which is going to run every day, searching through all of the locations looking for the cheapest flight in the next six months. When it comes up with a hit and it finds a flight that's actually cheaper than our predefined price, then it's going to send that date and price via our Twilio SMS module to our mobile phone so that we can book it right there and then.

<h2>Languages and Utilities Used</h2>

- <b>Python</b>
  
<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program walk-through:</h2>

<p align="center">
Flight_Deal_Finder: <br/>
<a href="https://imgur.com/oAGR7kP"><img src="https://i.imgur.com/oAGR7kP.jpg" title="source: imgur.com" /></a>
<a href="https://imgur.com/oFchoHG"><img src="https://i.imgur.com/oFchoHG.jpg" title="source: imgur.com" /></a>
<a href="https://imgur.com/NkOJtAB"><img src="https://i.imgur.com/NkOJtAB.jpg" title="source: imgur.com" /></a>
