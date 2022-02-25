# ElectricKeeper (ETH DENVER 2022)

An automated electric grid.
Powered by a Raspberry Pi 4, which is controlled by a hybrid smart contract using Chainlink Keepers to automate turning off LEDs for electric bill expirations.

Video demo: https://www.youtube.com/watch?v=949bsTmufhI

Website hosted on Fleek [IPFS+Filecoin]: ____ WORK IN PROGRESS _____

zkSync event counter example: [1 WEI = 1 EVENT DETECTED]:
https://rinkeby.zkscan.io/explorer/transactions/0x42d6f786023160c1b6980f3993b75702007be00d2575c97034f6831067e78227

<img src="https://github.com/MarcusWentz/ElectricKeeper/blob/main/images/animation4.gif" alt="Test"/>
<img src="https://github.com/MarcusWentz/ElectricalEthereum/blob/main/images/overview3.png" alt="Overview"/>
<img src="https://github.com/MarcusWentz/ElectricalEthereum/blob/main/images/wiring2.png" alt="Wiring"/>

Hardware: 

-Raspberry Pi 4 [Quantity: 1]

-LED (Red, Blue, Green, Yellow) [Quantity: 1 each]

-330 ohm resistor [Quantity: 4]

The LED is used to show a connection is powered while the 330 ohm resistor in series with the LED limits current (divides voltage away from LED which exponetinally increases current).

Diode Current Equation: https://www.allaboutcircuits.com/technical-articles/understanding-i-v-curves-of-non-linear-devices/

<img src="https://github.com/MarcusWentz/ElectricalEthereum/blob/main/images/diode_graph.png" alt="Graph"/>


