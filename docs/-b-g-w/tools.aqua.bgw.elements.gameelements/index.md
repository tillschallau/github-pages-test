---
title: tools.aqua.bgw.elements.gameelements -
---
//[BGW](../../index.md)/[tools.aqua.bgw.elements.gameelements](index.md)



# Package tools.aqua.bgw.elements.gameelements  


## Types  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.elements.gameelements/CardView///PointingToDeclaration/"></a>[CardView](-card-view/index.md)| <a name="tools.aqua.bgw.elements.gameelements/CardView///PointingToDeclaration/"></a>[jvm]  <br>Content  <br>open class [CardView](-card-view/index.md)(**height**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **width**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **posX**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **posY**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **front**: [Visual](../tools.aqua.bgw.visual/-visual/index.md), **back**: [Visual](../tools.aqua.bgw.visual/-visual/index.md)) : [GameElementView](-game-element-view/index.md)  <br>More info  <br>A CardView may be used to visualize a card.  <br><br><br>|
| <a name="tools.aqua.bgw.elements.gameelements/DiceView///PointingToDeclaration/"></a>[DiceView](-dice-view/index.md)| <a name="tools.aqua.bgw.elements.gameelements/DiceView///PointingToDeclaration/"></a>[jvm]  <br>Content  <br>open class [DiceView](-dice-view/index.md)(**height**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **width**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **posX**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **posY**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **visuals**: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Visual](../tools.aqua.bgw.visual/-visual/index.md)>) : [GameElementView](-game-element-view/index.md)  <br>More info  <br>A DiceView may be used to visualize a dice of any sides.  <br><br><br>|
| <a name="tools.aqua.bgw.elements.gameelements/GameElementView///PointingToDeclaration/"></a>[GameElementView](-game-element-view/index.md)| <a name="tools.aqua.bgw.elements.gameelements/GameElementView///PointingToDeclaration/"></a>[jvm]  <br>Content  <br>sealed class [GameElementView](-game-element-view/index.md) : [DynamicView](../tools.aqua.bgw.elements/-dynamic-view/index.md)  <br>More info  <br>Abstract super class for game elements like cards or tokens.  <br><br><br>|
| <a name="tools.aqua.bgw.elements.gameelements/TokenView///PointingToDeclaration/"></a>[TokenView](-token-view/index.md)| <a name="tools.aqua.bgw.elements.gameelements/TokenView///PointingToDeclaration/"></a>[jvm]  <br>Content  <br>open class [TokenView](-token-view/index.md)(**height**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **width**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **posX**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **posY**: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html), **visual**: [Visual](../tools.aqua.bgw.visual/-visual/index.md)) : [GameElementView](-game-element-view/index.md)  <br>More info  <br>A TokenView may be used to visualize an kind of token.  <br><br><br>|

