# Time-Fly

This shows the paths taken throughout the course of the entire simulation by particles in the CGM of a Milky-Way progenitor  at z=0.25. The specific simulation is a zoom-in galaxy formation simulation (named [Latte](https://arxiv.org/abs/1602.05957)) created as part of the [FIRE project](https://fire.northwestern.edu).

There are four origins for material in the CGM at z=0.25:

1. IGM Accretion (blue) - material that has either never been inside a galaxy or inside a galaxy a short time.
2. Wind (green) - material that was in the central galaxy previously
3. Satellite ISM (red) - material that is in a galaxy other than the central galaxy at z=0.25.
4. Satellite Wind (orange) - material that is no longer in a satellite galaxy, but was previously.

Further details can be found in Hafen et al., in prep.

All distances are in proper kpc relative to the central galaxy, and a ruler (100 kpc on a side with 1 kpc spacing between points) is shown in white. The position of stars at z=0.25 are shown in yellow. Clicking on the downward arrow next to a classification allows one to filter the data according to a variety of options.

We show the worldlines of 50 particles per origin, sampled randomly. Fewer worldlines can be displayed using the ParticleID option when filtering.

[The original Firefly is found here.](https://github.com/ageller/Firefly)
