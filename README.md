🗳️ dVoting – Decentralized Voting System using Blockchain
🚀 Overview

dVoting is a decentralized and transparent voting system built on the Ethereum blockchain.
It ensures secure, tamper-proof elections by leveraging smart contracts to manage candidate registration, vote casting, and result declaration — eliminating the need for centralized authorities.

🎯 Features

✅ Blockchain-based voting: Votes are recorded on the Ethereum blockchain for full transparency.
✅ Smart contract security: Prevents vote manipulation and duplication.
✅ Role-based access: Separate views for Admin (election authority) and Voters.
✅ Real-time results: Automatic vote counting and live result updates.
✅ Simple UI: User-friendly frontend built with HTML, CSS, and JavaScript.

⚙️ Tech Stack
Layer	Technology Used
Smart Contracts	Solidity
Blockchain Network	Ethereum (Ganache Local Network)
Development Framework	Truffle
Frontend	HTML, CSS, JavaScript, Web3.js
Wallet Integration	MetaMask
🧩 Project Structure
dVoting/
│
├── contracts/         # Solidity smart contracts
├── migrations/        # Truffle migration scripts
├── src/
│   ├── js/            # Frontend logic (Web3 integration)
│   ├── dist/          # Bundled frontend files
│   ├── css/           # Stylesheets
│   └── index.html     # Main webpage
├── test/              # Smart contract test cases
├── truffle-config.js  # Truffle network configuration
└── package.json       # Project dependencies

🛠️ Setup Instructions
1️⃣ Install Dependencies

Make sure Node.js, npm, and Truffle are installed:

npm install -g truffle
npm install

2️⃣ Start Local Blockchain

Open Ganache GUI or run:

ganache-cli

3️⃣ Compile and Deploy Smart Contract
truffle migrate --reset

4️⃣ Run the Frontend

Bundle the JavaScript files using Browserify:

browserify ./src/js/app.js -o ./src/dist/app.bundle.js


Then open index.html in your browser.

🔗 MetaMask Configuration

Network Name: Localhost 8545

New RPC URL: http://127.0.0.1:8545

Chain ID: 1337

Currency Symbol: ETH

Import one of your Ganache accounts into MetaMask for transactions.

🧠 Smart Contract Functionalities
Function	Description
addCandidate()	Admin adds new candidates
authorizeVoter()	Admin authorizes voters
vote()	Voter casts a vote
endElection()	Ends voting and declares results
getResult()	Fetches total votes per candidate

Preview:

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/4fd25469-583c-4476-97d6-dae31ee6e58a" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/c289f6ce-ceae-47ed-a111-0c8e93bdea78" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/e961d2ca-9b71-4aeb-b0e2-7b3afadc359c" />



