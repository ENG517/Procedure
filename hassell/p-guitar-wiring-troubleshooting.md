# Wiring a Single-Humbucker Setup: Troubleshooting

Common problems encountered when wiring guitar electronics and potential solutions.

## Prerequisites

You should have already completed the [Wiring a Single-Humbucker Setup: Connecting Components](/hassell/p-guitar-wiring.md) guide.

---

## Pot Knob Direction is Flipped

### Cause

This is the most common error when wiring guitar circuits and happens when you solder the outer lugs backwards, such as soldering the humbucker hot wire to **Lug 1** and grounding **Lug 3** on the volume pot instead of the other way around.

### Solution

De-solder the outer lugs of the affected pot(s) and re-solder them in reverse.

---

## Weak or no Sound Coming from the Circuit

### Cold Solder Joints

Solder didn’t fully bond to the lug or casing (dull, grainy, or blobbed look).

1. Reheat the joint until the solder flows smoothly and makes good contact.
2. Verify solid solder connection by tugging on the wires slighly.

### Miswired connections

Hot wire accidentally soldered to ground, or lugs mixed up on the pots/jack.

1. Double-check wiring against the diagram.
2. Re-route any misplaced wires.

### Shorts between hot and ground

A stray strand of wire, solder blob, or capacitor lead is touching a grounding point.

1. Inspect for accidental contact.
2. If there is accidental contact, re-solder as needed.
3. Clean excess solder.

### Faulty Output Jack

Jack lugs shorted, tip/sleeve reversed, or the jack is physically defective.

1. Re-solder correctly (hot → tip, ground → sleeve).
2. If that doesn't work, replace the output jack.

### Pickup Not Properly Grounded or Connected

Wrong color wires used for hot/ground, or coil leads not joined correctly.

1. Check manufacturer’s wiring code.
2. Verify that the series link wires (the ones you soldered together) are joined properly and insulated with electrical tape.

### Damaged or Faulty Potentiometer

If none of the other solutions fix the problem, you have likely fried the carbon track on one or both of the pots.

1. Replace the pot(s)
2. Ensure your soldering iron reaches at least 360 degrees Celsius.
3. Solder quickly and use heat sinks.

---

## Circuit is Humming

### Pot Grounding Issue

This could also be caused by cold solder joints with the grounding wires.

1. Double check all solder points for grounding wires (dull, grainy, or blobbed look).
2. Re-solder as needed.

### Bridge Grounding Issue

Bridge ground is either missing or the solder point is cold.

1. Ensure the bridge ground wire is soldered to the back of the volume pot casing.
2. Check for any debris between the bridge ground wire and the bridge.

---