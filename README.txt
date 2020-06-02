This is a place to put all material the pertains to my learning of how to design,
build and test a custom battery management system for li-ion batteries.

A BMS or battery management system is used to regulate a battery(s) made up of
a volatile chemistry that without a BMS will eventually become unstable. There
are many BMS systems available on the market today but many are built with little
quality and have few features.

The goal of this project is to not only create a BMS that will fit my needs and
expectations but also force me to learn about circuit design, PCB layout and
manufactoring.

I decided to use a ISL94202 as the backbone for my bms. This ic is a standalone
monitoring with balancing and current/voltage protection built in. It will allow
for me to experiment with designs going from a very simple "dumb" circuit with no
communication to one with a low power arm chip that will communicate with the
ISL94202, which intern could report battery condition via CAN to a main control
board or possibly integrating other devices.

To start the first design will be a simple board that only balances a 8s battery.



Christian - 5/2020
