---
title: RotationAnimation -
---
//[BGW](../../../index.md)/[tools.aqua.bgw.animation](../index.md)/[RotationAnimation](index.md)/[RotationAnimation](-rotation-animation.md)



# RotationAnimation  
[jvm]  
Content  
fun <[T](index.md) : [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)> [RotationAnimation](-rotation-animation.md)(elementView: [T](index.md), byAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = 0.0, duration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1000)  
More info  


A rotation animation. Rotates given ElementView to given angle.



## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a>elementView| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a><br><br>GameElementView to animate<br><br>|
| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a>byAngle| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a><br><br>Relative angle. Default: 0<br><br>|
| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a>duration| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a><br><br>Animation duration in milliseconds. Default: 1 second<br><br>|
  
  


[jvm]  
Content  
fun <[T](index.md) : [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)> [RotationAnimation](-rotation-animation.md)(elementView: [T](index.md), fromAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = elementView.rotation, toAngle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) = elementView.rotation, duration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1000)  
More info  


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a>elementView| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a><br><br>GameElementView to animate<br><br>|
| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a>fromAngle| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a><br><br>Initial angle. Default: current angle<br><br>|
| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a>toAngle| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a><br><br>Resulting angle. Default: current angle<br><br>|
| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a>duration| <a name="tools.aqua.bgw.animation/RotationAnimation/RotationAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Double#kotlin.Double#kotlin.Int/PointingToDeclaration/"></a><br><br>Animation duration in milliseconds. Default: 1 second<br><br>|
  
  



