---
id: 115
period: 3
title: AlgoMinter - NFT Image Generator
author: Zachary Minner (@1forh)
discussions-to: https://github.com/algorandfoundation/xGov/pull/115
company_name: minner.algo
category: dApps
focus_area: NFT
open_source: Yes
amount_requested: 40000
status: Final
---

## Abstract
I am developing an app that allows users to generate NFT collections utilizing user-uploaded image data (layers) as well as customizations that offer fine-grain control over the generated images. 

The dApp will allow the user to upload layer files, set rules for specific traits, preview images based on collection size, and then either download the images or mint them straight to the Algorand blockchain using ARC69, ARC19 specifications.

## Team
My name is Zachary Minner. I've been a Web Developer for 10+ years. I've built over 100+ websites/apps through my day job as well as over 10 different websites for Algorand NFT collections.

## Experience with Algorand
For the last 2+ years, I've been building an NFT community called Shitty Kitties with my wife Haley. Shitty Kitties is more than just NFTs. We have many utilities through our website and our Discord channel that offer users a unique and Shitty experience.
- Wallet utilities like Mass Add and Mass Send
- Entertainment/Rewards utilities like casino, raffles, and vending machine
- Profile look-up 
- and more

I've also built over 10 websites/dApps for different Algorand collections as well as Discord bots, exactly to the collections/creator specifications. 

I build dApps using Next.js/TypeScript and I'm very familiar with the JavaScript AlgoSDK as well as AlgoNode APIs.

## Present Proposal
The Image Generator will be the main feature of the app. A user will define "Layers" (ie. Backgrounds, Hats, Accessories) for their project. For each layer, the user can upload as many images as they want to represent different "traits" for that layer.

All of the layer, trait, and image data is stored in a database in the browser's IndexedDB.

Using all of the different layers, trait images, and other settings the user defined (like collection size, collection name, and trait rarities), images will be generated for the user to preview right on the website. This will give them the ability to do QA on the generated images so much easier than they would be able to when using a script to generate them.

There will also be a handful of useful tools that the user can use to save their favorite generated images for later generations, create 1/1s within your randomly generated images, and more. 

Once the user is satisfied with the generated images, the site will allow them to download all of the images in a zip file as well as give the user a JSON file of the metadata necessary for the ARC69 specification when minting the NFTs. This will be available to all users.

The app will allow users to pay a modest monthly fee in ALGO to gain access to some paid features.

As a paid feature, users can mint the Algorand NFTs right from the website. Once the user is satisfied with the generated images, the site will offer them the option to Mint them as ARC69 and/or ARC19 Algorand NFTs.

## Future Blueprint
I am building an MVP version first so that I can release it quicker and get feedback from the community. However, I have a few ideas that I'd like to implement at a future time.
- Cloud Storage for data/images
- Allow uploading gifs to generate NFT gifs
- Implement feedback from the Algorand community

## Benefits for the community
I think there's a huge gap missing in this area. There's a good amount of Algorand users trying to make generative NFT collections that don't have experience with Python or other languages needed to write an NFT Image Generation Script.
This task is often outsourced to one of the amazing developers on Algorand, at the cost of the collection creator. This site would allow anyone to design and generate their own generative Algorand NFT Collection with ease.

I know that there are a few NFT Image Generator options being developed but I think competition breeds innovation and creativity, so one more won't hurt at all. 

AlgoMinter will offer a sleek UI, fast and efficient data storage, and my undying support for bugs and later updates to the dApp.

## Additional information
I have a proven track record of getting shit done and done well. Building websites/apps and interacting with the Algorand community through Shitty Kitties are some of my greatest passions. I love the work I do here and hope to continue building cool shit for Algorand for years to come.

If you'd like to check out any of the existing stuff I've built, you can find some below.

- Shitty Kitties https://www.shittykitties.art - Many utilities and helpful features for Shitty Kitty holders
- Shitty Cities https://www.shittycities.art - Companion collection that allows holders to collect and update isometric City NFTs
- How to ALGO NFT https://www.howtoalgonft.com - Helpful information on all sorts of Algorand NFT topics. Working on redesigning and rebuilding this right now.
- NFT Missions https://www.nftmissions.com - Aggregates Adventure/Mission style staking from different Algorand NFT collections
