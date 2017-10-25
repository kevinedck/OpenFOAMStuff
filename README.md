# OpenFOAM_extensions
A personal collection of custom solvers, utitilies and other extensions for OpenFOAM

## Content

### wallShearStress_improved
* **Compatible with:** OpenFOAM 4.0.x
* **Backward compatible:** no

OpenFOAMs *wallShearStress* functionObject also includes the normal stress in the computation of wall shear stress. This extension removes the normal stress from the stress tensor.
