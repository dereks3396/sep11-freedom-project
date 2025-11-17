# Tool Learning Log

## Tool: **Kaboom**

## Project: **Parkour Game**

---

### 11/11/25:
* Make a new mini project imported from kaboom
* Copy [sprite's](https://kaboomjs.com/play?example=sprite) code and replace it with bean instead of sprite
* from this: [Sprite](Sprite.png)
* to this: [Bean](Bean.png)
* Removed the frames because bean is not animated like sprite is so it just crashed the site
* Set animations like *idle* and *run* to 0 because [bean](ide-anims.png) is not animated like [sprite](kaboom-anims.png).


### 11/12/25:

In another [example](https://kaboomjs.com/play?example=level) of kaboom

* I changed the level map in addLevel. I made it a bit bigger and added more ground blocks, more coins, and one ghost.
* I added a new tile letter "g" in tiles. This makes the ghosty sprite and gives it the tag "danger", so if the player touches it, they get hurt like with the spikes.
* I saved the player’s first position in a variable called startPos. When the player hits a "danger" tile, I set player.pos back to startPos so the player goes back to the start.
* I made a score variable and a scoreLabel text on the screen. When the player touches a coin, the coin is removed, the sound plays, score goes up by 1, and the label text changes.
* I added another jump key. Now the player can jump with Space or the Up arrow. Both keys check if the player is on the ground before calling player.jump().



<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
