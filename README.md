# radequate

[[Team Logo ] (https://www.github.com/Rise-In/example readMe/blob/main/Example_logo%20.png

Project Visual

## individual

My name is Ruddraksh Parida, a B.Tech student at Jamia Hamdard with a passion for technology and problem-solving. I’ve built skills in C++, C, Python, and Data Science, and recently enhanced my development abilities by participating in the Rise In Full Stack Bootcamp. Beyond coding, I enjoy gaming, traveling, and staying active through sports like cricket, basketball, badminton, and long jump. I’m driven by curiosity and a desire to build solutions that make a real impact.

## Description

Radequate is a full-stack decentralized application built on the Crypto Blockchain. It focuses on earthquake preparedness by monitoring seismic activity in real time. The app includes a powerful and user-friendly dashboard that displays current seismic data and potential earthquake risks. Using blockchain ensures that the data is transparent, tamper-proof, and accessible to all. When the system detects seismic patterns that may lead to an earthquake, it automatically sends SMS alerts to nearby users, helping them take timely action. Radequate aims to combine technology and decentralization to save lives by offering early warnings and trustworthy data in a simple, secure, and efficient way.

## Vision

At Radequate, our vision is to build a world where timely information saves lives. By using blockchain technology to detect and share seismic activity in a secure, decentralized way, we aim to warn people before disaster strikes. Our goal is to provide reliable alerts through SMS so communities can act fast and stay safe. With a clear dashboard and trusted data, Radequate empowers people to make informed decisions during emergencies. We believe that early warnings can prevent loss and create a safer future for everyone—because every life matters.

## Project Roadmap / Future Plans

Radequate – Software Development Plan

1. Smart Contract Design & Planning

--> Define key smart contract variables:

a) seismicData (struct with location, magnitude, timestamp)

b) alerts (mapping of location to alert status)

c) registeredUsers (mapping of address to phone number)

d) Define roles: admin (data submitter), users (alert recipients)

2. Smart Contract Development

--> Functions to implement:

 a) submitSeismicData(location, magnitude, timestamp) – for authorized sources

 b) evaluateRisk() – analyzes data and triggers alert status

 c) registerUser(phoneNumber) – users opt-in for alerts

 d) getAlertStatus(location) – check if an alert is active

3. Blockchain Integration (Backend)

a) Connect smart contracts using Web3.js or Ethers.js

b) Integrate with SMS API (like Twilio) to send alerts based on smart contract events

4. Front-End Dashboard Development

 i)Real-time data visualization of seismic activity

ii)User registration and phone number input

iii)Map showing active alerts and historical data

5. Testing & Security Review

Unit testing for smart contracts

Simulate seismic events to validate alert triggers

Audit smart contract for vulnerabilities

Deployment & Launch

Deploy smart contract on Crypto Blockchain

Host front-end on a decentralized platform (e.g., IPFS)

Go live and onboard users securely

## The Tech We Use

Rust and Web3

## Smart Contract Address

XXXXXXXXXX

## Setup Environment

Sure! Here's a simple and clear draft of a GitHub README Installation section for your Radequate project:

🛠️ Installation Guide – Radequate
Follow the steps below to set up the Radequate project locally:

1. Clone the Repository
bash

Edit
git clone https://github.com/your-username/radequate.git
cd radequate

2. Install Dependencies
Backend (Smart Contracts & Server)
bash
Copy
Edit
cd backend
npm install
Frontend (Dashboard)
bash
Copy
Edit
cd ../frontend
npm install

3. Configure Environment Variables
Create a .env file in both backend/ and frontend/ directories with necessary keys:

For example (backend):

ini
Copy
Edit
TWILIO_ACCOUNT_SID=your_sid
TWILIO_AUTH_TOKEN=your_token
BLOCKCHAIN_PROVIDER_URL=https://your-node-url
CONTRACT_ADDRESS=deployed_contract_address

4. Run the Smart Contract Locally (Optional for Dev)
If using Hardhat:

bash
Copy
Edit
cd backend
npx hardhat node
npx hardhat run scripts/deploy.js --network localhost

5. Start the Project
Backend
bash
Copy
Edit
cd backend
npm run start
Frontend
bash
Copy
Edit
cd ../frontend
npm run dev
✅ Done!
Now open your browser at http://localhost:3000 to see the dashboard.
