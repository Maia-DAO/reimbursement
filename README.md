# Reimbursement

> **NO ONE from the team will ever send any links or ask for any private information. If you receive any messages like that, please block them and report them to us.**

> **There is NO information and ZERO extra steps necessary for FULL reimbursement that are not included in this README. If your address is NOT ONE OF THE 16 LIST BELOW, you DO NOT HAVE TO DO ANYTHING. If you receive any messages like that, please block them and report them to us.**

You are now able to find all balances corresponding to the upcoming redeployment distribution. Please check your balance, but before doing that, please read the following information:

- bHERMES utility tokens won't be directly distributed but the whole bHERMES token will be instead. So you will be able to claim and delegate all of your utility tokens. If there is anyone in a situation where an OTC happened or used another AMM than uniswap V3 to exchange them, please let us know so we can try and solve that.
- We won't be adding liquidity in behalf of anyone. So you need to add liquidity again if you wish. This applies to every kind LP: Uniswap V3, TALOS and Unified Liquidity Tokens (Balancer Composable Stable Pool LPs).
- **Please read below to learn how reimbursement for trades after the first rescue transaction is being conducted.**

**If you have on of the following addresses please read [the next section ASAP](#swaps-after-rescue-tx):**

- 0xB307D426A34A72A94B32BCa5c5f0c8B36440Fa80
- 0xe29D8ac80c5dA2e8C23caf71f40af5d44E03c18D
- 0x1e121993b4A8bC79D18A4C409dB84c100FFf25F5

## Swaps after rescue tx

If you are one of the following addresses that had [net sells](./ecosystemSells.json), we want to revert your trades that happened after the rescue transaction so we can revert your losses. Please follow the instructions for your address or [reach out to us](#contact-us) so we can solve this issue.

If you sold, in order to revert the action, we need you to send back the WETH you received from the swap so we can send you back the original tokens you sold. If you don't have the WETH anymore, please reach out to us so we can try to find another solution.

### 0xCc74FC1C055Dc8996e1c33e47e3A7741691B9375

Please send `0.028926989241388257` ETH or WETH to `0xC26C6695aa3893b366ADB478475ABc9671e60047`. So we can send your `4972.83` sold HERMES tokens back to you.

tx: 0x655350a79af2149fa2494e5cec16524d080101cd85dd790bdf87934bc3060649

### 0xB307D426A34A72A94B32BCa5c5f0c8B36440Fa80

Please send `0.6494549344896502` ETH or WETH to `0xC26C6695aa3893b366ADB478475ABc9671e60047`. So we can send your `157016.8573825969` sold HERMES tokens back to you.

tx: TBD

### 0xe29D8ac80c5dA2e8C23caf71f40af5d44E03c18D

Please send `0.8762425216015506` ETH or WETH to `0xC26C6695aa3893b366ADB478475ABc9671e60047`. So we can send your `154302.56115201567` sold HERMES tokens back to you.

tx: TBD

### 0x1e121993b4A8bC79D18A4C409dB84c100FFf25F5

Please send `0.9492981395630838` ETH or WETH to `0xC26C6695aa3893b366ADB478475ABc9671e60047`. So we can send your `230000` sold HERMES tokens back to you.

tx: 0x22076a636520d5da37594044c43dce51ffa493347504459b6ca8ee0795aecb7c

### Ecosystem Buys and Sells

Amounts related to these swaps have been gathered seperately and can be verified in the following file:

- Buys: [ecosystemBuys.json](./ecosystemBuys.json)
- Sells: [ecosystemSells.json](./ecosystemSells.json)

A total of 9.14 ETH were spent acquiring/buying ecosystem tokens, this value will be returned to buyers and the ecosystem tokens bought aren't included in the reimbursement balance.

### Selling after the rescue, Unknown Smart Contracts and Arbitrageurs

There was a list of addresses that net sold after the rescue blocks. Because some addresses tried to take advantage of this situation. We removed them from the reimbursement list. **If your address is included in the following list, [PLEASE REACH OUT ASAP](#contact-us)**.

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

## Contact us

If you have any questions or need help, please reach out to us via a discord ticket or create an issue in this github repository.

- [Discord](https://discord.gg/maiadao)
- [Create issue in this repo](https://github.com/Maia-DAO/reimbursement/issues/new)

If you want to reach out to us via another form, you can send a tx to `0x00000000206ad3e31dfff979ccef06de72a9e027` with UTF-8 encoded data. We will try to reach out to you as soon as possible. 

If you are in contact with someone from the team, either through discord, telegram or twitter. You can also reach out to them directly. **Just please remember NO ONE from the team will ever send you any links or ask you for any private information. There is NO information and ZERO extra steps necessary for full reimbursement that are not included in this README. If you receive any messages like that, please block them and report them to us.**

## Reimbursement transactions

All transactions related to the reimbursement were made by the following address: `0x00000000206ad3e31DffF979Ccef06dE72a9E027`

Airdropped token 0xc557B3aA19F194303924B879d8fe085a67140AeE to 60 users, total amount 3463928856351128468437162:
- https://arbiscan.io/tx/0x607d8a6d3222dbcc879d8c094a2f930db1c8db96eb7cdaee7b1a1242f0dfac5a

Airdropped token 0xfD4785566143dc5108333de609ac4E8E0A52D00A to 10 users, total amount 7260098777:
- https://arbiscan.io/tx/0xbe99349e015803c3f591df00eea85f6beb8e22122a103f47a558ce05fcda227f

Airdropped token 0x390D857082b406f06b4d5c8377EC0aD36713aC33 to 9 users, total amount 4013164115:
- https://arbiscan.io/tx/0x9c4a348a4c2a17eeb54295629efcc06694d9d8d9f67ab77afa873032ed7c5de8

Airdropped token 0xE839360768881d1bECC05Bff2CC82176F4304D77 to 16 users, total amount 36052717249:
- https://arbiscan.io/tx/0x31fec867f44dab504fa7c339c7686569c9bdcc87f9510c0a2b069a74ceb69e28

Airdropped token 0xd7654107697D484c0070F6d71C699B6a1A9A9795 to 38 users, total amount 34138996923:
- https://arbiscan.io/tx/0x17dbbfb51583dd0cd998dca3d0320df02dc1baf9f801f7125fd4d3557428db5e

Airdropped token 0x87a7C6fE2D21781A66e9dbb9E60a66c5abE0FBbC to 116 users, total amount 939328549805930172295676:
- https://arbiscan.io/tx/0xb66a051833a773546c234804a86f9db2f79894dee971b85ebcc92895723407fe

Airdropped token 0x82ab9B2398217bF0200Bc8b18f2A995C1eFb975a to 5 users, total amount 41868829539:
- https://arbiscan.io/tx/0x23789d285fc7faa3d60b29d35762f452e1f77f282ebb3c6fb8285e23b3a0b799

Airdropped token 0xF7200F9c75c7D553a82F7400f5c8B431694e10bb to 25 users, total amount 1917047792639988594:
- https://arbiscan.io/tx/0xfd04352c62218cf24f1f62267a94239a815603db64052aa291bd51e421479022

Airdropped token 0x82aF49447D8a07e3bd95BD0d56f35241523fBab1 to 114 users, total amount 104625360024647403437:
- https://arbiscan.io/tx/0x3c474ef8dceb277e4d0ead3713eb18fd477ad501311109b3100d74a61b28ed08

Airdropped token 0x57D627b04e397Bd8c32C4aAA05Ec02AD20F0F033 to 1 users, total amount 1000000000:
- https://arbiscan.io/tx/0x90e9693ab22c62a29d9f3db5fb7ff0ef5ad5436cda93ca1772bde1c26b2a09d4

Airdropped token 0x916c46516302d743b02EE1075B9646d61Cc008c7 to 3 users, total amount 1905830234832630439:
- https://arbiscan.io/tx/0xb23026d843c37cec7bb3a2f5ab0d94de2a9e04d8c4d1f9e6c9c51ace5837e80c

Airdropped token 0x3878eA86aaeFE289134e9D433f932BCc9589Cff5 to 22 users, total amount 47472192976679150036:
- https://arbiscan.io/tx/0x907e36c98ec58151985a3b9c83fad7d8d81295f525822e7cfae85be5030e2b70

Airdropped token 0x8Ff53B87fEdde6A7dD8Ce4F94865eb826a616e1b to 12 users, total amount 8074981978538930463870:
- https://arbiscan.io/tx/0x926abfd04a8bba3d0a28143bc00bd52d0ee36225f0cd7fe9f4558fe05d544baf

Airdropped token 0xa293371eA7b1A227b7d3eEE0cD8FF8A65e30622c to 21 users, total amount 20035615207018286645:
- https://arbiscan.io/tx/0xc2cc4b5a444ba92ea41682596481d03236cb01e10ca9a71a5938394493fd8cc5

Airdropped token 0xf108A590BF86972B9BeaB03d6174AD7907554905 to 9 users, total amount 6851894567:
- https://arbiscan.io/tx/0x2399168282b3c8a2d61a0b97583ecad95f8e6c66bfdbe8529baaa5e0a51ad500

Airdropped token 0x6C4077a788043D877E4b76dd79dfc2DeF1804E04 to 2 users, total amount 5100000000000000:
- https://arbiscan.io/tx/0x6a671eb623e5a8c887312035176c099909c8f58f2e32c297d5e55dca68081d55

Airdropped token 0x6897f0Cf1c7c8Fb7dC565912dd64E63831995204 to 4 users, total amount 101113381528862792356:
- https://arbiscan.io/tx/0xcaa920451fb8927214e6128eb3396d050a4550bc000a111621061ad4df5e9ca6

Airdropped token 0x3aa9Be7e0Dac63A03C99FE247e0cF8CB6fd29363 to 20 users, total amount 23710839340264743054:
- https://arbiscan.io/tx/0x8b398ba66ae305693862bbc7b45399496fd930d5efc88f81da0289f5a2d8d5e9

Airdropped token 0xaf88d065e77c8cC2239327C5EDb3A432268e5831 to 14 users, total amount 86874366869:
- https://arbiscan.io/tx/0x84afe5523f2fcd4bfc77736f2ec390af8caeff31e4a81b7d55e3f189c08fe4a0

Airdropped token 0x57D627b04e397Bd8c32C4aAA05Ec02AD20F0F033 to 40 users, total amount 25386092711:
- https://arbiscan.io/tx/0xaa9081f435cec4fb7e526d71c3007a202fcec9304fef1abd71aae912d2a32e79

Airdropped token 0xb654cB02aB0318985B10CCE2C0027Ef36a3DB55B to 53 users, total amount 6132717654534677636651:
- https://arbiscan.io/tx/0xfb000619398cdf13389e3159fd6a71875b928ba336c5d9f29d63b26b975a117c

Airdropped token 0x3878eA86aaeFE289134e9D433f932BCc9589Cff5 to 5 users, total amount 2151230032508237255:
- https://arbiscan.io/tx/0xd54c622705098dac728b225362655d963b189c55e38c592cf022251e76110eba

Airdropped token 0xf7ab5B47112A5bCA13C9F50C2Cf25c78bAD4bd84 to 18 users, total amount 173910029593523949736864:
- https://arbiscan.io/tx/0xa06f49ee12ab07a42f6c95a7a711d7057bbd78e86a033dcb856a7d25b42a216d

Airdropped token 0xc5324a5F6AC10Ad356BC04d84bcd3c18ac824076 to 46 users, total amount 3479650328399:
- https://arbiscan.io/tx/0xb5130764710f031c09b38397a74b9dad8e31541b601a96385e79bf55b8252de7

Airdropped token 0x70Ed9e9fBc9f6a8A159bcE0485a1D0759f5e8c72 to 28 users, total amount 61108086549913363577:
- https://arbiscan.io/tx/0xeab1e7df82fe90d18e2d64625689f6a9ea4a9079ff699a0db6f7d79a456b8c2e

Airdropped token 0x0f2944ff2566Aa405ea7A9522ff5cD0cD5EF1797 to 10 users, total amount 28885507578:
- https://arbiscan.io/tx/0x70d6140620274594df2eb21f0f022aa8122a3a0ae7d17638886868b086e96240

Airdropped token 0xE18b9c05E3Bb22652812e3eD43459Ad8A8bB6A70 to 11 users, total amount 2416097950:
- https://arbiscan.io/tx/0xd0504180340494eebe216a0c947b3c2f7f07a3edeba3c795630a17c852276738

Airdropped token 0xFd086bC7CD5C481DCC9C85ebE478A1C0b69FCbb9 to 10 users, total amount 46772985792:
- https://arbiscan.io/tx/0xa291a67373b47fb25c7b406298063f1a0e742af858c9ba84b0cb069b89660427
