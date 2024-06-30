[!WARNING] Attention please! This code is used to extract blockchain and crypto developers wallet keys, please don't run it on your machines, be careful


[!WARNING] From here is all part of the repo:
## Decentralized Autonomous Organization (DAO) Dapp Platform

**Found the security issue:**

Is a obfucated  piece of code on the routers

**Project Overview:**

A web-based decentralized voting platform for DAOs, where members can propose, discuss, and vote on decisions in a secure and transparent manner.

**Key Features:**

- User registration and authentication.
- Smart contracts for secure voting and proposal management.
- Discussion boards for each proposal.
- Real-time voting results and proposal status.
- Notification system for important updates.

**Tech Stack:**

- Frontend: React.js, Redux, React Router.
- Backend: Node.js, Express.js, MongoDB.
- Smart Contracts: Ethereum.
- Authentication: OAuth.

**Note** This is a work in progress, please reach out if you wish to collaborate!

Data Storing
Data to Store on the Blockchain:

Proposal Data: Core data related to proposals, including:

Proposal title and description.
Proposal creator (user's Ethereum address).
Number of "yes" and "no" votes.
Proposal status (e.g., pending, approved, rejected).
Proposal execution status.

## Initial setup

### Environment

Node.js 18 or 19 version

### Installing dependencies and setting up environment variables

run: `npm install`

## Running the webapp

Use the following command to locally run the webapp for development:

```
npm start
```

Use the following command to build the webapp for deployment:

```
npm run build
```
