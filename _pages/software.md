---
layout: archive
title: ""
permalink: /software/
author_profile: true
redirect_from:
  - /software
---

# <span style="font-variant:small-caps;">MoonShine</span>
![moonshine](../images/moonshine_logo.png "moonshine"){: width="250" }
- To address the lack of open-source solutions for re-creating and manipulating moonlight cycles, we developed the software-hardware system <span style="font-variant:small-caps;">MoonShine</span>. This has two components:

### <span style="font-variant:small-caps;">MoonShineR</span>
- An R package with additional R scripts, predicts moonlight ground illuminance (in lux) at defined intervals, for a specified location and time range.
![moonshine](../images/moonshineR_example.jpg "moonshine"){: width="1000" }
### <span style="font-variant:small-caps;">MoonShineP</span>
- <span style="font-variant:small-caps;">MoonShineP</span>, a Python program running on a Raspberry Pi computer, uses the illuminance values from <span style="font-variant:small-caps;">MoonShineR</span> to gradually dim and brighten a diffused array of individually addressable LEDs, allowing realistic natural light regimes to be re- created in a laboratory environment.
![moonshine](../images/moonshineP_diagram.jpg "moonshine"){: width="600" }
## Usages
- <span style="font-variant:small-caps;">MoonShine</span> allows researchers to re-create a range of natural nocturnal lighting scenarios in the laboratory. It can be used to re-create full natural moonlight cycles with a relatively realistic spectral composition, generate manipulated moonlight schedules, or simulate light pollution. Furthermore, the moonlight illuminance predicted by <span style="font-variant:small-caps;">MoonShineR</span> is useful for field ecologists who require moonlight as a quantitative model predictor. Finally, to provide laboratory-housed animals with full diurnal light cycles, <span style="font-variant:small-caps;">MoonShine</span> allows researchers to re-create (in a simplified manner) natural twilight and sunlight regimes.
- <span style="font-variant:small-caps;">MoonShine</span> includes multiple features to re-create and manipulate light cycles. It supports color-shifting of the LED light (by adjustment of RGBW intensity ratios) to approximate the spectrum of natural moonlight, and to mimic habitat-specific conditions or certain types of light pollution.

## Resources
- [<span style="font-variant:small-caps;">MoonShine</span> GitHub Repository](https://github.com/Crampton-Lab/MoonShine)
- [<span style="font-variant:small-caps;">MoonShine</span> Instruction Manual](https://lokpoon.github.io/MoonShine_manual/overview.html)
