# nft-radar
Personal NFT listing tracker

I’m building a small tool to keep an eye on NFT collections I follow
on OpenSea.

It checks new listings against my price and trait filters and sends
me a Telegram message when something matches, so I don’t have to
keep refreshing collection pages.

The project runs on my computer. It uses OpenSea’s Stream API for
listing events and the REST API for collection data and traits.
It only sends notifications — purchases are made manually on OpenSea.
