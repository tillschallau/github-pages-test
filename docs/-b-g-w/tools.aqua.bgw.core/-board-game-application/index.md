//[BGW](../../../index.md)/[tools.aqua.bgw.core](../index.md)/[BoardGameApplication](index.md)



# BoardGameApplication  
 [jvm] open class [BoardGameApplication](index.md)

Superclass for all BGW Applications.



You may extend from this class in order to create your own application. Scenes get shown by calling showMenuScene and showGameScene. Application starts by calling show.

   


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.core/BoardGameApplication/BoardGameApplication/#/PointingToDeclaration/"></a>[BoardGameApplication](-board-game-application.md)| <a name="tools.aqua.bgw.core/BoardGameApplication/BoardGameApplication/#/PointingToDeclaration/"></a> [jvm] fun [BoardGameApplication](-board-game-application.md)()   <br>|


## Functions  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.core/BoardGameApplication/hideMenuScene/#kotlin.Number/PointingToDeclaration/"></a>[hideMenuScene](hide-menu-scene.md)| <a name="tools.aqua.bgw.core/BoardGameApplication/hideMenuScene/#kotlin.Number/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [hideMenuScene](hide-menu-scene.md)(fadeTime: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = Frontend.DEFAULT_FADE_TIME)  <br>More info  <br>Hides currently shown menuScene.  <br><br><br>|
| <a name="tools.aqua.bgw.core/BoardGameApplication/repaint/#/PointingToDeclaration/"></a>[repaint](repaint.md)| <a name="tools.aqua.bgw.core/BoardGameApplication/repaint/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [repaint](repaint.md)()  <br>More info  <br>Manually refreshes currently displayed scenes.  <br><br><br>|
| <a name="tools.aqua.bgw.core/BoardGameApplication/setFullScreen/#kotlin.Boolean/PointingToDeclaration/"></a>[setFullScreen](set-full-screen.md)| <a name="tools.aqua.bgw.core/BoardGameApplication/setFullScreen/#kotlin.Boolean/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [setFullScreen](set-full-screen.md)(fullscreen: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))  <br>More info  <br>Sets this BoardGameApplication to fullscreen mode.  <br><br><br>|
| <a name="tools.aqua.bgw.core/BoardGameApplication/setHorizontalSceneAlignment/#tools.aqua.bgw.core.HorizontalAlignment/PointingToDeclaration/"></a>[setHorizontalSceneAlignment](set-horizontal-scene-alignment.md)| <a name="tools.aqua.bgw.core/BoardGameApplication/setHorizontalSceneAlignment/#tools.aqua.bgw.core.HorizontalAlignment/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [setHorizontalSceneAlignment](set-horizontal-scene-alignment.md)(newHorizontalAlignment: [HorizontalAlignment](../-horizontal-alignment/index.md))  <br>More info  <br>Sets horizontal alignment of all scenes in this BoardGameApplication.  <br><br><br>|
| <a name="tools.aqua.bgw.core/BoardGameApplication/setScaleMode/#tools.aqua.bgw.core.ScaleMode/PointingToDeclaration/"></a>[setScaleMode](set-scale-mode.md)| <a name="tools.aqua.bgw.core/BoardGameApplication/setScaleMode/#tools.aqua.bgw.core.ScaleMode/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [setScaleMode](set-scale-mode.md)(newScaleMode: [ScaleMode](../-scale-mode/index.md))  <br>More info  <br>Sets scale mode of all scenes in this BoardGameApplication.  <br><br><br>|
| <a name="tools.aqua.bgw.core/BoardGameApplication/setSceneAlignment/#tools.aqua.bgw.core.Alignment/PointingToDeclaration/"></a>[setSceneAlignment](set-scene-alignment.md)| <a name="tools.aqua.bgw.core/BoardGameApplication/setSceneAlignment/#tools.aqua.bgw.core.Alignment/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [setSceneAlignment](set-scene-alignment.md)(newAlignment: [Alignment](../-alignment/index.md))  <br>More info  <br>Sets alignment of all scenes in this BoardGameApplication.  <br><br><br>|
| <a name="tools.aqua.bgw.core/BoardGameApplication/setVerticalSceneAlignment/#tools.aqua.bgw.core.VerticalAlignment/PointingToDeclaration/"></a>[setVerticalSceneAlignment](set-vertical-scene-alignment.md)| <a name="tools.aqua.bgw.core/BoardGameApplication/setVerticalSceneAlignment/#tools.aqua.bgw.core.VerticalAlignment/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [setVerticalSceneAlignment](set-vertical-scene-alignment.md)(newVerticalAlignment: [VerticalAlignment](../-vertical-alignment/index.md))  <br>More info  <br>Sets vertical alignment of all scenes in this BoardGameApplication.  <br><br><br>|
| <a name="tools.aqua.bgw.core/BoardGameApplication/show/#/PointingToDeclaration/"></a>[show](show.md)| <a name="tools.aqua.bgw.core/BoardGameApplication/show/#/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [show](show.md)()  <br>More info  <br>Shows the BoardGameApplication.  <br><br><br>|
| <a name="tools.aqua.bgw.core/BoardGameApplication/showAlertDialog/#tools.aqua.bgw.dialog.AlertType#kotlin.String#kotlin.Array[tools.aqua.bgw.dialog.ButtonType]/PointingToDeclaration/"></a>[showAlertDialog](show-alert-dialog.md)| <a name="tools.aqua.bgw.core/BoardGameApplication/showAlertDialog/#tools.aqua.bgw.dialog.AlertType#kotlin.String#kotlin.Array[tools.aqua.bgw.dialog.ButtonType]/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [showAlertDialog](show-alert-dialog.md)(alertType: [AlertType](../../tools.aqua.bgw.dialog/-alert-type/index.md), msg: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), vararg buttons: [ButtonType](../../tools.aqua.bgw.dialog/-button-type/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[ButtonType](../../tools.aqua.bgw.dialog/-button-type/index.md)>  <br>More info  <br>Shows a dialog containing the given message and buttons.  <br><br><br>|
| <a name="tools.aqua.bgw.core/BoardGameApplication/showFileDialog/#tools.aqua.bgw.dialog.FileDialog/PointingToDeclaration/"></a>[showFileDialog](show-file-dialog.md)| <a name="tools.aqua.bgw.core/BoardGameApplication/showFileDialog/#tools.aqua.bgw.dialog.FileDialog/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [showFileDialog](show-file-dialog.md)(dialog: [FileDialog](../../tools.aqua.bgw.dialog/-file-dialog/index.md)): [Optional](https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html)<[List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)>>  <br>More info  <br>Shows the given FileDialog.  <br><br><br>|
| <a name="tools.aqua.bgw.core/BoardGameApplication/showGameScene/#tools.aqua.bgw.core.BoardGameScene/PointingToDeclaration/"></a>[showGameScene](show-game-scene.md)| <a name="tools.aqua.bgw.core/BoardGameApplication/showGameScene/#tools.aqua.bgw.core.BoardGameScene/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [showGameScene](show-game-scene.md)(scene: [BoardGameScene](../-board-game-scene/index.md))  <br>More info  <br>Shows given BoardGameScene.  <br><br><br>|
| <a name="tools.aqua.bgw.core/BoardGameApplication/showMenuScene/#tools.aqua.bgw.core.MenuScene#kotlin.Number/PointingToDeclaration/"></a>[showMenuScene](show-menu-scene.md)| <a name="tools.aqua.bgw.core/BoardGameApplication/showMenuScene/#tools.aqua.bgw.core.MenuScene#kotlin.Number/PointingToDeclaration/"></a>[jvm]  <br>Content  <br>fun [showMenuScene](show-menu-scene.md)(scene: [MenuScene](../-menu-scene/index.md), fadeTime: [Number](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-number/index.html) = Frontend.DEFAULT_FADE_TIME)  <br>More info  <br>Shows given menu scene.  <br><br><br>|

