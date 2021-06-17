//[BGW](../../../index.md)/[tools.aqua.bgw.dialog](../index.md)/[FileDialog](index.md)



# FileDialog  
 [jvm] data class [FileDialog](index.md)(**mode**: [FileDialog.FileDialogMode](-file-dialog-mode/index.md), **title**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **initialFileName**: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), **initialDirectory**: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)?, **extensionFilters**: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[ExtensionFilter](../-extension-filter/index.md)>)

A FileDialog such as a file chooser or save dialog, depending on FileDialogMode.

   


## See also  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.dialog/FileDialog///PointingToDeclaration/"></a>[tools.aqua.bgw.dialog.FileDialog.FileDialogMode](-file-dialog-mode/index.md)| <a name="tools.aqua.bgw.dialog/FileDialog///PointingToDeclaration/"></a>|
| <a name="tools.aqua.bgw.dialog/FileDialog///PointingToDeclaration/"></a>[tools.aqua.bgw.dialog.ExtensionFilter](../-extension-filter/index.md)| <a name="tools.aqua.bgw.dialog/FileDialog///PointingToDeclaration/"></a>|
  


## Parameters  
  
jvm  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.dialog/FileDialog///PointingToDeclaration/"></a>mode| <a name="tools.aqua.bgw.dialog/FileDialog///PointingToDeclaration/"></a><br><br>The dialog's mode<br><br>|
| <a name="tools.aqua.bgw.dialog/FileDialog///PointingToDeclaration/"></a>title| <a name="tools.aqua.bgw.dialog/FileDialog///PointingToDeclaration/"></a><br><br>The dialog's title text<br><br>|
| <a name="tools.aqua.bgw.dialog/FileDialog///PointingToDeclaration/"></a>initialFileName| <a name="tools.aqua.bgw.dialog/FileDialog///PointingToDeclaration/"></a><br><br>The initial file name in the file name text box<br><br>|
| <a name="tools.aqua.bgw.dialog/FileDialog///PointingToDeclaration/"></a>initialDirectory| <a name="tools.aqua.bgw.dialog/FileDialog///PointingToDeclaration/"></a><br><br>The initial drectory where to open the file chooser<br><br>|
| <a name="tools.aqua.bgw.dialog/FileDialog///PointingToDeclaration/"></a>extensionFilters| <a name="tools.aqua.bgw.dialog/FileDialog///PointingToDeclaration/"></a><br><br>Extensions filters for this file chooser<br><br>|
  


## Constructors  
  
| | |
|---|---|
| <a name="tools.aqua.bgw.dialog/FileDialog/FileDialog/#tools.aqua.bgw.dialog.FileDialog.FileDialogMode#kotlin.String#kotlin.String#java.io.File?#kotlin.collections.List[tools.aqua.bgw.dialog.ExtensionFilter]/PointingToDeclaration/"></a>[FileDialog](-file-dialog.md)| <a name="tools.aqua.bgw.dialog/FileDialog/FileDialog/#tools.aqua.bgw.dialog.FileDialog.FileDialogMode#kotlin.String#kotlin.String#java.io.File?#kotlin.collections.List[tools.aqua.bgw.dialog.ExtensionFilter]/PointingToDeclaration/"></a> [jvm] fun [FileDialog](-file-dialog.md)(mode: [FileDialog.FileDialogMode](-file-dialog-mode/index.md), title: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", initialFileName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) = "", initialDirectory: [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)? = null, extensionFilters: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[ExtensionFilter](../-extension-filter/index.md)> = listOf())The dialog's mode   <br>|


## Types  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.dialog/FileDialog.FileDialogMode///PointingToDeclaration/"></a>[FileDialogMode](-file-dialog-mode/index.md)| <a name="tools.aqua.bgw.dialog/FileDialog.FileDialogMode///PointingToDeclaration/"></a>[jvm]  <br>Content  <br>enum [FileDialogMode](-file-dialog-mode/index.md) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[FileDialog.FileDialogMode](-file-dialog-mode/index.md)>   <br>More info  <br>Enum for possible FileDialog modes.  <br><br><br>|


## Properties  
  
|  Name |  Summary | 
|---|---|
| <a name="tools.aqua.bgw.dialog/FileDialog/extensionFilters/#/PointingToDeclaration/"></a>[extensionFilters](extension-filters.md)| <a name="tools.aqua.bgw.dialog/FileDialog/extensionFilters/#/PointingToDeclaration/"></a> [jvm] val [extensionFilters](extension-filters.md): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[ExtensionFilter](../-extension-filter/index.md)>Extensions filters for this file chooser   <br>|
| <a name="tools.aqua.bgw.dialog/FileDialog/initialDirectory/#/PointingToDeclaration/"></a>[initialDirectory](initial-directory.md)| <a name="tools.aqua.bgw.dialog/FileDialog/initialDirectory/#/PointingToDeclaration/"></a> [jvm] val [initialDirectory](initial-directory.md): [File](https://docs.oracle.com/javase/8/docs/api/java/io/File.html)? = nullThe initial drectory where to open the file chooser   <br>|
| <a name="tools.aqua.bgw.dialog/FileDialog/initialFileName/#/PointingToDeclaration/"></a>[initialFileName](initial-file-name.md)| <a name="tools.aqua.bgw.dialog/FileDialog/initialFileName/#/PointingToDeclaration/"></a> [jvm] val [initialFileName](initial-file-name.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)The initial file name in the file name text box   <br>|
| <a name="tools.aqua.bgw.dialog/FileDialog/mode/#/PointingToDeclaration/"></a>[mode](mode.md)| <a name="tools.aqua.bgw.dialog/FileDialog/mode/#/PointingToDeclaration/"></a> [jvm] val [mode](mode.md): [FileDialog.FileDialogMode](-file-dialog-mode/index.md)The dialog's mode   <br>|
| <a name="tools.aqua.bgw.dialog/FileDialog/title/#/PointingToDeclaration/"></a>[title](title.md)| <a name="tools.aqua.bgw.dialog/FileDialog/title/#/PointingToDeclaration/"></a> [jvm] val [title](title.md): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)The dialog's title text   <br>|

