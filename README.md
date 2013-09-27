BouncingArrows
==============

This is an slightly modified version eyalzh's BouncingArrows plugin (https://github.com/eyalzh/bouncingarrows).

Changes are:

* improved bouncing off of half blocks (like iron fences, glass panes, flower pots, etc.)
* added some checks to let arrows still stick to wooden buttons and wooden plates
* more bouncing: arrows are now bouncing until they are too slow, instead of the limit based on enchantment level (also reduced the the speed threshold from 0.6 to 0.5)
* reduced the arrow spray from 12 to 4
* the reflected/new spawned arrows are no pickup-able by players, just like normal ones
* added bouncing for snowballs (0.3 speed threshold)
* added some kind of "targetfinder/aimbot" for players with the right permission, just for fun :P (if the angle between the arrows initial direction and the direction towards the target is small enough, it will slightly push the arrow towards the target)
