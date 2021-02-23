# Year 2 Semester-2 Learning Journal

## Tuesday 16th February 2021

I had a small problem with making the minimap camera show the plane in the scene, even though I did exactly what the video showed how to do it. I thought it was because of the size of it as I haven't made a minimap camera in a while and I never experienced this issue before, but after resizing it, I realised it was the size of the camera as it showed the character I wanted moving around the scene.

I also had some confusions with writing the movement script for the character, which is mostly because I have never done it without the character controller and I never tied to do it like I did in the 2D games I made. I realised that the reason why I was struggling to write the movement for the 3D character was because I never wrote wrote the movements without using the Character Controller Component and I thought I could succeed without it.

When writing the script that would allow the script to manage the minimap camera's ability to rotate along with the character, I encountered an error with how it worked. It only worked on the same script and would not work if it is part of a different script. I do not know what I did wrong with the script, but I think it might have something to do with how I called the functions from the other scripts as I might have written it wrong and got confused on how I did it for my other assignments that involved using code.

## Tuesday 23rd February 2021

I encountered a problem with why when the pistol runs out of ammo, it stays in the reload position instead of returning to its idle position for the AmmoManagement Package. I thought it was because I missed something in the videos I watched, and it turned out that I did miss something: I had to set the booleon for pistol the animation back to false to return to the idle position because if I did not, it would stay at the idle position and never change after the reload animation is set to true.

As I progressed through the AmmoManagement Script, I got confused as to how I could re-write the script I wrote after watching the first video to work similarly to the script in the other video I watched as they did not contain all of the same variables to each other. I knew that if I wanted to give it a certain amount of ammo before running out and never be able to fire again, I needed to add more variables, but I did not know how to make sure that when the weapon reloads, the max ammo did not turn into a negative number.

I thought this is because I had to re-write the other bits of script that had nothing to do with the general firing commands, but I figured out that I did not need to touch the firing functions, I just had to re-write the ammo variables and add more to them. I planned on writting it after watching the second video, but later I decided to leave it and write it in the documentation instead as I already got the basic part of it done, I did not include any movement scripts to it and I did not feel that it was needed as it's mainly about shooting and reloading.
