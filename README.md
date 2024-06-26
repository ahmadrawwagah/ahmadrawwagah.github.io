# COMS3930-Portfolio

Hi, This is my portfolio for Creative Embedded Systems!! Below you can find some of the projects I have completed as a part of that course.


# ESP32 Valentines Art Installation
I created an art installation that consisted of an ESP32 in an envelope hanging from the ceiling

# Artistic Vision
I knew I wanted to theme my installation around Valentine's Day as we would be displaying our projects the day before Valentine's.
I decided that I would center my design on a quote I had seen online which reads "To be loved is to be changed" ~ some Twitter user.
I like this quote a lot and It fits with the theme of Valentine's. I wanted to have the text scroll past on the screen so I found
an example that does that. I also edited it to make it generative by adding a lot of randomness to the displayed text. The color
was chosen at random and the position was chosen at random. I also added a 30% chance that the text wouldn't be displayed and instead,
a stream of hearts would appear with random color and position as well. I also purposefully allowed for the text to appear on top of 
each other as I liked how chaotic it looked on the screen after it had been running for a while. The screen eventually resets itself
which ensures the text stays readable the entire time.
# Challenges
Some of the challenges I faced while making this project were the limited battery capacity and the open-ended nature of the assignment.
The limited battery size meant I needed to come up with a way to limit my power draw. I did this by dimming the backlight every 5 mins.
I also struggled to find inspiration for what to do for my project. I only came up with the idea while I was scrolling on Twitter and 
saw the quote.
# Video
[Here](https://youtube.com/shorts/sWXqJz0Kr38?feature=share) This Is a video I took of my project. You can see the text scrolling by with different colors and overlapping each other.


# Code
[Here](https://github.com/ahmadrawwagah/Ahmad_Scroll/tree/master) is the link to my code and technical documentation.

# ESPotify
I created a device that allows me to adjust my Spotify settings without touching my computer.

# Artistic Vision
I am very fond of old stereo and hi-fi equipment. I love using the tactile switches and dials to adjust settings. I am also fond of convenience which causes me to listen to Spotify more than my records and other physical media. The vision of this project was to combine both the tactile nature of stereo equipment with the convenience of Spotify. I did this by making physical ways to interact with Spotify. Ideally, this project would have been housed in something that would fit visually with the rest of my stereo equipment.

# Challenges
I faced many challenges while creating this project. I initially struggled to get the button wired up correctly. I ended up solving this problem by isolating the individual problems with the wiring by first figuring out how to wire the button for data and then wiring it for lights as well. I then had to figure out how to interact with Spotify and I subsequently found the spotiPY api. I faced challenges when it came to reading data from the potentiometer and the button at the same time. I partially solved this by adding a delay which helped with the potentiometer, but it also made the button flaky. Also, there is a delay between adjusting the volume or skipping the track because the API call to Spotify is a bit slow depending on the speed of the internet that the computer is connected to.
# Video
[Here](https://youtube.com/shorts/TaB9tKiJ_rI?feature=share) This Is a video I took of my project. You can see the volume changing as I turn the knob and the track skipping when I press the button.

# Code
[Here](https://github.com/ahmadrawwagah/Module-2/tree/main) is the link to my code and technical documentation.
