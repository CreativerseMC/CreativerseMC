# Welcome to the Creativerse

### Public Server
We host a public server on Java edition Minecraft 1.17.1 at **137.74.246.121:25589**

This is hosted using the Kovan testnet, you can get Kovan testnet ETH at https://faucets.chain.link/kovan

### Running your own Creativerse server
You need to run a Bukkit/Spigot server. I recommend using [PaperMC](https://papermc.io/). Use a 1.18 version.

All you need are 4 plugins:
- [Worldedit](https://dev.bukkit.org/projects/worldedit)
- [AsyncWorldEdit](https://www.spigotmc.org/resources/asyncworldedit.327/)
- [PlotSquared v6](https://www.spigotmc.org/resources/plotsquared-v6.77506/)
- [Creativerse](https://github.com/CreativerseMC/CreativerseMC-Plugin/releases)

You will need to run an Ethereum node, I recommend using [Alchemy](https://www.alchemy.com/). You will also need to run an IPFS node, I recommend running this locally. You also need an API key from [NFT.Storage](https://nft.storage)

Run the server to generate the config files, shut it down and go to `plugins/Creativerse/config.yml`. Edit the config's `NFT-Storage-API-Key`, `ETH-Node`, and `IPFS-Node` with your respective keys and urls. Leave the other config parameters as default unless you know what you are doing.


### Source Code
All the source code for the plugin and the smart contract is public at https://github.com/CreativerseMC/CreativerseMC-Plugin

The website used to facilitate ETH transactions also has its source code public at https://github.com/CreativerseMC/Creativerse-React-Website

You can also see a base pure html/javascript version of the website at https://github.com/CreativerseMC/CreativerseMC.github.io

# Socials
- Website: https://CreativerseMC.com
- Twitter: https://twitter.com/CreativerseMC
- Discord: https://discord.gg/FHAZcVfxDn
- Reddit Account: https://www.reddit.com/user/CreativerseMC
