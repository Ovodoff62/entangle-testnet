When using Arbitrum custom chain:
Stacking Feature: Couldn't remove Stake from USDT Pool (error "Transaction is failed"), while USDC worked fine.
Transfer Feature: Couldn't send sSGUC (error "Transaction is failed") until I added more USDC in Staking. Seems like there is a minimum amount of sSGUC that you need to have in order for transfer to work. And there are no mentions of that in Transfer window.
Transfer Feature: Couldn't send sSGUT even when added more USDT in Staking (error "Transaction is failed"). Tried various amounts but couldn't make Unstaking and Transfer work for USDT.
General:
After "Transfer" is completed, can't find LSDs on arrival chain, tried to detect them with Transfer function, always shows zero. Tested with tokens on Polygon, Arbitrum, Avalanche.
After successful transaction, window often not updating available balance correctly, until you refresh the page.

UI suggestions:
Wold be nice to have buttons (25%, 50%, 75%) or slider in window next to amount in Staking/Exchange/Transfer windows.
In transfer when opening Token list, it show list in default order without detecting chain and tokens. If I'm connected to let's say Arbitrum, when I open token list, naturally I expect to see Arbitrum tokens on top and with balance.
