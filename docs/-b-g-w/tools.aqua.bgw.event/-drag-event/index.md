//[BGW](../../../index.md)/[tools.aqua.bgw.event](../index.md)/[DragEvent](index.md)



# DragEvent  
 [jvm] class [DragEvent](index.md)(**draggedElement**: [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md), **dragTargets**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)>) : [Event](../-event/index.md)

Event that gets raised for drag gestures.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.event/DragEvent///PointingToDeclaration/"></a>draggedElement| <a name="tools.aqua.bgw.event/DragEvent///PointingToDeclaration/"></a><br><br>Currently dragged ElementView<br><br>|
| <a name="tools.aqua.bgw.event/DragEvent///PointingToDeclaration/"></a>dragTargets| <a name="tools.aqua.bgw.event/DragEvent///PointingToDeclaration/"></a><br><br>list of all ElementViews that accepted the drag gesture<br><br>|
  


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.event/DragEvent/DragEvent/#tools.aqua.bgw.elements.ElementView#kotlin.collections.List[tools.aqua.bgw.elements.ElementView]/PointingToDeclaration/"></a>[DragEvent](-drag-event.md)| <a name="tools.aqua.bgw.event/DragEvent/DragEvent/#tools.aqua.bgw.elements.ElementView#kotlin.collections.List[tools.aqua.bgw.elements.ElementView]/PointingToDeclaration/"></a> [jvm] fun [DragEvent](-drag-event.md)(draggedElement: [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md), dragTargets: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)> = listOf())Currently dragged ElementView   <br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.event/DragEvent/draggedElement/#/PointingToDeclaration/"></a>[draggedElement](dragged-element.md)| <a name="tools.aqua.bgw.event/DragEvent/draggedElement/#/PointingToDeclaration/"></a> [jvm] val [draggedElement](dragged-element.md): [ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)Currently dragged ElementView   <br>|
| <a name="tools.aqua.bgw.event/DragEvent/dragTargets/#/PointingToDeclaration/"></a>[dragTargets](drag-targets.md)| <a name="tools.aqua.bgw.event/DragEvent/dragTargets/#/PointingToDeclaration/"></a> [jvm] val [dragTargets](drag-targets.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[ElementView](../../tools.aqua.bgw.elements/-element-view/index.md)>list of all ElementViews that accepted the drag gesture   <br>|

