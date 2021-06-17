//[BGW](../../../index.md)/[tools.aqua.bgw.core](../index.md)/[Scene](index.md)



# Scene  
 [jvm] sealed class [Scene](index.md)<[T](index.md) : [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)>

Superclass for BGW scenes.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.core/Scene///PointingToDeclaration/"></a>width| <a name="tools.aqua.bgw.core/Scene///PointingToDeclaration/"></a><br><br>Scene width in virtual coordinates<br><br>|
| <a name="tools.aqua.bgw.core/Scene///PointingToDeclaration/"></a>height| <a name="tools.aqua.bgw.core/Scene///PointingToDeclaration/"></a><br><br>Scene height in virtual coordinates<br><br>|
  


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.core/Scene/addElements/#kotlin.Array[TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])]/PointingToDeclaration/"></a>[addElements](add-elements.md)| <a name="tools.aqua.bgw.core/Scene/addElements/#kotlin.Array[TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addElements](add-elements.md)(vararg elements: [T](index.md))  <br>More info  <br>Adds all given elements to the root node and rootElements list.  <br><br><br>|
| <a name="tools.aqua.bgw.core/Scene/clearElements/#/PointingToDeclaration/"></a>[clearElements](clear-elements.md)| <a name="tools.aqua.bgw.core/Scene/clearElements/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [clearElements](clear-elements.md)()  <br>More info  <br>Removes all elements from the root node and rootElements list.  <br><br><br>|
| <a name="tools.aqua.bgw.core/Scene/findPathToChild/#tools.aqua.bgw.elements.ElementView/PointingToDeclaration/"></a>[findPathToChild](find-path-to-child.md)| <a name="tools.aqua.bgw.core/Scene/findPathToChild/#tools.aqua.bgw.elements.ElementView/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [findPathToChild](find-path-to-child.md)(elementView: [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)>  <br>More info  <br>Searches node recursively through the visual tree and logs path.  <br><br><br>|
| <a name="tools.aqua.bgw.core/Scene/playAnimation/#tools.aqua.bgw.animation.Animation/PointingToDeclaration/"></a>[playAnimation](play-animation.md)| <a name="tools.aqua.bgw.core/Scene/playAnimation/#tools.aqua.bgw.animation.Animation/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [playAnimation](play-animation.md)(animation: [Animation](../../tools.aqua.bgw.animation/-animation/index.md))  <br>More info  <br>Plays given animation.  <br><br><br>|
| <a name="tools.aqua.bgw.core/Scene/removeElements/#kotlin.Array[TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])]/PointingToDeclaration/"></a>[removeElements](remove-elements.md)| <a name="tools.aqua.bgw.core/Scene/removeElements/#kotlin.Array[TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [removeElements](remove-elements.md)(vararg elements: [T](index.md))  <br>More info  <br>Removes all given elements from the root node and rootElements list.  <br><br><br>|
| <a name="tools.aqua.bgw.core/Scene/zoomOut/#/PointingToDeclaration/"></a>[zoomOut](zoom-out.md)| <a name="tools.aqua.bgw.core/Scene/zoomOut/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [zoomOut](zoom-out.md)()  <br>More info  <br>Zooms scene out to max bounds.  <br><br><br>|
| <a name="tools.aqua.bgw.core/Scene/zoomTo/#tools.aqua.bgw.util.CoordinatePlain/PointingToDeclaration/"></a>[zoomTo](zoom-to.md)| <a name="tools.aqua.bgw.core/Scene/zoomTo/#tools.aqua.bgw.util.CoordinatePlain/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [zoomTo](zoom-to.md)(to: [CoordinatePlain](../../tools.aqua.bgw.util/-coordinate-plain/index.md))  <br>fun [zoomTo](zoom-to.md)(from: [Coordinate](../../tools.aqua.bgw.util/-coordinate/index.md), to: [Coordinate](../../tools.aqua.bgw.util/-coordinate/index.md))  <br>fun [zoomTo](zoom-to.md)(fromX: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), fromY: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), toX: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), toY: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html))  <br>More info  <br>Zooms scene to given bounds.  <br><br><br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.core/Scene/background/#/PointingToDeclaration/"></a>[background](background.md)| <a name="tools.aqua.bgw.core/Scene/background/#/PointingToDeclaration/"></a> [jvm] var [background](background.md): [Visual](../../tools.aqua.bgw.visual/-visual/index.md)The background visual of this scene.   <br>|
| <a name="tools.aqua.bgw.core/Scene/height/#/PointingToDeclaration/"></a>[height](height.md)| <a name="tools.aqua.bgw.core/Scene/height/#/PointingToDeclaration/"></a> [jvm] val [height](height.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)The height of this scene in virtual coordinates.   <br>|
| <a name="tools.aqua.bgw.core/Scene/opacity/#/PointingToDeclaration/"></a>[opacity](opacity.md)| <a name="tools.aqua.bgw.core/Scene/opacity/#/PointingToDeclaration/"></a> [jvm] var [opacity](opacity.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)Opacity of the background of this scene.   <br>|
| <a name="tools.aqua.bgw.core/Scene/rootNode/#/PointingToDeclaration/"></a>[rootNode](root-node.md)| <a name="tools.aqua.bgw.core/Scene/rootNode/#/PointingToDeclaration/"></a> [jvm] val [rootNode](root-node.md): [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)The root node of this Scene.   <br>|
| <a name="tools.aqua.bgw.core/Scene/width/#/PointingToDeclaration/"></a>[width](width.md)| <a name="tools.aqua.bgw.core/Scene/width/#/PointingToDeclaration/"></a> [jvm] val [width](width.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)The width of this scene in virtual coordinates.   <br>|


## Inheritors  
  
|  Name | 
|---|
| <a name="tools.aqua.bgw.core/BoardGameScene///PointingToDeclaration/"></a>[BoardGameScene](../-board-game-scene/index.md)|
| <a name="tools.aqua.bgw.core/MenuScene///PointingToDeclaration/"></a>[MenuScene](../-menu-scene/index.md)|

