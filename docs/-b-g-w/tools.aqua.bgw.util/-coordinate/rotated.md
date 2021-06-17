---
title: rotated -
---
//[BGW](../../../index.md)/[tools.aqua.bgw.util](../index.md)/[Coordinate](index.md)/[rotated](rotated.md)



# rotated  
[jvm]  
Content  
fun [rotated](rotated.md)(angle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), center: [Coordinate](index.md)): [Coordinate](index.md)  
More info  


Rotates coordinate by angle degrees around center point. With

<ul><li>Angle t,</li><li>Center point Z</li><li>Coordinate P</li></ul>

 cos(phi)  -sin(phi)  *  Px - Zx  +  Zx  =  sin(phi)   cos(phi)  Zy  sin(phi)*(Px-Zx) + cos(phi)*(Py-Zy) + Zy 

  


[jvm]  
Content  
fun [rotated](rotated.md)(angle: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)): [Coordinate](index.md)  
More info  


Rotates coordinate by angle degrees around point (0,0). With

<ul><li>Angle t,</li><li>Center point Z</li><li>Coordinate P</li></ul>

 cos(phi)  -sin(phi)  *  Px - Zx  +  Zx  =  sin(phi)   cos(phi)  Zy  sin(phi)*(Px-Zx) + cos(phi)*(Py-Zy) + Zy 

  



