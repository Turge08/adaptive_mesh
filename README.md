This is based on kyleisah's adaptive bed mesh: https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging/blob/main/Configuration/Adaptive_Mesh.cfg

# NOTE: This is currently in beta

Features:
- 2 different methods to specify object coordinates: exclude object or using arguments (PRINT_MIN and PRINT_MAX)
- bed mesh is recreated is bed temp +/- 2 degrees from previous mesh
- Supports Klicky and Euclid probe attaching/docking
- Bed mesh is reused if smaller than previous one
- Supports Voron Stealthburner LED macros

## Usage:

1. Update your print_start macro to supply the PRINT_MIN and PRINT_MAX arguments OR
2. enable [exclude_object]. More info here: https://docs.mainsail.xyz/overview/features/exclude-objects

