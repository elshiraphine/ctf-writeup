## Misc - D0ts N D4sh3s

In this challenge, we were given an attachment with morse code in it as follows.

```
----- .---- ----- ----- ----- ----- ----- .---- / ----- .---- ----- .---- ----- ----- .---- ----- / ----- .---- ----- ----- ----- ----- ----- .---- / ----- ----- .---- .---- ----- ----- .---- ----- / ----- ----- .---- .---- ----- ----- ----- ----- / ----- ----- .---- .---- ----- ----- .---- ----- / ----- ----- .---- .---- ----- ----- .---- .---- / ----- .---- .---- .---- .---- ----- .---- .---- / ----- ----- .---- ----- ----- ----- ----- .---- / ----- .---- .---- .---- ----- .---- ----- ----- / ----- .---- .---- .---- ----- ----- .---- .---- / ----- .---- ----- .---- .---- .---- .---- .---- / ----- .---- .---- ----- .---- ----- .---- ----- / ----- .---- .---- .---- ----- .---- ----- .---- / ----- ----- .---- .---- ----- .---- ----- .---- / ----- .---- .---- .---- ----- .---- ----- ----- / ----- .---- ----- .---- .---- .---- .---- .---- / ----- ----- .---- .---- ----- .---- ----- ----- / ----- .---- ----- .---- .---- .---- .---- .---- / ----- .---- .---- ----- .---- .---- ----- .---- / ----- ----- .---- .---- ----- ----- ----- ----- / ----- .---- .---- .---- ----- ----- .---- ----- / ----- .---- .---- .---- ----- ----- .---- .---- / ----- ----- .---- .---- ----- ----- .---- .---- / ----- .---- ----- .---- .---- .---- .---- .---- / ----- .---- .---- ----- ----- ----- ----- .---- / ----- .---- .---- ----- ----- .---- .---- ----- / ----- .---- .---- .---- ----- .---- ----- ----- / ----- ----- .---- .---- ----- ----- .---- .---- / ----- ----- .---- .---- ----- ----- ----- .---- / ----- ----- .---- .---- ----- ----- .---- ----- / ----- .---- ----- .---- .---- .---- .---- .---- / ----- .---- .---- ----- ----- ----- ----- .---- / ----- ----- .---- .---- ----- ----- ----- .---- / ----- ----- .---- ----- ----- ----- ----- .---- / ----- .---- .---- .---- .---- .---- ----- .----
```

We try to convert this morse code. Thanks to [morsedecoder.com](https://morsedecoder.com/id/). We got the binary code as follows.

```
01000001 01010010 01000001 00110010 00110000 00110010 00110011 01111011 00100001 01110100 01110011 01011111 01101010 01110101 00110101 01110100 01011111 00110100 01011111 01101101 00110000 01110010 01110011 00110011 01011111 01100001 01100110 01110100 00110011 00110001 00110010 01011111 01100001 00110001 00100001 01111101
```

Using the binary decoder from [cryptii.com](https://cryptii.com/pipes/binary-decoder), we got the flag.

</br>

So, this is the flag.

```
ARA2023{!ts_ju5t_4_m0rs3_aft312_a1!}
```
