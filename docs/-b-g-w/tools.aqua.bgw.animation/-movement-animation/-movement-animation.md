//[BGW](../../../index.md)/[tools.aqua.bgw.animation](../index.md)/[MovementAnimation](index.md)/[MovementAnimation](-movement-animation.md)



# MovementAnimation  
[jvm]  
Content  
fun <[T](index.md) : [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)> [MovementAnimation](-movement-animation.md)(elementView: [T](index.md), byX: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = 0.0, byY: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = 0.0, duration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1000)  
More info  


A movement animation. Moves given ElementView relative to parents anchor point.



## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a>elementView| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a><br><br>GameElementView to animate<br><br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a>byX| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a><br><br>Relative X movement.<br><br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a>byY| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a><br><br>Relative Y movement.<br><br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a>duration| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a><br><br>Animation duration in milliseconds. Default: 1 second<br><br>|
  
  


[jvm]  
Content  
fun <[T](index.md) : [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)> [MovementAnimation](-movement-animation.md)(elementView: [T](index.md), fromX: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = elementView.posX, toX: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = elementView.posX, fromY: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = elementView.posY, toY: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = elementView.posY, duration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1000)  
More info  


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a>elementView| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a><br><br>GameElementView to animate<br><br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a>fromX| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a><br><br>Initial X position. Default: current PosX<br><br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a>toX| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a><br><br>Resulting X position. Default: current PosX<br><br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a>fromY| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a><br><br>Initial X position. Default: current PosY<br><br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a>toY| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a><br><br>Resulting X position. Default: current PosY<br><br>|
| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a>duration| <a name="tools.aqua.bgw.animation/MovementAnimation/MovementAnimation/#TypeParam(bounds=[tools.aqua.bgw.elements.ElementView])#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Number#kotlin.Int/PointingToDeclaration/"></a><br><br>Animation duration in milliseconds. Default: 1 second<br><br>|
  
  



