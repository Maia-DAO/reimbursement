# Reimbursement

You are now able to find all balances corresponding to the upcoming redeployment distribution. Please check your balance, but before doing that, please read the following information:

- bHERMES utility tokens won't be directly distributed but the whole bHERMES token will be instead. So you will be able to claim and delegate all of your utility tokens. If there is anyone in a situation where an OTC happened or used another AMM than uniswap V3 to exchange them, please let us know so we can try and solve that.
- We won't be adding liquidity in behalf of anyone. So you need to add liquidity again if you wish. This applies to every kind LP: Uniswap V3, TALOS and Unified Liquidity Tokens (Balancer Composable Stable Pool LPs).
- **Please read below to learn how reimbursement for trades after the first rescue transaction is being conducted.**

### Selling after the rescue, Unknown Smart Contracts and Arbitrageurs

There was a list of addresses that net sold after the rescue blocks. Because some addresses tried to take advantage of this situation. We removed them from the reimbursement list. **If your address is included in the following list, PLEASE REACH OUT ASAP** to us via a discord ticket or create an issue in this github repository.

- 0x00000000CfE3369BcdBC76071bA6e0A4e0Fe98Bd
- 0x277CcbFc3Cca490E63F60F836758ce5823944518
- 0x2BA981b9eBB03b0b9D7454d236D6321824DFC302
- 0x429D51D948c75b8d029a150744f5914a1573eAB4
- 0x474E51f692a724CD054BcaA07cCd094c9C7D93a0
- 0x5F515F6C524B18cA30f7783Fb58Dd4bE2e9904EC
- 0x60ca5DEf792E7528f8fF48b7aea60C1E2234294B
- 0x9D3FBdb90C41D9aaA2100148c5C69d65bCae6fB0
- 0xb01F8f528702d411d24c9bB8Cc0e2ffF779ec013
- 0xD2584fb1f05f3130cdffF35928BC2d42afa59972
- 0xE37e799D5077682FA0a244D46E5649F71457BD09
- 0xf238d4353246948eCDc3F3252ae939FE5234E145

## Swaps after rescue tx

Amounts related to these swaps have been gathered seperately and can be verified in the following file:

- Buys: [ecosystemBuys.json](./ecosystemBuys.json)
- Sells: [ecosystemSells.json](./ecosystemSells.json)

A total of 9.14 ETH were spent acquiring/buying ecosystem tokens, this value will be returned to buyers and the ecosystem tokens aren't including reimbursement balance.

If you sold, in order to revert the action, we need you to send back the WETH you received from the swap so we can send you back the original tokens you sold. If you don't have the WETH anymore, please reach out to us so we can try to find another solution.

## Balances

Here is a detailed list of files with balances and their respective content. Each file has a version with and without decimals/names. Look at the version with decimals for easier reading.

### Total per User

This is a list of all token balances to distribute per user:
- With decimals and names: [totalPerUserDecimalsWithNames.json](./totalPerUserDecimalsWithNames.json)
- With decimals: [totalPerUserDecimals.json](./totalPerUserDecimals.json)
- With names: [totalPerUserWithNames.json](./totalPerUserWithNames.json)
- Raw: [totalPerUser.json](./totalPerUser.json)

### Total per Token

This is a list of all token balances to distribute to users per token:
- With decimals and names: [totalPerTokenDecimalsWithNames.json](./totalPerTokenDecimalsWithNames.json)
- With decimals: [totalPerTokenDecimals.json](./totalPerTokenDecimals.json)
- With names: [totalPerTokenWithNames.json](./totalPerTokenWithNames.json)
- Raw: [totalPerToken.json](./totalPerToken.json)

### Token Totals

This is a list of the sum of all token balances to distribute to users:
- With decimals and names: [tokenTotalsDecimalsWithNames.json](./tokenTotalsDecimalsWithNames.json)
- With decimals: [tokenTotalsDecimals.json](./tokenTotalsDecimals.json)
- With names: [tokenTotalsWithNames.json](./tokenTotalsWithNames.json)
- Raw: [tokenTotals.json](./tokenTotals.json)
