Simple evolution simulation framework for organelles/molecular structures based on a theoretical silicon based primordial soup and it's probable most common reaction products. Building in complexity one step at a time, and tracking for assignment. 

The reactivity values will next be improved by defining higher-order complexity as molecules build on one another, which would require a more detailed approach to simulate how molecules evolve.

The reactivity values are currently abritrary, but can be understood in the context of real-world chemical reactivity:

    Oxygen (O2) and Hydrogen (H2) have a high reactivity because they are often involved in many chemical reactions, particularly with other elements like silicon and carbon (forming molecules like water, silica, and hydrocarbons).
    Silicon is given a high reactivity as well because it forms bonds readily, especially in an environment conducive to silicon-based life.
    Carbon has a lower reactivity in this model, although it’s highly reactive in biological systems. In this context, the value of 0.7 could indicate its relative rarity or how it may not immediately react with other molecules unless driven by a specific condition (such as higher temperature or energy).
    
The time step (self.time_step) represents how many cycles the simulation has gone through. In this case, it increments by 1 each time the evolve_molecules() method is called. It helps visualize the progression of the simulation.

This portion will be improved by using dynamic variables instead of a fixed 1 time step per simulation cycle, based on reaction rates, soup composition or temperature. For example, if the temperature is higher, reactions might occur more quickly, reducing the time between steps.

Most weights are currently placeholders.
