//[BGW](../../../index.md)/[tools.aqua.bgw.core](../index.md)/[BoardGameScene](index.md)



# BoardGameScene  
 [jvm] open class [BoardGameScene](index.md)(**width**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **height**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html)) : [Scene](../-scene/index.md)<[ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)> 

Superclass for BGW game scenes. Extends from this class in order to create your own game scene.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.core/BoardGameScene///PointingToDeclaration/"></a>width| <a name="tools.aqua.bgw.core/BoardGameScene///PointingToDeclaration/"></a><br><br>Scene width in virtual coordinates<br><br>|
| <a name="tools.aqua.bgw.core/BoardGameScene///PointingToDeclaration/"></a>height| <a name="tools.aqua.bgw.core/BoardGameScene///PointingToDeclaration/"></a><br><br>Scene height in virtual coordinates<br><br>|
  


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.core/BoardGameScene/BoardGameScene/#kotlin.Number#kotlin.Number/PointingToDeclaration/"></a>[BoardGameScene](-board-game-scene.md)| <a name="tools.aqua.bgw.core/BoardGameScene/BoardGameScene/#kotlin.Number#kotlin.Number/PointingToDeclaration/"></a> [jvm] fun [BoardGameScene](-board-game-scene.md)(width: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = 1920, height: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = 1080)Scene width in virtual coordinates   <br>|


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.core/Scene/addElements/#kotlin.Array[tools.aqua.bgw.elements.ElementView]/PointingToDeclaration/"></a>[addElements](index.md#1316805822%2FFunctions%2F-1902411840)| <a name="tools.aqua.bgw.core/Scene/addElements/#kotlin.Array[tools.aqua.bgw.elements.ElementView]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [addElements](index.md#1316805822%2FFunctions%2F-1902411840)(vararg elements: [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md))  <br>More info  <br>Adds all given elements to the root node and rootElements list.  <br><br><br>|
| <a name="tools.aqua.bgw.core/Scene/clearElements/#/PointingToDeclaration/"></a>[clearElements](../-scene/clear-elements.md)| <a name="tools.aqua.bgw.core/Scene/clearElements/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [clearElements](../-scene/clear-elements.md)()  <br>More info  <br>Removes all elements from the root node and rootElements list.  <br><br><br>|
| <a name="tools.aqua.bgw.core/Scene/findPathToChild/#tools.aqua.bgw.elements.ElementView/PointingToDeclaration/"></a>[findPathToChild](../-scene/find-path-to-child.md)| <a name="tools.aqua.bgw.core/Scene/findPathToChild/#tools.aqua.bgw.elements.ElementView/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [findPathToChild](../-scene/find-path-to-child.md)(elementView: [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)>  <br>More info  <br>Searches node recursively through the visual tree and logs path.  <br><br><br>|
| <a name="tools.aqua.bgw.core/BoardGameScene/lock/#/PointingToDeclaration/"></a>[lock](lock.md)| <a name="tools.aqua.bgw.core/BoardGameScene/lock/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [lock](lock.md)()  <br>More info  <br>Locks scene from any user input.  <br><br><br>|
| <a name="tools.aqua.bgw.core/Scene/playAnimation/#tools.aqua.bgw.animation.Animation/PointingToDeclaration/"></a>[playAnimation](../-scene/play-animation.md)| <a name="tools.aqua.bgw.core/Scene/playAnimation/#tools.aqua.bgw.animation.Animation/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [playAnimation](../-scene/play-animation.md)(animation: [Animation](../../tools.aqua.bgw.animation/-animation/index.md))  <br>More info  <br>Plays given animation.  <br><br><br>|
| <a name="tools.aqua.bgw.core/Scene/removeElements/#kotlin.Array[tools.aqua.bgw.elements.ElementView]/PointingToDeclaration/"></a>[removeElements](index.md#-1423518191%2FFunctions%2F-1902411840)| <a name="tools.aqua.bgw.core/Scene/removeElements/#kotlin.Array[tools.aqua.bgw.elements.ElementView]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [removeElements](index.md#-1423518191%2FFunctions%2F-1902411840)(vararg elements: [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md))  <br>More info  <br>Removes all given elements from the root node and rootElements list.  <br><br><br>|
| <a name="tools.aqua.bgw.core/BoardGameScene/unlock/#/PointingToDeclaration/"></a>[unlock](unlock.md)| <a name="tools.aqua.bgw.core/BoardGameScene/unlock/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [unlock](unlock.md)()  <br>More info  <br>Unlocks scene for user input.  <br><br><br>|
| <a name="tools.aqua.bgw.core/Scene/zoomOut/#/PointingToDeclaration/"></a>[zoomOut](../-scene/zoom-out.md)| <a name="tools.aqua.bgw.core/Scene/zoomOut/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [zoomOut](../-scene/zoom-out.md)()  <br>More info  <br>Zooms scene out to max bounds.  <br><br><br>|
| <a name="tools.aqua.bgw.core/Scene/zoomTo/#tools.aqua.bgw.util.CoordinatePlain/PointingToDeclaration/"></a>[zoomTo](../-scene/zoom-to.md)| <a name="tools.aqua.bgw.core/Scene/zoomTo/#tools.aqua.bgw.util.CoordinatePlain/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [zoomTo](../-scene/zoom-to.md)(to: [CoordinatePlain](../../tools.aqua.bgw.util/-coordinate-plain/index.md))  <br>fun [zoomTo](../-scene/zoom-to.md)(from: [Coordinate](../../tools.aqua.bgw.util/-coordinate/index.md), to: [Coordinate](../../tools.aqua.bgw.util/-coordinate/index.md))  <br>fun [zoomTo](../-scene/zoom-to.md)(fromX: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), fromY: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), toX: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), toY: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html))  <br>More info  <br>Zooms scene to given bounds.  <br><br><br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.core/BoardGameScene/background/#/PointingToDeclaration/"></a>[background](index.md#143687209%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.core/BoardGameScene/background/#/PointingToDeclaration/"></a> [jvm] var [background](index.md#143687209%2FProperties%2F-1902411840): [Visual](../../tools.aqua.bgw.visual/-visual/index.md)The background visual of this scene.   <br>|
| <a name="tools.aqua.bgw.core/BoardGameScene/height/#/PointingToDeclaration/"></a>[height](index.md#-500663984%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.core/BoardGameScene/height/#/PointingToDeclaration/"></a> [jvm] val [height](index.md#-500663984%2FProperties%2F-1902411840): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)The height of this scene in virtual coordinates.   <br>|
| <a name="tools.aqua.bgw.core/BoardGameScene/opacity/#/PointingToDeclaration/"></a>[opacity](index.md#-1328006024%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.core/BoardGameScene/opacity/#/PointingToDeclaration/"></a> [jvm] var [opacity](index.md#-1328006024%2FProperties%2F-1902411840): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)Opacity of the background of this scene.   <br>|
| <a name="tools.aqua.bgw.core/BoardGameScene/rootNode/#/PointingToDeclaration/"></a>[rootNode](index.md#201890963%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.core/BoardGameScene/rootNode/#/PointingToDeclaration/"></a> [jvm] val [rootNode](index.md#201890963%2FProperties%2F-1902411840): [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)The root node of this Scene.   <br>|
| <a name="tools.aqua.bgw.core/BoardGameScene/width/#/PointingToDeclaration/"></a>[width](index.md#-392183651%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.core/BoardGameScene/width/#/PointingToDeclaration/"></a> [jvm] val [width](index.md#-392183651%2FProperties%2F-1902411840): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)The width of this scene in virtual coordinates.   <br>|

