---
title: tools.aqua.bgw.visual -
---
//[BGW](../../index.md)/[tools.aqua.bgw.visual](index.md)



# Package tools.aqua.bgw.visual  


## Types  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.visual/ColorVisual///PointingToDeclaration/"></a>[ColorVisual](-color-visual/index.md)| <a name="tools.aqua.bgw.visual/ColorVisual///PointingToDeclaration/"></a>[jvm]  <br>Content  <br>class [ColorVisual](-color-visual/index.md)(**color**: [Color](https://docs.oracle.com/javase/8/docs/api/java/awt/Color.html)) : [SingleLayerVisual](-single-layer-visual/index.md)  <br>More info  <br>A solid color visual.  <br><br><br>|
| <a name="tools.aqua.bgw.visual/CompoundVisual///PointingToDeclaration/"></a>[CompoundVisual](-compound-visual/index.md)| <a name="tools.aqua.bgw.visual/CompoundVisual///PointingToDeclaration/"></a>[jvm]  <br>Content  <br>class [CompoundVisual](-compound-visual/index.md)(**children**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[SingleLayerVisual](-single-layer-visual/index.md)>) : [Visual](-visual/index.md)  <br>More info  <br>A compound visual containing stacked single layer visuals.  <br><br><br>|
| <a name="tools.aqua.bgw.visual/ImageVisual///PointingToDeclaration/"></a>[ImageVisual](-image-visual/index.md)| <a name="tools.aqua.bgw.visual/ImageVisual///PointingToDeclaration/"></a>[jvm]  <br>Content  <br>class [ImageVisual](-image-visual/index.md)(**image**: [BufferedImage](https://docs.oracle.com/javase/8/docs/api/java/awt/image/BufferedImage.html)) : [SingleLayerVisual](-single-layer-visual/index.md)  <br>More info  <br>Visual showing an image.  <br><br><br>|
| <a name="tools.aqua.bgw.visual/SingleLayerVisual///PointingToDeclaration/"></a>[SingleLayerVisual](-single-layer-visual/index.md)| <a name="tools.aqua.bgw.visual/SingleLayerVisual///PointingToDeclaration/"></a>[jvm]  <br>Content  <br>sealed class [SingleLayerVisual](-single-layer-visual/index.md) : [Visual](-visual/index.md)  <br>More info  <br>Superclass for single layer visuals.  <br><br><br>|
| <a name="tools.aqua.bgw.visual/TextVisual///PointingToDeclaration/"></a>[TextVisual](-text-visual/index.md)| <a name="tools.aqua.bgw.visual/TextVisual///PointingToDeclaration/"></a>[jvm]  <br>Content  <br>class [TextVisual](-text-visual/index.md)(**text**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) : [SingleLayerVisual](-single-layer-visual/index.md)  <br>More info  <br>A visual displaying text.  <br><br><br>|
| <a name="tools.aqua.bgw.visual/Visual///PointingToDeclaration/"></a>[Visual](-visual/index.md)| <a name="tools.aqua.bgw.visual/Visual///PointingToDeclaration/"></a>[jvm]  <br>Content  <br>sealed class [Visual](-visual/index.md)  <br>More info  <br>Visual superclass.  <br><br><br>|

