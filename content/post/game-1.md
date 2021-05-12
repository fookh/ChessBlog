---
date: 2021-05-02
description: "How not to attack against the London System"
featured_image: "/images/posts/p001/01.PNG"
tags: ["Black", "London System", "King's Indian Defense", "d4"]
title: "Game 1: The London failure"
disable_share: "true"
---

## Summary
My opponent played the London System and I responded with the King's Indian setup. I tried to break in the center to challenge his position but failed to do so properly. By move 13, the game was basically over with a 4.5 avantage for white after a disastrous queen move.

My post-game analysis shows that there was at least two good opportunities that I missed during the game.

## The game

<iframe id="7964730" allowtransparency="true" frameborder="0" style="width:100%;border:none;" src="//www.chess.com/emboard?id=7964730"></iframe><script>window.addEventListener("message",e=>{e['data']&&"7964730"===e['data']['id']&&document.getElementById(`${e['data']['id']}`)&&(document.getElementById(`${e['data']['id']}`).style.height=`${e['data']['frameHeight']+30}px`)});</script>

## Hunting the dark squared bishop
One of the main idea in the London System is to quickly get the darked squared bishop beyond the pawn chain. But then it can easily be attacked and White often has to play h3 to give it a cover square.

This game is no exception and with my knight quickly coming on f6, I had to opportunity to trade for his bishop and open my dark squared bishop which would be then uncontested.

{{< figure src="/images/posts/p001/02.PNG" title="The most played move is h3">}}

{{< figure src="/images/posts/p001/03.GIF" title="Here's how masters would abuse this bishop">}}

## The light squared bishop placement
In the London System, the light squared bishop goes on e2.

In this game, my opponent choose d3 which is punishable with the right idea.

{{< figure src="/images/posts/p001/04.PNG" title="Bd3 is terrible! If you know how to punish it...">}}

The idea is to abuse a fork with the bishop on d3 and the knight on f3. In order to achieve that plan, we need to bring the rook on e8 to support the e-pawn push.

### The more precise way

{{< figure src="/images/posts/p001/05.GIF" title="Here's how Stockfish manages to defend">}}

White still has a way to defend against the fork by pinning the knight to the queen. 

Because White controls the e4 square twice, black needs to knight to help the rook support the e4 push. Sacrificing the dark squared bishop gives enough time for White to move a piece to e4 and block the push and the fork.

It's still a good position for Black.

### The more effective way

{{< figure src="/images/posts/p001/06.GIF" title="White loses a piece if he doesn't react on time">}}

Because we are not playing against stockfish or master level players, we can try to prevent the defense by playing h6. 

While this is a bad move because it gives White the change to move the light squared bishop out of the fork, it's likely that a player that played Bd3 doesn't know about this position and will get caught.

## Against normal London System development

Because my futur opponent might not make this mistakes, here's how we want to break the center against the London System.

The central break should be coming on c5 to avoid the over protected e5 square. Somehow, removing the queens seems mandatory for Black. I'm not sure why.

{{< figure src="/images/posts/p001/07.GIF" title="The c5 push is easier">}}

## Conclusion

Against the London System, we now have our checklist to know what to do:
- Did the opponent keep a safe square for his dark squared bishop? If not, hunt him down with our knight.
- Did the opponent played Bd2? If not, look for tactical idea in the center.
- Does the opponent has a safe position centered around e4? If yes, push the c-pawn to break in the center