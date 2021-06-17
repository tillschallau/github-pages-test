//[BGW](../../../index.md)/[tools.aqua.bgw.event](../index.md)/[KeyEvent](index.md)



# KeyEvent  
 [jvm] class [KeyEvent](index.md)(**keyCode**: [KeyCode](../-key-code/index.md), **character**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **controlDown**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **shiftDown**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **altDown**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) : [Event](../-event/index.md)

Event that gets raised for key inputs.

   


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.event/KeyEvent///PointingToDeclaration/"></a>keyCode| <a name="tools.aqua.bgw.event/KeyEvent///PointingToDeclaration/"></a><br><br>Corresponding key code enum value<br><br>|
| <a name="tools.aqua.bgw.event/KeyEvent///PointingToDeclaration/"></a>character| <a name="tools.aqua.bgw.event/KeyEvent///PointingToDeclaration/"></a><br><br>Corresponding character string<br><br>|
| <a name="tools.aqua.bgw.event/KeyEvent///PointingToDeclaration/"></a>controlDown| <a name="tools.aqua.bgw.event/KeyEvent///PointingToDeclaration/"></a><br><br>Whether control key was pressed<br><br>|
| <a name="tools.aqua.bgw.event/KeyEvent///PointingToDeclaration/"></a>shiftDown| <a name="tools.aqua.bgw.event/KeyEvent///PointingToDeclaration/"></a><br><br>Whether shift key was pressed<br><br>|
| <a name="tools.aqua.bgw.event/KeyEvent///PointingToDeclaration/"></a>altDown| <a name="tools.aqua.bgw.event/KeyEvent///PointingToDeclaration/"></a><br><br>Whether alt key was pressed<br><br>|
  


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.event/KeyEvent/KeyEvent/#tools.aqua.bgw.event.KeyCode#kotlin.String#kotlin.Boolean#kotlin.Boolean#kotlin.Boolean/PointingToDeclaration/"></a>[KeyEvent](-key-event.md)| <a name="tools.aqua.bgw.event/KeyEvent/KeyEvent/#tools.aqua.bgw.event.KeyCode#kotlin.String#kotlin.Boolean#kotlin.Boolean#kotlin.Boolean/PointingToDeclaration/"></a> [jvm] fun [KeyEvent](-key-event.md)(keyCode: [KeyCode](../-key-code/index.md) = KeyCode.UNDEFINED, character: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", controlDown: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), shiftDown: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), altDown: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))Corresponding key code enum value   <br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.event/KeyEvent/altDown/#/PointingToDeclaration/"></a>[altDown](alt-down.md)| <a name="tools.aqua.bgw.event/KeyEvent/altDown/#/PointingToDeclaration/"></a> [jvm] val [altDown](alt-down.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)Whether alt key was pressed   <br>|
| <a name="tools.aqua.bgw.event/KeyEvent/character/#/PointingToDeclaration/"></a>[character](character.md)| <a name="tools.aqua.bgw.event/KeyEvent/character/#/PointingToDeclaration/"></a> [jvm] val [character](character.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)Corresponding character string   <br>|
| <a name="tools.aqua.bgw.event/KeyEvent/controlDown/#/PointingToDeclaration/"></a>[controlDown](control-down.md)| <a name="tools.aqua.bgw.event/KeyEvent/controlDown/#/PointingToDeclaration/"></a> [jvm] val [controlDown](control-down.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)Whether control key was pressed   <br>|
| <a name="tools.aqua.bgw.event/KeyEvent/keyCode/#/PointingToDeclaration/"></a>[keyCode](key-code.md)| <a name="tools.aqua.bgw.event/KeyEvent/keyCode/#/PointingToDeclaration/"></a> [jvm] val [keyCode](key-code.md): [KeyCode](../-key-code/index.md)Corresponding key code enum value   <br>|
| <a name="tools.aqua.bgw.event/KeyEvent/shiftDown/#/PointingToDeclaration/"></a>[shiftDown](shift-down.md)| <a name="tools.aqua.bgw.event/KeyEvent/shiftDown/#/PointingToDeclaration/"></a> [jvm] val [shiftDown](shift-down.md): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)Whether shift key was pressed   <br>|

