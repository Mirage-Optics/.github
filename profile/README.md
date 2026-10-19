# MIRAGE

**GPU-accelerated simulation tools for coupled optics.** Developed by the Mechanics of Materials Research group at Eindhoven University of Technology (TU/e).

Standard ray tracers are not built to couple natively with multi-physics finite element solvers. Mirage is designed to do exactly that.

## The suite

- **[Mirage Optics](https://pypi.org/project/mirage-optics-engine)** [![PyPI Downloads](https://img.shields.io/pepy/dt/mirage-optics-engine?color=457A4B&labelColor=black&label=downloads)](https://pepy.tech/projects/mirage-optics-engine): GPU-accelerated finite element ray tracer for light transport and absorption in gradient-index and gradient-absorptivity media. Install with `pip install mirage-optics-engine`.
- **Mirage DLP**: vat photopolymerization for digital light processing, coupling ray-traced nonlinear optics with a reaction-diffusion model.
- **Mirage TVAM**: vat photopolymerization for tomographic volumetric additive manufacturing, coupling ray-traced nonlinear optics with a linear curing model. Release follows publication.
- **[DMD projection ray generator](https://github.com/Mirage-Optics/DMDprojector-raydiscretizer)**: TOML-driven generator of DMD projections in Mirage's `.ry` ray format. Standalone or as a submodule.

## Publications

- Mirage Optics: [doi:10.1364/OE.582633](https://doi.org/10.1364/OE.582633)
- Mirage DLP: [doi:10.1117/12.3100381](https://doi.org/10.1117/12.3100381)
- Mirage TVAM: M. Aarab et al., *Numerical study of light self-focusing-induced striations in tomographic volumetric additive manufacturing* (under review; data in [mirage-striations-in-tvam-tutorial](https://github.com/Mirage-Optics/mirage-striations-in-tvam-tutorial))

## Credits

The current codebase was developed by **Marwan Aarab** ([@m-aarab](https://github.com/m-aarab)) in the **Mechanics of Materials** research group at TU/e, under the supervision of **J.J.C. Remmers** ([@jjcremmers](https://github.com/jjcremmers)) and **M.G.D. Geers**. Their supervision focused on the numerical methods; the code itself was not reviewed by them, and responsibility for the implementation lies with the author.
