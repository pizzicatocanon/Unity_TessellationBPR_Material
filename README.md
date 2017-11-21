# Unity_TessellationBPR_Material

```
Megascans Tessellation Shader

With the release of Megascans we bring you a custom shader written to support the exported data from Megascans Bridge.

This shader is intended for cinematics and visualisations, it has not been optimised for gaming and is compatible with DirectX11 only.


Installation:

	1. In your asset store manager, import the "Quixel Megascans Tessellation Shader" asset.
	2. On your object's material, select the Third Dimension Studios/MegascansSurface shader from the shader drop down list
	3. Assign the relevant image maps that were output from Megascans Bridge (using the Unity export preset) to the labelled slots on the Shader.


Customisation:

The shader can be customised to achieve the desired effect, here are the options you have available:

	- Colour: is mixed with your albedo map to change the hue and brightness of your image
	- Metallic: Megascans doesn't output this map currently, so we've provided a slider to allow you to adjust how metallic your material looks.
	- Displacement Amount: How raised / lowered the detail is.
	- Tessellation Amount: How fine the tessellation is - higher numbers = lower performance but more detail.
	- AO Intensity: Increases / Decreases the Ambient Occlusion Intensity of your Ambient Occlusion map
	- Tile Amount: Tiles the texture the specified amount. This also scales the displacement so you can make quick adjustments. Increasing this means you might have to manually increase the tessellation value which doesn't auto scale.


Video Tutorial is available here: https://www.youtube.com/watch?v=z9Pw1gtiNb0	


Get Megascans: https://megascans.se/
Visit Our Website: http://thirddimensionstudios.co.uk

Please note that we are a third party and are in no way associated with Quixel.

Shader was created using Shader Forge (which is not necessary to use this asset). Shader Forge can be found here: https://www.assetstore.unity3d.com/en/#!/content/14147
```
