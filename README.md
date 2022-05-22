## Tech Used
* Vue Js
* Algorand Testnet
* Purestake API
* Pyteal as Backend

## Inspiration
We wanted to build a **Decentralized Voting System using Blockchain** .After read the hackathon readme file we wanted to made a vue app on the algo-testnet . In their People can Vote their Favourite team . we are making this voting app of the state cricket teams.
 **Using blockchain, voting process can be made more secure, transparent, immutable, and reliable

## Advantages
* You can vote anytime/anywhere (During Pandemics like COVID-19 where it’s impossible to hold elections physically).
* Secure
* Immutable
* Faster
* Transparent
* Only Creator can Choose Winner.
* 
## General Voting Diagram
![voting-diagram](https://github.com/SAMBITSARGAM/algorand-voting/blob/main/2020-04-22-21.png)
## How i built it
We Know that :-
"A blockchain is a time-stamped decentralized series of fixed records that contains data of any size is controlled by a large network of computers that are scattered around the globe and not owned by a single organization. Every block is secured and connected with each other using hashing technology which protects it from being tempered by an unauthorized person."
* The contracts.py file contains the smart contract code and is written with the PyTeal library. In this example, a new smart contract is deployed for each new auction. And as we described in the overview, every auction needs to support creating, setting up, placing a bid, and closing out an auction. In a bit, we’ll take you through where each of these scenarios is represented in the code.
* Only the owner of the web-app can set winner and add a contest because if we gave permission to all then it's can not secure.

## Challenges we ran into
I made this application using vue as a frontend and pyteal as our backend.

## Accomplishments that I proud of
* My first Dapp in the Algorand Blockchain.
* It's takes more than 48hours but finally it's over you can try[link](https://algorand-voting.vercel.app/)

<-----------Thank You ------------->

### Licence 
```
MIT License

Copyright (c) 2022 SAMBIT SARGAM EKALABYA

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
