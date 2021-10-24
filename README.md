# labpbr-substance-tools
A set of Substance Designer nodes which aid the creation of Minecraft textures

## labpbr-publish
Converts metal-rough materials to LabPBR, and provides some features such as height fading.
### Features:
- EVERY option has helpful tooltips explaining what it does, and how to use certain channels
- Automatic organisation of material channels based on LabPBR 1.3 standard
- A robust and highly customisable height fade feature, which can help to reduce artifacts from parallax occlusion mapping
- Presets for common dielectric f0 values as well as LabPBR hardcoded metals
- Multiple options for blending material f0 values based on a metalness map
- Automatically remaps porosity, subsurface scattering and emissive maps to LabPBR ranges
- Multiple options for opacity handling, including thresholding and dilation

## biome_tint
Adjusts the colours of an image to compensate for Minecraft's temperature-based biome tint. Choose from built-in vanilla colormaps or use a custom one.

## labpbr_f0_presets
Super simple drop down list of commonly used f0 values.
