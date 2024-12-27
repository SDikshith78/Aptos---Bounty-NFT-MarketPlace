-----------------------------------   Aptos-related project ---------------------------------------

-----------------------------------   Bounty - Level Up Your Aptos NFT Marketplace dApp (Fullstack) ---------------------------------------

Video Demo link: Click to see
paste the link here

------------------------------------------------------------------ PROJECT OVERVIEW -------------------------------------------------------
As part of our development on the Aptos blockchain, we've built an NFT Marketplace that allows users to interact with NFTs through buying, selling, supporting creators, and transferring. 
The core logic is managed by a Move smart contract for blockchain operations, while the frontend provides an engaging user interface. 

Bounty Project Overview: This project integrates the NFT Marketplace smart contract with a TypeScript and React frontend, offering a seamless experience for users to manage their NFT collections and 
engage with the marketplace.

----------- Technologies Used ---------------
Frontend:
* React.js: Utilized for building the user interface with dynamic updates.
* TypeScript: Employed for type safety across the application, with all components using .tsx file format.
* Lottie-react: For showcasing success and failure animations post-transaction.

UI & Styling:
Custom CSS: Applied for specific animations and styling, like hover effects on buttons for actions like "Buy" or "Support". and added background colors to MarketPlace and NFT Collection.

Backend:
* Move: The smart contract for the marketplace is written in Move(.move file), deployed on the Aptos Testnet at 0x223d508f051f5869e232658de4a25c493813273319b5130ae54838c609be630d.

Issues We Faced & Solved:
* Wallet Payement and initialize Errors: Initial issues with were like approving and initialize. But then got to know that our profile is not wiped out even though showing/getting "Generic Error",
                                          it is there and working fine we can proceed with transfer, support etc..
* Lottie Animations: Managed to integrate Lottie animations for success and failure payment process, ensuring they display for an adequate duration without TypeScript errors.

* I also wanted to add Tilt.js animation in frontend(typerscript) but it is not working.

Note:
* Transaction/Network Fees: Handled transactions for buying, selling, supporting, and transferring NFTs, ensuring appropriate fee management.
* State Management: Used React's local state for managing NFT filters, sorting, and transaction status, opting for simplicity over complex state management solutions.

Features:
* Connect Wallet: Users must connect their wallet (like Petra) to interact with the marketplace functionalities.
* NFT Minting: Users can mint new NFTs directly from the interface.
* NFT Marketplace: Displays NFTs for sale, with options to filter by rarity and price range, and sort by price.
* Blockchain Integration: All marketplace actions leverage the NFTMarketplace.move contract for on-chain execution.
* Wallet Integration: Users can connect or disconnect their Aptos wallets to engage in transactions.
* NFT Transfer: Allows users to transfer NFTs from their collection to another address with a modal for recipient input like NFT id.
* Support Creators: Users can tip creators who have minted NFTs, using the tip_creator function from our smart contract.
* Animations for Feedback: Success and failure animations are shown using Lottie for transaction outcomes.
*UI Enhancements: 
- Hover Effects: Added to buttons for buying and supporting etc.., enhancing user interaction.

Conclusion:
In conclusion, our Aptos NFT Marketplace project successfully merges blockchain technology with a user-friendly frontend, providing a robust platform for NFT interactions. We've navigated through various technical challenges, including wallet integration and animation implementation, to deliver a marketplace where users can mint, buy, sell, support creators, and transfer NFTs with ease. The integration of Move smart contracts with a React and TypeScript frontend ensures both security and performance, while the addition of visual feedback through Lottie animations enhances user engagement. This project not only showcases the capabilities of the Aptos blockchain but also sets a foundation for future enhancements and features in the NFT space.
