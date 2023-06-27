# active-walkers
Continuation of the Active Walkers/Ant Simulator project that I did for a university project; legacy code can be found in jacob-toller/mathematical-modelling-4

## Why a new repo?
I wanted to keep the new progress separate from the legacy code; and with a new repo name. Also GitHub doesn't allow for forking of your own repositories.

## Whats the plan moving forward?

Plan is to rewrite all the bits of the project that I wanted to do while I was working on the project at uni, but didn't have the time to due to the deadline. This will be in a more modular way compared to the current jupyter notebook.
1. Renderer - Want to make this part simply take in the system state, and drawing parameters; and draw the state from that with it being otherwise disconnected from the rest of the project. This would mean it could not only render the system as it is running, but also allow for the system states to be saved and then re-drawn at a later time.
2. 'game loop' - To work with the new renderer system, this should be able to compile the system state when the current tick has finished processing for the renderer and to be saved. This will also include stuff that is currently saved such as runtime and scenario statistics

