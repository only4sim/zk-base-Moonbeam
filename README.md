# zk-base-Moonbeam
## Empowering Zero-Knowledge on Moonbeam: Introducing Zokrates and Basical Libraries

### Description
Our visionary project is set to redefine the landscape of zero-knowledge by seamlessly integrating Zokrates, a powerful zero-knowledge proof system, and essential libraries into the Moonbeam blockchain network. With a focus on addressing critical verification challenges, enhancing privacy, and providing comprehensive tools for developers, we aim to unlock a new era of secure and privacy-preserving computation on the blockchain.


### 

```plantuml
---------------------------
|   zkML-base-Moonbeam     |
---------------------------
| -[x] Zokrates Connector  |
| -[x] Pedersen Commitment |
| -[]  Perceptron          |
----------------------------
```

### Overcoming Verification Challenges
A key contribution of our project is tackling the persistent verification issues related to data types in on-chain processes. We recognize the paramount importance of efficient and reliable data verification for ensuring the integrity and validity of machine learning models. By harnessing the capabilities of Zokrates, we empower developers and researchers to overcome these challenges, facilitating trustworthy machine learning applications on Moonbeam. In addition, we have also solved the type matching problem of Zokrates when using ether.js, which is incorrectly documented in the current Zokrates documentation.

### Robust Pedersen Commitment Library
To enhance privacy and confidentiality in zero-knowledge machine learning, we have developed a robust Pedersen commitment library. Pedersen commitments play a crucial role in securely masking and encrypting sensitive data inputs within machine learning models. Our user-friendly and comprehensive library allows developers to seamlessly integrate this cryptographic technique into their Moonbeam applications, bolstering data privacy and enabling secure training and inference.

### TODO: Streamlined Perceptron Library for Neural Network Builders
Recognizing the significance of neural networks in machine learning, our project introduces a streamlined Perceptron library. This library simplifies the integration of Perceptron, a fundamental building block in neural networks, into Moonbeam. By providing developers with easy-to-use tools, we empower them to construct and train advanced neural networks, harnessing the potential of zero-knowledge methodologies to preserve privacy and confidentiality.


### Summary
Our project marks a good milestone in the advancement of zero-knowledge computation on Moonbeam. By combining the power of Zokrates with essential libraries, we offer developers the means to build privacy-preserving and secure applications. Whether it's overcoming verification challenges, leveraging Pedersen commitments for data masking, or utilizing the Perceptron library for neural network builders, our project sets the stage for the future of zero-knowledge computation on the Moonbeam blockchain.

### Demo
- [Moonbeam zero-knowlege proof template](https://youtu.be/lb7_94rqK74)
- [Pedersen Commitment Library](https://youtu.be/8kZHOQtp1Ck)

### Bounty
![Successful batch verification](/Successful%20batch%20verification.png)
We also leverage the batch precompile feature provided by the Moonbeam. It helps users to carry on batch verification, which can improve the verification efficiency greatly. Please check our demo:
- [Batch Precompile Verification](https://www.youtube.com/watch?v=7NeR2L_ueW0)

Since it takes some time for transactions to be loaded into the block explorer, we show a previously successful batch verification in the video along with a screenshot of the transaction after the explorer has been updated. You can see that the batch transaction was successfully executed as an internal transaction.


Join us on this transformative journey as we empower developers to unlock the full potential of zero-knowledge proof, fostering privacy, security, and trust on the Moonbeam network. 