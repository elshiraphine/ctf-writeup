## Steg - Backward Time
> This pic we recovered from a lab pc seems suspect.
> 
> Can you check it out and see if anything stands out?
> 
> Developed by jackzabbs16

In this challenge we were given a [png file](assets/time_backwards.png). Using `strings` command, I found something interesting <br />
```
is this what you're
looking for?


01101000 01100101 01110010 01100101 00100000 01101100 01101001 01100101 01110011 00100000 01110100 01101000 01100101 00100000 01100110 01101100 01100001 01100111 00100000 01100110 01110010 01101111 01101101 00100000 01101100 01101111 01101110 01100111 00100000 01101100 01101111 01101110 01100111 00100000 01100001 01100111 01101111 00101110 00101110 00101110 00100000 01101110 01101001 01100011 01100011 01111011 01100110 01100001 00110001 00110001 01101001 01101110 01100111 01011111 01100010 01100001 01100011 01101011 01011111 01110011 01110000 01110010 00110001 01101110 01100111 01011111 01100001 01101000 00110011 01100001 01100100 01111101
```
So, using this [binary to ascii tools](https://www.binaryhexconverter.com/binary-to-ascii-text-converter), the flag was:
```
nicc{fa11ing_back_spr1ng_ah3ad}
```