# Testnet-blocksize-fork-data-Raw
For some tests I use Blocktrail testnet webhooks, 
Here are all the blocks (in structured format) that my service rejected in last ~2 weeks for various reasons,
some are just timeout issues that took more time than the next block to reach my server and considered an older block,
and the later ones are regarding the forks on testnet blockchain for blocksize proposals (BIP101, 8MB vote, ... )

Some info about the data :

Starting block :

      * height: 580259

      * arrival_time: 2015-10-27T12:40:55+0000

End Block:

      * height: 601430

      * arrival_time: 2015-11-11T07:13:27+0000
      
I may not have the time to make some sense out of this data, but I know someone will 
Although there might be better ways to get this data (including data for the main branch), It might be challenging for some.

Keep me posted if you did something cool with it,

p.s some interesting things to look at https://twitter.com/lopp/status/664099176234532864

e.g.

      * "height": 601529
      * "block_time": "2015-11-11T08:20:02+0000"
      * "arrival_time":"2015-11-11T06:33:13+0000"
