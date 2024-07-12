# 🎉 Welcome to Polygon zkSNARK Circuit Implementation! 🎉

Hello there, welcome to my project! For this project, I have designed a zkSNARK circuit that implements a specific logical operation and deployed a verifier on-chain to verify proofs generated from this circuit.

## Description 📚

This project is an implementation of a zkSNARK circuit using the Circom programming language. The circuit is designed to handle specific logical operations, and the goal is to prove knowledge of inputs \( A \) (0) and \( B \) (1) that yield a 0 output. The project includes deploying a Solidity verifier to the Sepolia or Mumbai Testnet to verify the generated proofs.

### Creating the Circuit 🛠️
Users can create the circuit using the Circom programming language. The circuit is designed to handle specific logical operations and generate proofs.

### Generating Proofs 📜
Proofs are generated using the inputs \( A = 0 \) and \( B = 1 \) to validate the logical operation implemented in the circuit.

### Deploying Verifier 🌐
A Solidity verifier is deployed to the Sepolia or Mumbai Testnet. The verifier is used to verify the proofs generated from the circuit.

### Verifying Proofs ✅
The `verifyProof()` method on the verifier contract is called to assert the output is true, confirming the validity of the proof.

## Installation 📦

* Clone or download the code from the GitHub repository.
* Use the `hardhat-circom` template to write, compile the circuit, and generate proofs.
* Deploy the verifier to the Sepolia or Mumbai Testnet using public RPC and faucet.
* Call the `verifyProof()` method to verify the proof.

## Usage 🚀

1. **Write and Compile the Circuit**:
   - Use Circom to write and compile the circuit.
   - Generate intermediaries and proofs.

2. **Deploy Verifier**:
   - Deploy the Solidity verifier contract to the Sepolia or Mumbai Testnet.

3. **Verify Proof**:
   - Call the `verifyProof()` method on the deployed verifier contract.
   - Assert that the output is true to confirm the proof.

## Submission Requirements 📋

1. **GitHub Repository**:
   - Add your project to a public GitHub repository.
   - Include a `README.md` file with a clear overview of the project.

2. **Video Walkthrough**:
   - Record a video (5 minutes or less) explaining your code and demonstrating the project.
   - Use Loom or a similar tool for the recording.


https://www.loom.com/share/06d593f9db2e49f98f6644694b0ccfc1
[ it's not so good cuz it's one shot and done not prepared... ]

3. **Transaction/Application ID**:
   - Include the transaction or application ID if applicable.

## 👋 Join in!
Got a great idea? We'd love to see your contribution! Feel free to submit an issue or open a pull request.😁

## ⚠️ Help
Ensure you are using the correct Solidity compiler version to avoid compatibility issues.

## 👤 Authors
Hey there! I'm Mannu Baveja, the creator of this project.

---

We can't wait to see what you build! Upon completion of this project, you will earn your Proof of Learn NFT, which qualifies you for our Talent Collective, connecting you with professional opportunities.

