### Description

you will deploy an NFT collection on the Ethereum blockchain, Map the collection to Polygon, and Transfer assets over via the Polygon Bridge. To put a twist on the project, use an image generation tool - like DALLE 2 or Midjourney - to the images for your NFTs.



### Installing

1. Clone the repository:

   ```bash
    https://github.com/piyush07-bhardwaj/polygon-MOD-01
   
2. Install the required dependencies :

   ```bash
    cargo build --release
    cargo install --path circom
   
3. Installing snarkjs :

   ```bash
   npm install -g snarkjs


## Usage

To generate and verify zero-knowledge proofs for your circuits, follow these steps:

1. Define your circuit in the `circuits` folder.

2. Create an input JSON file in the `Proof` folder, specifying the inputs to your circuit.

3. Run the `genProof.js` script:

`node genProof.js`

This will compile our circuit, calculate the witness, and generate the proof and public signals.


###Projects Rubics


Generate a 5-item collection using DALLE 2 or Midjourney


Store items on IPFS using pinata.cloud


Deploy an ERC721 or ERC1155 to the Goerli Ethereum Testnet


You should have a promptDescription function on the contract that returns the prompt you used to generate the images


Map Your NFT Collection using Polygon network token mapper. Note: this isn’t necessary but helpful for visualization.


Write a hardhat script to batch mint all NFTs. Hint: ERC721A is optimal here.


Write a hardhat script to batch transfer all NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge


Approve the NFTs to be transferred


Deposit the NFTs to the Bridge


Test balanceOf on Mumbai


## Contributing

Contributions to Poly-zkEVM-Circuit are welcome! If you find any issues or want to add new features, feel free to open a pull request. 

##Author

Piyush Bhardwaj
