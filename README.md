# solana-project


BUY
1. CHECK_IF_FREEZABLE - Set to true to buy tokens only if they are not freezable.
2. CHECK_IF_BURNED - Set to true to buy tokens only if their liquidity pool is burned.
3. CHECK_IF_IS_LOCKED (liquidity lock check)
4. CHECK_IF_MINT_IS_RENOUNCED - Set to true to buy tokens only if their mint is renounced.
5. CHECK_IF_MUTABLE - Set to true to buy tokens only if their metadata are not mutable.
6. CHECK_IF_SOCIALS - Set to true to buy tokens only if they have at least 1 social.
7. CHECK_TOP10_HOLDERS_PERCENTAGE: true/false
8. MIN_POOL_SIZE (bot buy only if pool size is > of amount) Set 0 to disable.
9. MAX_POOL_SIZE (bot buy only if pool size is < of amount) Set 0 to disable.
10. MIN_LP_BURNED_PERCENT - Some tokens only send 1 token to burned, it's better to calculate burned percent.
11. TAKE_PROFIT=  (in %)
12. STOP_LOSS= (in %)
13. MIN_SOL_LP: x
14. MIN_TOKEN_LP_PERCENTAGE: x
15. MAX_TOP10_HOLDERS_PERCENTAGE: 70
16. MAX_SINGLE_OWNER_PERCENTAGE: 10
SELL
1. PRICE_CHECK_INTERVAL (ms) :
   Interval in milliseconds for checking the take profit and stop loss conditions
   Set to zero to disable take profit and stop loss.
2. TAKE_PROFIT : x %
3. STOP_LOSS : x  %
4. SELL_SLIPPAGE : x %
5. SKIP_SELLING_IF_LOST_MORE_THAN : x %
   If token loses more than X% of value, bot will not try to sell
6. PRICE_CHECK_DURATION (ms) : x %
   Time in milliseconds to wait for stop loss/take profit conditions
   If you don't reach profit or loss bot will auto sell after this time
   Set to zero to disable take profit and stop loss
7. AUTO_SELL - true/false
8. MAX_SELL_RETRIES - Maximum number of retries for selling a token
