I have always been facsinated by flashlights. I think my love for them comes from my love of horror stories and games. This project was originally inspired by my search for a commerically available flashlight that had high efficiency, both to maximize runtime and with the hope of using it with a different project of mine, a kinetically charge battery. I was searching various flashlight forums for recommednations when I stumbled upon a forum chain theorycrafting what features would maximize efficiency. However, since no flashlight exists following those design princinples I decided to try building one myself.  
  
So what actually makes an efficient flashlight?  
Broadly speaking, a flashlight can be split into two main sections:  
First is the "light emitting" part, this includes both the optics as well as the emitters (the parts the make light)
Second is the "driver", which controls both the power supply circuit as well as any control circuitry.  
These two parts make up the majority of the power using/wasting parts of a flashlight, and so optimizing efficiency for the system basically means optimizing each of their efficiencies.  
  
Optimizing the Bright Part  
The basis of this design comes from the non-linear efficiency curve of LEDs. In short, LEDs are more efficient the lower current you drive them at. Since the light emitted is also a function of current, the less light an LED generates, the less power it uses to generate that light. So instead of having one LED generating a large amount of light, the load is split between multiple LEDs, meaning each of them individually generates a smaller amount of light. This results in the same amount of light in the end, but with less power wasted.  
This method does have its downsides:  
1. Spread  
    Since the light 
3. 










































So, probably too late in the building process, around when the circuit design was almost finished, I realized I should probably look into different LED to see if any other LEDs with high efficiency existed. It was possible that the original forum post was wrong or outdated, and the Luxeon V while highly efficient and a great emitter might have been beaten by some recent, unknown LED. And so after a bit of searching I found this blog post from Ledrise posted in 2020. Two things stood out to me immeadately. First, the Luxeon brand (which I assumed was referring to the Luxeon V) was not the most efficient LED available (though it still was 2nd place). This meant I'd probably have to recheck and change my design right as it was finished, which was a big error on my part, though the main circuit parts should still work for this other emitter, the __. -The second thing though was that the Luxeon brand peak efficienc-
