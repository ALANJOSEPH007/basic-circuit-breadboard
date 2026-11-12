
# Basic Circuit Build: Battery, Switch, Resistor and LED

A low-voltage DC circuit built on a breadboard from a circuit diagram, with
continuity and voltage checked using a digital multimeter.

## Goal
To practise reading a simple circuit diagram, building the circuit
accurately, and checking it with a multimeter, as a first step into
electrical and panel-building work.

## Components
- 9V battery with snap connector
- Slide or push switch
- 470 Ω resistor (yellow-violet-brown)
- Red LED
- Breadboard and jumper wires
- Digital multimeter

## Circuit diagram
Battery (+) → switch → 470 Ω resistor → LED (long leg, anode) → LED (short
leg, cathode) → Battery (−)

See `diagram/` for the diagram I followed.

## How it works
Current flows from the battery's positive terminal through the switch and the
resistor to the LED, then back to the negative terminal. The resistor limits
the current so the LED isn't damaged. An LED only works one way round, so the
longer leg (anode) must connect towards the positive side.

Expected current: (9 V − about 2 V LED voltage) ÷ 470 Ω ≈ 15 mA.

## Build steps
1. Place the LED on the breadboard, with the long leg in a different row
   from the short leg.
2. Connect the resistor from the LED's long leg row to an empty row.
3. Connect the switch between that row and the battery's positive wire.
4. Connect the battery's negative wire to the LED's short leg row.
5. Check every connection against the diagram **before** connecting the
   battery.
6. Connect the battery and test the switch.

## Testing with the multimeter
| Check | Expected | Measured |
|---|---|---|
| Continuity: switch closed, battery (+) wire to resistor | Beep / near 0 Ω | |
| Continuity: switch open | No beep / open circuit | |
| Battery voltage (no load) | About 9 V | |
| Voltage across resistor, circuit on | About 7 V | |
| Voltage across LED, circuit on | About 2 V | |

## Problems and fixes
(Add anything that went wrong and how you found and fixed it, for example the
LED not lighting because it was the wrong way round. Delete this section if
nothing went wrong.)

## Safety
- Low voltage only (9 V battery).
- Battery disconnected while changing any connection.
- Connections checked against the diagram before powering up.
- Components kept dry and away from loose metal.

## What I learned
- How to read a simple circuit diagram and build from it.
- How to use a multimeter to check continuity and measure voltage.
- Why a resistor is needed with an LED, and how to check results against
  expected values.

## Photos
See `images/` for each stage of the build and the finished circuit.
