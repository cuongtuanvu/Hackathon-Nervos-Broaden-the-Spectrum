
1. A screenshot of the console output immediately after you have successfully issued a smart contract call.
![Contract Call](https://github.com/cuongtuanvu/Hackathon-Nervos-Broaden-the-Spectrum/blob/main/Task%2003%20-%20Issue%20A%20Smart%20Contract%20Call%20To%20The%20Deployed%20Smart%20Contract/Contract%20Call.JPG?raw=true)

2. The transaction hash from the console output (in text format).
```
0x5415f70b514e30f96ff81dd5c99ae147c6b9e3b578c0259d35626374b64e828f
```

3. The contract address that you called (in text format).
```
0x1E4c72b11A5153E612380A8bf66186300A0753f9
```

4. The ABI for contract you made a call on (in text format).
```
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
];
```
