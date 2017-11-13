# Markov Me

My state space and transition probabilities according to an analysis of 3 years
of my Google location and activity data.

Arrows represent my probability of remaining in the same state or transitioning
to another state within 5 minutes.

View the live demo: [ndawe.github.io/markov](https://ndawe.github.io/markov)

I selected the activity assigned the highest confidence for each event before
histogramming all state transitions within 5 minute intervals. Multiple
candidate activities often have confidence values that are very close. For
example, I see that riding a bike is easily confused with being in a
vehicle (must be my smooth pedal stroke ;)).

![](demo.png)

Disclaimer: I don't actually satisfy the Markov property.

Visualization created by adapting code written by [Setosa.io](http://setosa.io)
