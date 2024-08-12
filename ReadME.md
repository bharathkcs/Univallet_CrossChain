# Univalet

Univalet is an innovative cross-chain cryptocurrency wallet designed to simplify the management of digital assets across multiple blockchains. Our platform provides users with a comprehensive set of features, including the ability to send, receive, swap, borrow, and repay various tokens seamlessly within a secure and user-friendly environment. Leveraging the power of Analog Stacks, Univalet offers true cross-chain interoperability, allowing users to perform transactions across Ethereum and Polygon networks effortlessly.

## Video Demonstration

You can watch the video demonstration of the Univallet app here:

[![Univallet App Video](https://img.youtube.com/vi/oCoDixVuQic/0.jpg)](https://www.youtube.com/watch?v=oCoDixVuQic)


## Key Features

- **Seamless Token Swaps:** Swap tokens between Ethereum and Polygon with ease.
- **Borrow and Repay:** Borrow assets with collateral and manage repayments directly from the wallet.
- **Send and Receive:** Instantly send and receive tokens across multiple networks.
- **Token Purchases:** Buy tokens directly within the app.
- **Transaction History:** Keep track of all your transactions with a transparent and detailed history.

## Login Information

You can either register as a new user or use the following login credentials to access Univalet and explore all its features:

- **Gmail:** kcsb28@gmail.com | **Password:** 123456
- **Gmail:** bentelyr52@gmail.com | **Password:** 123456
- **Gmail:** varshadhkumar@gmail.com | **Password:** 123456
- **Gmail:** vikramcoir98@gmail.com | **Password:** 123456

## Setup Instructions

To start the smart contract server, please follow these steps:

1. **Run Ganache CLI:**
   ```bash
   ganache-cli
   ```

2. **Deploy the smart contracts for Ethereum and Polygon networks:**
   ```bash
   truffle migrate --reset --network development --migrations_directory migrations/ethereum
   truffle migrate --reset --network development --migrations_directory migrations/polygon
   ```

3. **Start the front-end:**
   Navigate to the front-end directory, and run:
   ```bash
   npm install
   npm run dev
   ```

## MongoDB Setup

Please ensure that you add the following URI to your MongoDB configuration and start the connection. This is necessary for enabling user login and registration:

- **Link:** `MONGO_URI = mongodb+srv://chatgptbhav:HcriMZxOpIGsU3g8@cluster0.u9uhzi7.mongodb.net/hackathon?retryWrites=true&w=majority&appName=Cluster0`

**Note:** Due to the large file size of our project, we have utilized Git LFS to upload the project as a ZIP file. Unfortunately, we cannot share the code directly via GitHub or the Hackathon portal.
