# Jupitercoin Core [JPC]
==========================

![Jupitercoin](http://i.imgur.com/JdBkcou.png)

## About
Jupitercoin is a cryptocurrency like Bitcoin, although it does not use SHA256 as its proof of work (POW). Taking development cues from Tenebrix and Litecoin, Jupitercoin currently employs a simplified variant of scrypt.

## License
Jupitercoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## FAQ

### Mining
Jupitercoin uses a simplified variant of the scrypt key derivation function as its proof of work with a target time of one minute per block and difficulty readjustment after every block. The block rewards are fixed and halve every 100,000 blocks. Starting with the 400,000th block, a permanent reward of 1 Jupitercoin per block will be paid.  The difficulty retargeting scheme is based off of Dogecoin.

The current block reward schedule:

* 1–99,999: 10 Jupitercoin 
* 100,000–199,999: 5 Jupitercoin
* 200,000–299,999: 2.5 Jupitercoin
* 300,000–399,999: 1.25 Jupitercoin
* 400,000+: 1 Jupitercoin

### Ports

* RPC 8569
* P2P 8568
