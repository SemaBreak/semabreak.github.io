+++ 
title = "Qubes Os Adventures"
date = "2026-11-25" 
tags = [ 
	"qubesos",
       ] 
+++

I must confess, as much as I would like to say I chose QubesOS for its security features, that would be a lie.
I love putting things into boxes and this seems like the perfect opportunity to do so. I tried to do something similar to QubesOS
but with vanilla VMs, but the lack of proper integration with the broader OS made it so much more of a headache than it needed to be.

So, I decided to give QubesOS a shot, now that in the year of RAMagaddon I have gotten a laptop with 32GB of RAM, I could probably run QubesOS comfortably. So armed with some excitement, I installed it on my laptop and started to use it daily.

## What I Liked:

* Spinning up VMs in a blink of an eye, with specific use cases in mind. 
* Trying to wrap my head around the various design decisions the developers made was a challenge I enjoyed.

## What I Disliked:
* Software. Template VMs (the root for the single purpose VMs) have no internet connection, outside the proxy for the package manager, I spent many hours trying to figure out how to install the Pi coding agent on it, since I wanted to create an agent template. It eventually worked, but it needed more tinkering than I wanted for a simple command line install.
* Performance. While not horrendous, I tried to connect to a zoom meeting from inside a disposable Qube, and constant dropped frames made the conversation barely possible (though to my suprise, passing the mic and camera to the VM was easy and simple).

Overall, I emjoyed my time on QubesOS, but because of the edge cases where a VM was more of a headache than a help, I decided to move off it to an arch based distro, and gave up on the dream of having my operating systems in neat little boxes.

I am still looking at containers and NixOS as an alternative (at least for my server).
