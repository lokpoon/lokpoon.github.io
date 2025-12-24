---
layout: archive
title: ""
permalink: /software/
author_profile: true
redirect_from:
  - /software
---

# <span style="font-variant:small-caps;">MoonShine</span>
![moonshine](../images/moonshine_logo.png "moonshine"){: width="300" }
<br/><br/> 
- [<span style="font-variant:small-caps;">MoonShine</span> GitHub Repository](https://github.com/Crampton-Lab/MoonShine)
- [<span style="font-variant:small-caps;">MoonShine</span> Instruction Manual](https://lokpoon.github.io/MoonShine_manual/overview.html)

To address the lack of open-source solutions for predicting, re-creating, and manipulating moonlight cycles, I developed the software-hardware system <span style="font-variant:small-caps;">MoonShine</span>.

<span style="font-variant:small-caps;">MoonShine</span> allows researchers to re-create a range of natural nocturnal lighting scenarios in the laboratory. It can re-create natural moonlight cycles with a relatively realistic spectral composition, generate manipulated moonlight schedules, or simulate light pollution.
<br/><br/> 
<span style="font-variant:small-caps;">MoonShine</span> includes multiple features for re-creating and manipulating light cycles. It supports color shifting of the LEDs (by adjusting RGBW intensity ratios) to approximate the spectrum of natural moonlight, and to mimic habitat-specific conditions or certain types of light pollution.
<br/><br/> 
Furthermore, the moonlight illuminance predicted by <span style="font-variant:small-caps;">MoonShineR</span> is useful for field ecologists who use moonlight as a quantitative predictor. Finally, to provide laboratory-housed animals with full diurnal light cycles, <span style="font-variant:small-caps;">MoonShine</span> allows researchers to re-create natural twilight and sunlight regimes.

## <span style="font-variant:small-caps;">MoonShineR</span>
An R package that predicts ground-level moonlight illuminance (lux) at defined intervals for a specified location and time range. It can also predict sunlight and twilight. It warns the user of lunar eclipses during the prediction period.
<br/><br/> 
![moonshine](../images/moonshineR_example.jpg "moonshine"){: width="1000" }
## <span style="font-variant:small-caps;">MoonShineP</span>
<span style="font-variant:small-caps;">MoonShineP</span>, a Python program running on a Raspberry Pi, uses illuminance values from <span style="font-variant:small-caps;">MoonShineR</span> to gradually dim and brighten a diffused array of individually addressable LEDs, allowing realistic natural light regimes to be re- created in a laboratory environment.
<br/><br/> 
![moonshine](../images/moonshineP_diagram.jpg "moonshine"){: width="600" }

