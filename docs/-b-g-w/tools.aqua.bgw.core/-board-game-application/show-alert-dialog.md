//[BGW](../../../index.md)/[tools.aqua.bgw.core](../index.md)/[BoardGameApplication](index.md)/[showAlertDialog](show-alert-dialog.md)



# showAlertDialog  
[jvm]  
Content  
fun [showAlertDialog](show-alert-dialog.md)(alertType: [AlertType](../../tools.aqua.bgw.dialog/-alert-type/index.md), msg: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg buttons: [ButtonType](../../tools.aqua.bgw.dialog/-button-type/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[ButtonType](../../tools.aqua.bgw.dialog/-button-type/index.md)>  
More info  


Shows a dialog containing the given message and buttons.



#### Return  


Chosen button or Optional.empty if canceled



## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.core/BoardGameApplication/showAlertDialog/#tools.aqua.bgw.dialog.AlertType#kotlin.String#kotlin.Array[tools.aqua.bgw.dialog.ButtonType]/PointingToDeclaration/"></a>alertType| <a name="tools.aqua.bgw.core/BoardGameApplication/showAlertDialog/#tools.aqua.bgw.dialog.AlertType#kotlin.String#kotlin.Array[tools.aqua.bgw.dialog.ButtonType]/PointingToDeclaration/"></a><br><br>The type of the alert. Affects the displayed icon<br><br>|
| <a name="tools.aqua.bgw.core/BoardGameApplication/showAlertDialog/#tools.aqua.bgw.dialog.AlertType#kotlin.String#kotlin.Array[tools.aqua.bgw.dialog.ButtonType]/PointingToDeclaration/"></a>msg| <a name="tools.aqua.bgw.core/BoardGameApplication/showAlertDialog/#tools.aqua.bgw.dialog.AlertType#kotlin.String#kotlin.Array[tools.aqua.bgw.dialog.ButtonType]/PointingToDeclaration/"></a><br><br>Message to be shown<br><br>|
| <a name="tools.aqua.bgw.core/BoardGameApplication/showAlertDialog/#tools.aqua.bgw.dialog.AlertType#kotlin.String#kotlin.Array[tools.aqua.bgw.dialog.ButtonType]/PointingToDeclaration/"></a>buttons| <a name="tools.aqua.bgw.core/BoardGameApplication/showAlertDialog/#tools.aqua.bgw.dialog.AlertType#kotlin.String#kotlin.Array[tools.aqua.bgw.dialog.ButtonType]/PointingToDeclaration/"></a><br><br>Buttons to be shown<br><br>|
  
  



