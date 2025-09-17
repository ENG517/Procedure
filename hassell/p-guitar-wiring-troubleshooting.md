# Guitar Wiring Troubleshooting

Common problems encountered when wiring guitar electronics and potential solutions. Follow each problem-solution in order to rule out each one.

## Prerequisites

You should have already completed the [Wiring a Single-Humbucker Setup: Connecting Components](/hassell/p-guitar-wiring.md) guide.

---

## Pot Knob Direction is Flipped

### Reversed Lug Connections

This is the most common error when wiring guitar circuits and happens when you solder the outer lugs backwards, such as soldering the humbucker hot wire to **Lug 1** and grounding **Lug 3** on the volume pot instead of the other way around.

* De-solder the outer lugs of the affected pot(s) and re-solder them in reverse.

---

## Weak or no Sound Coming from the Circuit

### 1. Faulty Humbucker or Output Jack

#### Humbucker

There's a problem with the pickup itself or the output jack.

1. De-solder the humbucker.
2. Disconnect the wires from the output jack.
3. Re-solder the humbucker directly to the output jack.
   * Hot wire to the **Tip Lug**
   * Ground wire to the **Sleeve Lug**

If the circuit produces sound with a direct connection, it's a problem with the pots. 

#### If the Problem Persists After Soldering a Direct Connection

* Solder a different humbucker to the output jack. If the circuit produces sound, it's a faulty humbucker. If the problem persists, it's a faulty output jack and you need to replace it.

### 2. Miswired Connections

Hot wire accidentally soldered to ground, or lugs mixed up on the pots/jack.

1. Double-check wiring against the diagram.
2. Re-route any misplaced wires.

### 3. Cold Solder Joints

Solder didn’t fully bond to the lug or casing (dull, grainy, or blobbed look).

1. Reheat the joint until the solder flows smoothly and makes good contact.
2. Verify solid solder connection by tugging on the wires slighly.

### 4. Shorts Between Hot and Ground

A stray strand of wire, solder blob, or capacitor lead is touching a grounding point.

1. Inspect for accidental contact.
2. If there is accidental contact, re-solder as needed.
3. Clean excess solder.

### 5. Pickup Not Properly Grounded or Connected

Wrong color wires used for hot/ground, or coil leads not joined correctly.

1. Check manufacturer’s wiring code.
2. Verify that the series link wires (the ones you soldered together) are joined properly and insulated with electrical tape.

### 6. Damaged or Faulty Potentiometer

If none of the other solutions fix the problem, you have likely fried the carbon track on one or both of the pots. The only solution is to replace the pot(s).

> **Important:** Ensure your soldering iron reaches at least 360 degrees Celsius to limit the amount of time the iron is in contact with the carbon track. Solder quickly and use heat sinks.

---

## Circuit is Humming

### 1. Pot Grounding Issue

This could also be caused by cold solder joints with the grounding wires.

1. Double check all solder points for grounding wires (dull, grainy, or blobbed look).
2. Re-solder as needed.

### 2. Bridge Grounding Issue

Bridge ground is either missing or the solder point is cold.

1. Ensure the bridge ground wire is soldered to the back of the volume pot casing.
2. Check for any debris between the bridge ground wire and the bridge.

---
