# SPHEREx Blink

**https://spherex-blink.github.io/**

Pick any point in the sky and blink NASA's SPHEREx infrared images of it, so moving objects (nearby stars, brown dwarfs, maybe a
"Planet X") and varying stars stand out. Built for the NASA Space Apps Challenge 2026, challenge "Planet X and SPHEREx",
by team Halal Haemek (Haifa).

How it works:
- **A static sky index** (built by this repo's workflow) records which of the ~1.6 million SPHEREx images cover each point of the sky.
- **The browser reads only the pixels it needs** straight from NASA's public SPHEREx archive on AWS (`nasa-irsa-spherex`).
- **The index refreshes daily**, so new SPHEREx data appears automatically.

This repository only publishes the site. **Source code, docs and the 30-second demo video: https://github.com/spherex-blink/spherex-blink**

Data: SPHEREx spectral images from NASA/IPAC IRSA. SPHEREx is a joint project of the Jet Propulsion Laboratory and the
California Institute of Technology, funded by NASA. Built with the help of Claude Code (AI-assisted development).
