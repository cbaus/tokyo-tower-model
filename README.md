# Tokyo Tower Model
Free low-poly Blender model of Tokyo Tower  
Created with Blender 2.8.2

![Tokyo Tower](https://github.com/cbaus/tokyo-tower-model/raw/master/images/tokyo_tower_real.jpg)
<span>Photo by <a href="https://unsplash.com/@thetalkinglens?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Louie Martinez</a> on <a href="https://unsplash.com/?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

## Description
Tokyo Tower is the iconic landmark of Tokyo, a 332.9m high communications and observation tower.  
This model is not very accurate and only loosely based on a picture. Don't expect any beams or steel scaffolding. It simply a few blocks with a UV map (alpha) for the steel beams. On the other hand you can get it for free here under the GPL license. Enjoy.  

This model was created for the [ICEcuBEAR](https://apps.apple.com/jp/app/icecubear/id1533578432?l=en) project.

## Blender model
If you want to edit the file, use the `tokyo_tower.blend` which has a camera and light. If you want to import it somewhere e.g. in unity, use the `_export` files.

<table width="700">
    <tr>
        <td width="30%">
<img src="https://raw.githubusercontent.com/cbaus/tokyo-tower-model/master/images/tokyo_tower_render_1.png" width="200" height="auto" />
        </td>
        <td width="30%">
<img src="https://raw.githubusercontent.com/cbaus/tokyo-tower-model/master/images/tokyo_tower_polygons.png" width="200" height="auto" />
        </td>
        <td width="30%">
<img src="https://raw.githubusercontent.com/cbaus/tokyo-tower-model/master/images/tokyo_tower_render_2.png" width="200" height="auto" />
        </td>
    </tr>
</table>

## Texture
If you do not see the steel texture
 * go to `Shading` workspace
 * click the `Red steel` material on the right under `Material properties`
 * reload the png file for the left-most box `tower_texture.png.001`
 * make sure `Color` of this box is connected to `Fac` of the `Mix Shade` box.
 * repeat for `White steel`
 
The texture was probably exported with an absolute path.
