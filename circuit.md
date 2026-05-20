[⬅️ Build guide](build.md#main-circuit)

# Making Circuit Board

## Color coding
* Balck - Ground
* Red - Power
* Grey - Matrix
* White - LEDs
* Orange - Rows
* Blue - Cols
* Yellow - Clock
* Green - Data

## HotSwap Sockets
Push sockets into the holes using something flat on the hard surface.

![hotswaps](images/circuit/1.svg)


## Rows
Place diodes into the holders, form legs into the rows. Solder. \
Using piece of wires connect two halfs of rows.

![rows](images/circuit/2.svg)


## Collumns
Using piece of wires make collumns.

![collumns](images/circuit/3.svg)

## LEDs
Mount machine pin sockets. \
Place resistors into the holders. \
Using wires, connect resistors to the LEDs socket pins.

![leds](images/circuit/4.svg)


## Power Circuit
Using wires, build the circuit for the power routes. \
Using diode legs make ground node, connect LEDs cathodes to the ground pin of the reset button.

![power](images/circuit/5.svg)


## Routing Rows
Using wires, connect the rows to the controller socket pins.

![routing-rows](images/circuit/6.svg)


## Routing Columns
Using wires, connect the columns to the controller socket pins.

> [!TIP]
> Start wiring from the bottom contacts.

![routing-columns](images/circuit/7.svg)


## Trackpoint Connector
Mount machine pin coskets.
Using wires connect trackpoint socket to controller socket pins.

> [!NOTE]
> Pinout: YRG--B

![trackpoint](images/circuit/8.svg)


## Final look
![board](images/circuit/0.svg)

[⬅️ Build guide](build.md#main-circuit)
