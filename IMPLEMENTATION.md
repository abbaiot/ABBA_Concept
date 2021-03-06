# An implementation of ABBA
This file contains the description of the code as implemented in node-red and is a specific instance of the algorithm presented in section VI of this [paper](https://arxiv.org/pdf/2108.03942.pdf).

# Pre-requisite
To run the code proposed here, the user will need to install
* [Node-red](https://nodered.org/).
* Install the Node-red-dashboard through the node-red menu.
* The Mersenne Twister Pseudo Random Number Generator (PRNG). Following instructions given here http://npmjs.com/package/mersenne-twister.

To use the Mersenne Twister module, the user will navigate to the .node-red folder and open the setting.re file to add "MersenneTwister:require(mersenne-twister')," in "functionGlobalcontext" (Tested on MacOS and Raspbian).

# Building ABBA
The [source code](https://github.com/abbaiot/ABBA_Concept/blob/main/src/flows.json) contains multiple flows and subflows that together form a simulation of the proposed intrusion detection technique. In the following paragraphs the content of each flow will be described along with the role of some of the main blocks that are critical for the code to function.  
## Transmitter
![ABBA_Tx](https://github.com/abbaiot/ABBA_Concept/blob/main/img/Tx_flow.png)

## Receiver
![ABBA_Tx](https://github.com/abbaiot/ABBA_Concept/blob/main/img/Rx_flow.png)

## User Interface
![ABBA_Tx](https://github.com/abbaiot/ABBA_Concept/blob/main/img/Dashboard.png)
