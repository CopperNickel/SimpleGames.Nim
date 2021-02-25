# Nim Game 

[![NuGet version (SimpleGames.Nim)](https://img.shields.io/nuget/v/SimpleGames.Nim.svg?style=flat-square)](https://www.nuget.org/packages/SimpleGames.Nim/)

Is good old classical [Nim game](https://en.wikipedia.org/wiki/Nim)

# 3-5-7 Sticks Game

Is *Nim-like* game for two players. Each player takes turn removing at least **1** and at most **max** (usually **3**) consequent sticks.
Who takes the last stick loses (in reversed game wins). The initial position usually is
```
       | | |      (3 sticks)
     | | | | |    (5 sticks)
   | | | | | | |  (7 sticks)
```    
Note, that unlike *classical Nim* player can remove same number of sticks from same row in *different ways*, e.g. there are **3** unequal ways to remove 2 stick from the last row:
```
       | | |      
     | | | | |    
   x x | | | | |  

       | | |      
     | | | | |    
   | x x | | | |   

       | | |      
     | | | | |    
   | | x x | | | 
```
