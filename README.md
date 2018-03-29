# Dstm-NoDevFee
Dstm (<=0.5.7) fee redirect for Linux-based systems.
----------------------------------------------------------------------

What is this?

This .so allows you to redirect dstm's miner dev fee to your walle.

----------------------------------------------------------------------

How does it work?

It simply uses LD_PRELOAD trick to insert your wallet instead of dstm's.

----------------------------------------------------------------------

How do I use it?

!Works only with Dstm's miner 0.5.7 (0.5.8 and higher are not supported)
You can run it on Linux-based OS by using this command: 
LD_PRELOAD=/absolute/path/to/the/nofee.so ./zm <standard-arguments-you-use-with-this-miner>

If you use Windows OS you may try using Stratum Proxy for Zcash.
