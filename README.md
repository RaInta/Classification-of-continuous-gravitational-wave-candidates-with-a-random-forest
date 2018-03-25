# Classification-of-continuous-gravitational-wave-candidates-with-a-random-forest
Classification of continuous gravitational wave candidates with a random forest
---

<img src="./Figures/GR_warpedSpaceTime.jpg" width=640>

If you've been paying attention to science news over the last year or two, you'd notice that [gravitational waves](https://en.wikipedia.org/wiki/Gravitational_wave) have revolutionized how we see (or 'hear') the Universe. Looking into data from the [LIGO](www.ligo.org) gravitational-wave observatories, we have seen the largest stellar-mass black holes spiral into each other, causing the very fabric of space-time itself to reverberate. We've seen neutron stars collide, in turn illuminating where Earth got all its heavy metals—including gold and platinum.

However, we have yet to see gravitational waves from spinning neutron stars. I search within LIGO data for the faint hum that may be given off by neutron stars in the ashes of 'recent' star explosions ([supernovae](https://en.wikipedia.org/wiki/Supernova)). Here is a roadmap of the supernova remnants searched for in our Galaxy (the Sun is the yellow dot):


<img src="./Figures/PostCasA_SNR_positions_greenText2.jpg" width=640>
---

## What's the problem?

These searches are very expensive (each target took almost half a million CPU hours on a modern computing cluster). They generate a _lot_ of potential candidates. Currently, these have to be checked manually, by hand, to rule out if they are the result of something physically plausible, or are merely artifacts of the instruments (which we expect most of them to be). This is a problem ripe for an attack from Machine Learning!

We will apply a Random Forest classifier to classify potential candidates as detections ('signal'), instrumental lines ('line') or merely noise ('noise').




<img src=".Figures/RndForestOverview_neg.png" width=640>

<img src=".Figures/Candidate1_2F_freq.png" width=640>
<img src=".Figures/Candidate2_2F_freq.png" width=640>
<img src=".Figures/Candidate5_2F_freq.png" width=640>
<img src=".Figures/cleaned_candidate_histogram_18000.png" width=640>
<img src=".Figures/ksStat_36301.png" width=640>
<img src=".Figures/ksStat_P2_0.png" width=640>
<img src=".Figures/RaTTUSelfie_Escher.png" width=640>
<img src=".Figures/RndForestOverview.png" width=640>
<img src=".Figures/vetoed_line_VelaJr_10.png" width=640>
