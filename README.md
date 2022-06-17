# Welcome to HMM NFT 💎

### Reviewing the website

1. Visit https://hmm-nft.xyz/
2. Try to break the site. 
3. Minting will not work, because I have not togged sales, so DO NOT MINT cuz the gas fees will be very high
4. Let Sticky know in Discord what you find

### Reviewing the code

1. Review the code so you can see how the website is made
2. The main "website" is in `/src/App.js /` which is built in React
3. The App.Js file pulls in other directories to interact with the blockchain, like 

> import { useDispatch, useSelector } from "react-redux";
> import { connect } from "./redux/blockchain/blockchainActions";
> import { fetchData } from "./redux/data/dataActions";
> import * as s from "./styles/globalStyles";
> import styled from "styled-components";

4. You dont need to understand all of it, but just look for anything that looks amiss or like it might not work
5. Let Sticky know in Discord what you find

### Creating a sandbox environment (Optional)

1. Copy this code into your local environment
2. Create a new netlify account (Free version is fine)
3. Once you have signed up, create a new project from the github repo
4. Deploy to the netlify.com domain they assign for you
5. Try to break things :) 



