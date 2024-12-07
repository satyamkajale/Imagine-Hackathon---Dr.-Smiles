# Dr Smiles: Earn immutable digital currency using smiles!

A cutting-edge Web3 application that analyzes your smile and rewards real happiness with USDC crypto(Built on top of Coinbase Development Platform). 

## How It Works

1. 📸 Click a picture of your smile
2. 🤖 AI analyzes your smile's authenticity
3. ✨ Real Smiles (score > 3) earn 0.001 rewards
4. 🌐 Best smiles are stored on-chain.

## Technical Stack

### Frontend
- Next.js
- TypeScript
- Tailwind CSS
- Privy
- Ethers.js

## Smart Contract Features

- Decentralized smile analysis via Openputer AI Oracle (built on Coinbase Development Platform)
- Real-time reward distribution
- Transparent scoring system
- Gas-optimized operations on Base Network

## Technical Details

### Blockchain Integration
- Compatible with Base Network
- Openputer AI Oracle (based on AgentKit) for decentralized smile analysis
- Gas-efficient smart contract design

### Security
- Secure wallet authentication
- Protected image storage
- Rate limiting on submissions
- Sybil resistance through wallet verification

## Features
- Wallet authentication - Privy
- Camera Feature - Selfie
- AI smile Analysis
- Gallery with Winning smiles
- Responsive Design
- Community funding


## Process of running it in your own device

How to Run This Project
### Step 1 - Clone the Repository

### Step 2 - Set Up Environment Variables:

Add the following in .env file located in the root of the project.
- NEXT_PUBLIC_PRIVY_APP_ID=your-privy-app-id
- NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
- NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key

Replace placeholders with actual values:
- Privy App ID: From Privy Dashboard.
- Supabase URL and Anon Key: From your Supabase Project Settings.

### Step 3 - Install Dependencies:
npm install

### Step 4 - Start the Development Server:
npm run dev

### Step 5 - Access the app at http://localhost:3000.

### Troubleshooting Tips
- Ensure the .env file is in the root directory, formatted correctly, and variables are properly defined.
- Restart the development server after updating environment variables.
- Use console.log to verify environment variable values during debugging.
- This streamlined process should help you get the project running successfully. 
