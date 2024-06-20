# Devlog - Wen

### Current Version
[WC_Ambient_Debug2.maxpat](/MaxPatch/)

- Made for PS3 controller (it had a start button and gyro)
- Takes in voice input (I used contact mics) 
- Everything can be controlled by the controller, you don't have to touch your laptop 
- Uses mainly FM8 and samples 


### Things I'm proud of:
- Got performance feedback that it sounded like deep sea ocean 
- Playing it is fun for me, intuitive for performing  
- Interpolated values work well with chosen parameters 
- Reliable, not sudden in any changes because of the line~ object, thank you to Amogh for that 
- The presentation mode looks really pretty :) 

### Things to improve:
- The left arrow keys toggle on long droning samples, I wonder if there is a more elegant way of doing that instead of
having to click 3 more times to properly toggle it off, sending a bang didn't work. I need some visual feedback which drone is playing,
what is the best way to do that?
- I want to move away from FM8 and just create my own sounds, that is more achievable now that I have explored procedural audio!
- I have the new PS5 now (exciting!), I am wondering what more features I can add, with the touch pad
- I want to work more with the gyroscope, currently it is on with panning tilt left and right, would love to play with filters  
- The panning favours right side I believe, what's a better calculation to split it to the left? 

