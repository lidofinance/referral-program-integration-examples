# Lido Referral Program

Earn rewards and make Ethereum more secure by spreading the benefits of staking with Lido.

## How to participate

To participate in the Lido Referral Program, simply go to [Lido Referral Program page](https://referral.lido.fi/), generate your referral link and share it with others.

## Referral link

Your referral link will look something like this `https://stake.lido.fi/?ref=0x0000000000000000000000000000000000000000`. It leads to the [Lido Staking app](https://stake.lido.fi/) with your address as the `ref` search parameter. Whenever someone stakes ETH with your link, your address will be passed as the referral address into the [Lido contract](https://etherscan.io/address/0xae7ab96520de3a18e5e111b5eaab095312d7fe84).

## Sharing your link

You are free to share your link whichever way you want: DMs, social media, a piece of paper, broadcast it over radio. You can also choose to use Lido Referral Program banners on your website or even embed the Lido Staking App via the `iframe` tag.

### Adding a Lido banner to your website

- Add an `<a>` tag
- Specify your link as the value of the `href` attribute
- [optional] add `target="_blank"` and `rel="noopener noreferrer"` attributes to safely open the link in a new tab
- Pick any banner you like from [banners](/banners), copy the raw SVG code
- Paste it inside your `<a>` tag
- That's it!

See banner examples [here](/examples/banners).

### Embedding the Lido Staking App

- Add an `<iframe>` tag
- Specify `title` attribute, e.g. `title="Lido Staking App"`
- Specify your link as the value of the `src` attribute
- [optional] add `width="360"` and `height="500"` attributes to make the embedded app bigger
- You're all done!

See the embedded staking app example [here](/examples/iframe).
