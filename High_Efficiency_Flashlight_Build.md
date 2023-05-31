I have always been facsinated by flashlights. I think my love for them comes from my love of horror stories and games. This project was originally inspired by my search for a commerically available flashlight that had high efficiency, both to maximize runtime and with the hope of using it with a different project of mine, a kinetically charge battery. I was searching various flashlight forums for recommednations when I stumbled upon a forum chain theorycrafting what features would maximize efficiency. However, since no flashlight exists following those design princinples I decided to try building one myself.  
  
So what actually makes an efficient flashlight?  
Broadly speaking, a flashlight can be split into two main sections:  
First is the "light emitting" part, this includes both the optics as well as the emitters (the parts the make light)
Second is the "driver", which controls both the power supply circuit as well as any control circuitry.  
These two parts make up the majority of the power using/wasting parts of a flashlight, and so optimizing efficiency for the system basically means optimizing each of their efficiencies.  
  
Optimizing the Bright Part
The basis of this design comes from the non-linear efficiency curve of LEDs. In short, LEDs are more efficient the lower current you drive them at. Since the light emitted is also a function of current, the less light an LED generates, the less power it uses to generate that light. So instead of having one LED generating a large amount of light, the load is split between multiple LEDs, meaning each of them individually generates a smaller amount of light. This results in the same amount of light in the end, but with less power wasted.
