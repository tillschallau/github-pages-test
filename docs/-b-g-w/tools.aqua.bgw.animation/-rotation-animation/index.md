//[BGW](../../../index.md)/[tools.aqua.bgw.animation](../index.md)/[RotationAnimation](index.md)



# RotationAnimation  
 [jvm] class [RotationAnimation](index.md)<[T](index.md) : [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)>(**elementView**: [T](index.md), **fromAngle**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **toAngle**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **duration**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [ElementAnimation](../-element-animation/index.md)<[T](index.md)> 

A rotation animation. Rotates given ElementView to given angle.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/RotationAnimation///PointingToDeclaration/"></a>elementView| <a name="tools.aqua.bgw.animation/RotationAnimation///PointingToDeclaration/"></a><br><br>GameElementView to animate<br><br>|
| <a name="tools.aqua.bgw.animation/RotationAnimation///PointingToDeclaration/"></a>fromAngle| <a name="tools.aqua.bgw.animation/RotationAnimation///PointingToDeclaration/"></a><br><br>Initial angle. Default: current angle<br><br>|
| <a name="tools.aqua.bgw.animation/RotationAnimation///PointingToDeclaration/"></a>toAngle| <a name="tools.aqua.bgw.animation/RotationAnimation///PointingToDeclaration/"></a><br><br>Resulting angle. Default: current angle<br><br>|
| <a name="tools.aqua.bgw.animation/RotationAnimation///PointingToDeclaration/"></a>duration| <a name="tools.aqua.bgw.animation/RotationAnimation///PointingToDeclaration/"></a><br><br>Animation duration in milliseconds. Default: 1 second<br><br>|
  


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a>[RotationAnimation](-rotation-animation.md)| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a> [jvm] fun <[T](index.md) : [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)> [RotationAnimation](-rotation-animation.md)(elementView: [T](index.md), byAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, duration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1000)A rotation animation.   <br>|
| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a>[RotationAnimation](-rotation-animation.md)| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a> [jvm] fun <[T](index.md) : [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)> [RotationAnimation](-rotation-animation.md)(elementView: [T](index.md), fromAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = elementView.rotation, toAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = elementView.rotation, duration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1000)GameElementView to animate   <br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.animation/RotationAnimation/duration/#/PointingToDeclaration/"></a>[duration](index.md#-990622726%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/RotationAnimation/duration/#/PointingToDeclaration/"></a> [jvm] var [duration](index.md#-990622726%2FProperties%2F-1902411840): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)Animation duration in milliseconds.   <br>|
| <a name="tools.aqua.bgw.animation/RotationAnimation/element/#/PointingToDeclaration/"></a>[element](index.md#-2006637872%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/RotationAnimation/element/#/PointingToDeclaration/"></a> [jvm] val [element](index.md#-2006637872%2FProperties%2F-1902411840): [T](index.md)ElementView to animate   <br>|
| <a name="tools.aqua.bgw.animation/RotationAnimation/fromAngle/#/PointingToDeclaration/"></a>[fromAngle](from-angle.md)| <a name="tools.aqua.bgw.animation/RotationAnimation/fromAngle/#/PointingToDeclaration/"></a> [jvm] var [fromAngle](from-angle.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)Initial angle.   <br>|
| <a name="tools.aqua.bgw.animation/RotationAnimation/onFinished/#/PointingToDeclaration/"></a>[onFinished](index.md#-1458599811%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/RotationAnimation/onFinished/#/PointingToDeclaration/"></a> [jvm] var [onFinished](index.md#-1458599811%2FProperties%2F-1902411840): [EventHandler](../../tools.aqua.bgw.event/-event-handler/index.md)<[Event](../../tools.aqua.bgw.event/-event/index.md)>?Event handler that gets invoked when animation has finished.   <br>|
| <a name="tools.aqua.bgw.animation/RotationAnimation/running/#/PointingToDeclaration/"></a>[running](index.md#161758573%2FProperties%2F-1902411840)| <a name="tools.aqua.bgw.animation/RotationAnimation/running/#/PointingToDeclaration/"></a> [jvm] var [running](index.md#161758573%2FProperties%2F-1902411840): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)Boolean indicating whether the animation is currently playing.   <br>|
| <a name="tools.aqua.bgw.animation/RotationAnimation/toAngle/#/PointingToDeclaration/"></a>[toAngle](to-angle.md)| <a name="tools.aqua.bgw.animation/RotationAnimation/toAngle/#/PointingToDeclaration/"></a> [jvm] var [toAngle](to-angle.md): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)Resulting angle.   <br>|

