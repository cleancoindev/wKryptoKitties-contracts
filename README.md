Crypto Collectibles Series - 
[Cats](https://github.com/cryptocopycats/contracts) · 
[Punks](https://github.com/cryptopunksnotdead/contracts)


# CryptoKitties Blockchain Contracts / Services

_Code on the Blockchain - Electronic Contract Scripts_



## /kitties - Core CryptoKitties

Etherscan

- KittyCore, see contract address [`0x06012c8cf97bead5deae237070f9587f8e7a266d`](https://etherscan.io/address/0x06012c8cf97bead5deae237070f9587f8e7a266d#code)

> The genetic combination algorithm is kept seperate so we can open-source all of
> the rest of our code without making it _too_ easy for folks to figure out how the genetics work.
> Don't worry, I'm sure someone will reverse engineer it soon enough!
>
> -- Commentary from the CryptoKitties source code

**Update 2019**  The sooper-sekretoo GeneScience contract
with the "magic" mixGenes function is now open source
with inline running commentary. Thanks!

- GeneScience, see contract address [`0xf97e0a5b616dffc913e72455fde9ea8bbe946a2b`](https://etherscan.io/address/0xf97e0a5b616dffc913e72455fde9ea8bbe946a2b#code)



> The auctions are
> seperate since their logic is somewhat complex and there's always a risk of subtle bugs. By keeping
> them in their own contracts, we can upgrade them without disrupting the main contract that tracks
> kitty ownership.
>
> -- Commentary from the CryptoKitties source code


- SaleClockAuction, see contract address [`0xb1690c08e213a35ed9bab7b318de14420fb57d8c`](https://etherscan.io/address/0xb1690c08e213a35ed9bab7b318de14420fb57d8c#code)
- SiringClockAuction, see contract address [`0xc7af99fe5513eb6710e6d5f44f9989da40f27f26`](https://etherscan.io/address/0xc7af99fe5513eb6710e6d5f44f9989da40f27f26#code)




For more see [**Inside the CryptoKitties Blockchain Contracts / Services »**](kitties)



## /wrapped - Wrapped CryptoKitties (WCK, WG0, WVG0)


> $WCK wrapped cryptokitties; its actually backed by a digital cat;
> where as other coins are backed by hot-air.


Etherscan

- WrappedCK (WCK), see contract address [`0x09fe5f0236f0ea5d930197dce254d77b04128075`](https://etherscan.io/address/0x09fe5f0236f0ea5d930197dce254d77b04128075#code)
- WrappedG0 (WG0), see contract address [`0xa10740ff9ff6852eac84cdcff9184e1d6d27c057`](https://etherscan.io/address/0xa10740ff9ff6852eac84cdcff9184e1d6d27c057#code) - Gen 0 Variant
- WrappedVG0 (WVG0), see contract address [`0x25c7b64a93eb1261e130ec21a3e9918caa38b611`](https://etherscan.io/address/0x25c7b64a93eb1261e130ec21a3e9918caa38b611#code) - Virgin Gen 0 Variant


For more see [**Inside the Wrapped CryptoKitties (WCK, WG0, WVG0) Blockchain Contracts / Services »**](wrapped)

