We changed part of the logic on July 18, 2023, the following is the analysis and compensation plan

If you execute the sent Json file from the unisat platform, two UTXOs will be sent, the first one is the sender’s UTXO, and the second one is the receiver’s UTXO; the previous logic of the Torbin Virtual machine is that we monitor the receiver’s UTXO, which is wrong. We have changed the logic of the underlying monitoring block, and now we monitor the sender’s Json, so when an address is mint, he should judge that it should be the json sender to get grc20 or grc721 grc137, because the address that sends json is the account that executes mint

Now we have reindexed

If some of your assets cannot be seen on the front end, please find the address where you sent and executed the json before, the assets may be there

For example, in the transaction details of https://mempool.space/address/bc1p26fd34c25034m4xmhldd6yvgppewn237qzjyj4pr6zp8wk7p09mszxz07f

It mint a domain, which was previously in bc1pkpzrepl45x7adwq0gl736xk69q6v6amr3ggaq6dygrvfdzqtqk
yseqm3j7

Now it's at bc1p06kcgwd3jcqahtp3a6ssz7ey58zew30m3wnzzh9g4law8cvw8f
dsttk3su
inside;

The re-indexed BTC block height is at 792982;

Therefore, after re-indexing, some assets cannot be seen because gensisBlock has not scanned them, but the assets are still visible in the wallet. We cannot change the front end of the webpage, so we give the following compensation plan

All those who cannot display "assets" on the webpage due to this incident will automatically reissue gsp, and we will provide $GSP tokens as compensation according to the missing amount of assets held
Because the gas fee is the same, we will compensate according to this ratio

grc 5:10000
mystery box 1:10000
All domains 1:10000

Note: GSP token is the only platform token of the Goldstandard project. The token has not been issued/minted at present. It will be the first currency issued on the BTC main network using smart contracts. Developers need GSP tokens to deploy smart contracts. Developers can also obtain long-term GSP rewards by creating library contracts;

We will count the number of people compensated by GSP tokens, and when the team is unlocked, it will be deducted from the team's share
