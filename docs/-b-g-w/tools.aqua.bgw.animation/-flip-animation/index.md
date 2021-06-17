//[BGW](../../../index.md)/[tools.aqua.bgw.animation](../index.md)/[FlipAnimation](index.md)



# FlipAnimation  
 [jvm] class [FlipAnimation](index.md)<[T](index.md) : [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)>(**elementView**: [T](index.md), **fromVisual**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **toVisual**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **duration**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [ElementAnimation](../-element-animation/index.md)<[T](index.md)> 

A flip animation. Sets background to given fromVisual than Contracts background in half the given duration. Then switches to new visual and extends again in half the given duration.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/FlipAnimation///PointingToDeclaration/"></a>elementView| <a name="tools.aqua.bgw.animation/FlipAnimation///PointingToDeclaration/"></a><br><br>ElementView to animate<br><br>|
| <a name="tools.aqua.bgw.animation/FlipAnimation///PointingToDeclaration/"></a>fromVisual| <a name="tools.aqua.bgw.animation/FlipAnimation///PointingToDeclaration/"></a><br><br>Initial visual<br><br>|
| <a name="tools.aqua.bgw.animation/FlipAnimation///PointingToDeclaration/"></a>toVisual| <a name="tools.aqua.bgw.animation/FlipAnimation///PointingToDeclaration/"></a><br><br>Resulting visual<br><br>|
| <a name="tools.aqua.bgw.animation/FlipAnimation///PointingToDeclaration/"></a>duration| <a name="tools.aqua.bgw.animation/FlipAnimation///PointingToDeclaration/"></a><br><br>Animation duration in milliseconds. Default: 1 second<br><br>|
  


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/FlipAnimation/FlipAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a>[FlipAnimation](-flip-animation.md)| <a name="tools.aqua.bgw.animation/FlipAnimation/FlipAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Int#kotlin.Int#kotlin.Int/PointingToDeclaration/"></a> [jvm] fun <[T](index.md) : [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)> [FlipAnimation](-flip-animation.md)(elementView: [T](index.md), fromVisual: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), toVisual: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), duration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 500)ElementView to animate   <br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.animation/FlipAnimation/duration/#/PointingToDeclaration/"></a>[duration](index.md#-1051227989%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/FlipAnimation/duration/#/PointingToDeclaration/"></a> [jvm] var [duration](index.md#-1051227989%2FProperties%2F-1902411840): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)Animation duration in milliseconds.   <br>|
| <a name="tools.aqua.bgw.animation/FlipAnimation/element/#/PointingToDeclaration/"></a>[element](index.md#1732185087%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/FlipAnimation/element/#/PointingToDeclaration/"></a> [jvm] val [element](index.md#1732185087%2FProperties%2F-1902411840): [T](index.md)ElementView to animate   <br>|
| <a name="tools.aqua.bgw.animation/FlipAnimation/fromVisual/#/PointingToDeclaration/"></a>[fromVisual](from-visual.md)| <a name="tools.aqua.bgw.animation/FlipAnimation/fromVisual/#/PointingToDeclaration/"></a> [jvm] var [fromVisual](from-visual.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)Initial visual   <br>|
| <a name="tools.aqua.bgw.animation/FlipAnimation/onFinished/#/PointingToDeclaration/"></a>[onFinished](index.md#429284590%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/FlipAnimation/onFinished/#/PointingToDeclaration/"></a> [jvm] var [onFinished](index.md#429284590%2FProperties%2F-1902411840): [EventHandler](../../tools.aqua.bgw.event/-event-handler/index.md)<[Event](../../tools.aqua.bgw.event/-event/index.md)>?Event handler that gets invoked when animation has finished.   <br>|
| <a name="tools.aqua.bgw.animation/FlipAnimation/running/#/PointingToDeclaration/"></a>[running](index.md#-394385764%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/FlipAnimation/running/#/PointingToDeclaration/"></a> [jvm] var [running](index.md#-394385764%2FProperties%2F-1902411840): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)Boolean indicating whether the animation is currently playing.   <br>|
| <a name="tools.aqua.bgw.animation/FlipAnimation/toVisual/#/PointingToDeclaration/"></a>[toVisual](to-visual.md)| <a name="tools.aqua.bgw.animation/FlipAnimation/toVisual/#/PointingToDeclaration/"></a> [jvm] var [toVisual](to-visual.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)Resulting visual   <br>|

