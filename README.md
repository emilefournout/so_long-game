# so_long-game
Little C game pacman like

<img width="1303" alt="emile" src="https://user-images.githubusercontent.com/77667022/177381072-6f051cea-f506-41fc-949b-9c092649a1cc.png">

<a href="https://github.com/JaeSeoKim/badge42"><img src="https://badge42.vercel.app/api/v2/cl3uaey7l005409i8ff06egjg/stats?cursusId=21&coalitionId=undefined" alt="efournou's 42 stats" /></a>

<a href="https://github.com/JaeSeoKim/badge42"><img src="https://badge42.vercel.app/api/v2/cl3uaey7l005409i8ff06egjg/project/2633720" alt="efournou's 42 so_long Score" /></a>

Work only for MacOS, cause of Minilibx (42 graphic library), [https://harm-smits.github.io/42docs/libs/minilibx/getting_started.html#getting-a-screen-on-windows-10-wsl2](https://harm-smits.github.io/42docs/libs/minilibx/getting_started.html#getting-a-screen-on-windows-10-wsl2) for those who want to use Linux or Windows

**PLAY**

  First:
    `make`


  Then:
    `./so_long map/<namemap>.ber` exemple : `./so_long map/emile.ber`

  Take all pieces before finish in green zone good luck



**YOU CAN CREATE YOUR OWN MAP:**

First:
    `touch <namemap>.ber`


Then: Fill the file with:

    - 1 for a blue wall (map must be surrounded with)

    - 0 for nothing (white)

    - P for red starting point (only one in the map)

    - E for green endpoint

    - C for coins
    
 
 Exemple of map :
 
 <img width="67" alt="Screen Shot 2022-07-05 at 7 38 48 PM" src="https://user-images.githubusercontent.com/77667022/177384959-56a943e8-dd13-4c44-8cd4-e0c7d7720a5a.png">




Very interresting project, a big part is generate pixel by pixel, learn a lot about memory and have first use of graphical lib low level

That's it !
