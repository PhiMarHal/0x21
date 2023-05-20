# 0x21

DeFi resources.

## Wallet Providers

*Standard wallets, controlled with seed phrases or private keys.*

### Browser Extensions

Metamask - https://metamask.io/

Rabby - https://rabby.io/

Taho - https://taho.xyz/ (prev Tally Ho)

### Online

MyCrypto - https://app.mycrypto.com/dashboard

MyEtherWallet - https://www.myetherwallet.com/

### Local

0xFrame - https://frame.sh/

MyCrypto Desktop - https://download.mycrypto.com/

## Smart Wallets

*Smart contract wallets, with advanced features like account abstraction.*

Safe - https://app.safe.global (previously Gnosis Safe)

>A Safe is a multisig wallet. If set up as 1/1, it enables multistep transactions and easy key rotation.

Argent - https://www.argent.xyz/ (mobile only)

## Aggregators

DefiLlama - https://swap.defillama.com

>Aggregates aggregators. Time-efficient choice in most cases

CowSwap - https://swap.cow.fi

>Protected against frontrunning. Execution is delayed.

Swapr - https://swapr.eth.limo

## MEV Protection

- lowering slippage to <=0.1% will work most of the time on liquid tokens.
- use limit orders on Matcha or 1inch
- use natively MEV protected dexes like CowSwap
- trade on Arbitrum or Optimism, their sequencers are currently centralized (no frontrunning from thirdparties)
- use RPCs:

MEVBlocker: https://mevblocker.io/

>Focused on fast execution. Refunds 90% of any backrunning opportunity.

MEVBlocker offers alternate endpoints for different purposes
>- with revert protection: https://rpc.mevblocker.io/noreverts
>- without refunds, but with revert protection and full privacy: https://rpc.mevblocker.io/norefunds
>
Flashbots Protect: https://docs.flashbots.net/flashbots-protect/rpc/quick-start

>Protects against reverts.

Flashbots Protect also offers other endpoints, similar to MEVBlocker: https://docs.flashbots.net/flashbots-protect/rpc/mev-share#examples

## Analytics

Coingecko - https://www.coingecko.com

DefiLlama - https://defillama.com

### Avalanche

Glacier - https://www.glacier.exchange/

SoliSnek - https://www.solisnek.finance/swap

### Canto

Velocimeter - https://www.velocimeter.xyz/swap
