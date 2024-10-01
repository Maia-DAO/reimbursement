# Reimbursement

You are now able to find all balances corresponding to the upcoming redeployment distribution. Please check your balance, but before doing that, please read the following information:

- bHERMES utility tokens won't be directly distributed but the whole bHERMES token will be instead. So you will be able to claim and delegate all of your utility tokens. If there is anyone in a situation where an OTC happened or used another AMM than uniswap V3 to exchange them, please let us know so we can try and solve that.
- We won't be adding liquidity in behalf of anyone. So you need to add liquidity again if you wish. This applies to every kind LP: Uniswap V3, TALOS and Unified Liquidity Tokens (Balancer Composable Stable Pool LPs).
- Please read below to learn how reimbursement for trades after the first rescue transaction is being conducted.

## Swaps after rescue tx

Amounts related to these swaps have been gathered seperately and are not
reflected in the reimbursement balances currently made available.

## Balances

Here is a detailed list of files with balances and their respective content. Each file has a version with and without decimals. Look at the version with decimals for easier reading.

### Total per User

This is a list of all token balances to distribute per user:
- With decimals: [totalPerUserDecimals.json](./totalPerUserDecimals.json)
- Raw: [totalPerUser.json](./totalPerUser.json)

### Total per Token

This is a list of all token balances to distribute to users per token:
- With decimals: [totalPerTokenDecimals.json](./totalPerTokenDecimals.json)
- Raw: [totalPerToken.json](./totalPerToken.json)

### Token Totals

This is a list of the sum of all token balances to distribute to users:
- With decimals: [tokenTotalsDecimals.json](./tokenTotalsDecimals.json)
- Raw: [tokenTotals.json](./tokenTotals.json)