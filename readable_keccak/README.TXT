Hi.

The SHA-3 competition is nearing it's end and I would personally like 
to support Keccak as the winner. I have a PhD in hash function cryptanalysis
so don't take my word for it, go ahead and look into the code !

Since I couldn't find a *compact* and/or *readable* implementation of Keccak 
anywhere, here's one I cooked up as a service to the curious.

This implementation is intended for study of the algorithm, not for 
production use. 

The code works correctly on 64-bit little-endian platforms with gcc.
Like your Linux box. The main.c module contains self-tests for all 
officially supported hash sizes. 

If you're looking for production code, the official multi-megabyte package
covers everyting you could possibly need and too much much more: 
http://keccak.noekeon.org/

Cheers,
- Markku  19-Nov-11

Dr. Markku-Juhani O. Saarinen <mjos@iki.fi>
