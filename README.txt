A Pen created at CodePen.io. You can find this one at https://codepen.io/jkantner/pen/zZayxp.

 A speedometer that measures your typing speed in real time. It works like those used by typing test websites such as typingtest.com. To make it work, I had to figure out how to turn the WPM formula ( (total characters / 5) / 1 minute ) into a real-time WPM formula. So after experimenting with the tests, this is what I came up with:

((total characters / (# of times characters were recorded each second)) / 5) * 60 seconds

I got the idea to create this demo after memories of playing some racing mini game in early versions of Mavis Beacon where your typing speed is your driving speed.