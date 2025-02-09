rev/javascryption : You wake up alone in a dark cabin, held captive by a bushy-haired man demanding you submit a "flag" to leave. Can you escape?

![image](Writeups/lactf2025/images/javascryption0.png)

So we have to enter the flag, interesting, checking the source code we see a very familiar string. Its a base85 string.

![image](lactf2025/images/javascryption1.png)

Putting that into cyberchef and doing a little bit of tinkering gives us the flag lactf{no_grizzly_walls_here}

![image](lactf2025/images/javascryption2.png)
