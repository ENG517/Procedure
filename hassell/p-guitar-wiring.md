# Wiring a Single-Humbucker Setup: Connecting Components

## Prerequisites

### Materials

* One Humbucker
* Two Split Shaft 500K potentiometers
  * The larger the casing the easier they are to work with.
* Potentiometer knobs
* A mono output jack
* A spool of red and a spool of black stranded tinned copper wire
  * You can find single spools that have both.
* A spool of solid core copper wire
* A .022uf tone capacitor

Your materials should be prepped and ready to connect. If they are not, follow the [Wiring a Single-Humbucker Setup: Preparing Materials](/hassell/p-guitar-wiring-prep-materials.md) guide.

### Tools

* Soldering Iron, between 40W and 80W. Anything less than 40W will be too weak.
* Solder; any kind will work.
* A wire stripper
* A screwdriver set
* Electrical tape
* A marker

### Skills

* You should have some prior experience soldering. If you don't, practice for a few hours before continuing with this guide. *(Will insert link to a soldering guide here)*

---

## Important Details and Warnings for Soldering

When soldering wires to the pot casings, there is a risk of frying the carbon track, which will either break the pot entirely or limit its ability to control volume or tone. Below are some steps to take to help prevent that:

1. Ensure your soldering iron is heated to at least 360 degrees Celsius. The hotter it is, the less time it needs to be in contact with the pot casing.
2. After soldering a wire to the pot casing, give it some time to cool before soldering anything else to it.
3. While not required, using [heat sinks](https://www.youtube.com/watch?v=7TQfPwgvEe4) can help.

---

## Connecting the Humbucker

![Wiring diagram showing where to connect humbucker wires](/hassell/assets/images/screenshots/humbucker-wire.png)

### 1. Connect the Hot Wire

Solder the **black** wire to **Lug 3** of your designated volume pot.

### 2. Connect the Ground Wire

Solder the **white**, **green**, or **yellow** wire, depending on the type and brand of your humbucker, to the casing of the volume pot.

---

## Connecting the Hot Wires

![Wiring diagram showing the volume pot hot wire connections](/hassell/assets/images/screenshots/lug2-wire.png)

### 1. Join Hot Wires

Twist together the stripped ends of the two red wires you previously cut on one side only, leaving the other ends separate.

### 2. Solder Hot Wires

1. Solder the twisted end to **Lug 2** of the volume pot.
2. Solder one of the separate ends to **Lug 1** of the tone pot.
3. Solder the other separate end to the **Tip** of the output jack (smaller outer-most lug).

---

## Connecting the Capacitor

### 1. Connect Hot End

Solder one leg of the capacitor to **Lug 2** of the tone pot. Since this kind of capacitor is non-polarized, meaning current can flow in either direction, it does not matter which end you choose to be the hot end.

### 2. Connect Ground End

![Diagram showing the tone pot side view with parallel capacitor leg](/hassell/assets/images/screenshots/tone-pot-side-view.png)

1. Place the other leg of the capacitor against the tone pot case and fold the end to be parallel with the pot casing.
2. Solder the folded end to the pot casing.

---

## Grounding Lug 1 of the Volume Pot

![Wiring diagram showing the ground connection from Lug 1 of the volume pot to the casing](/hassell/assets/images/screenshots/lug1-ground.png)

### Method 1: Connect the Solid Core Wire

Solder the fully-stripped 0.5 inch solid core wire from **Lug 1** of the volume pot straight back to the volume pot casing.

> **Note:** Depending on the size of the pots you have, 0.5 inches may be too large. If the wire is too large, you again risk breakage or a cold solder connection that will nullify the grounding.

### Method 2: Solder the Lug Directly

Instead of using a solid core wire, you can bend **Lug 1** of the volume pot back and solder it directly to the casing, which is far more time and space efficient.

**I do not recommend using this unless you are confident in your soldering abilities.**

---

## Grounding the Rest of the Circuit

### 1. Connect the Two Pots

![Wiring Diagram showing the ground connection between the volume and tone pots](/hassell/assets/images/screenshots/pot-ground.png)

Solder one of the black wires you previously cut from the volume pot casing to the tone pot casing.

### 2. Connect the Output Jack Ground

![Wiring Diagram showing the ground connection between the volume pot casing to the output jack](/hassell/assets/images/screenshots/output-jack-ground.png)

Solder the final black wire from the casing of the volume pot to the Sleeve of the output jack (the larger inner-most lug).

---

## Testing the Circuit

Everything is wired in place. Now, it's time to test things out. 

### 1. Connect to an Amp

1. Plug a 1/4 inch cable from the output jack to an amp.
2. Turn the amp on and crank the volume.

### 2. Check for Sound

1. Turn the knob of the volume pot all the way clockwise.
2. Using your phone, or any music playing device, play a song and hold the speaker up to the humbucker. You should hear the song playing through the amp.
3. With the song still playing against the humbucker, turn the knob of the volume pot counter-clockwise. You should hear the song get quieter as you turn, going completely mute when the knob is turned fully counter-clockwise.

### 3. Check for Tone

With the song still playing against the humbucker, turn the knob of the tone pot clockwise and counter-clockwise. You should hear a noticeable difference as you do: turning the knob all the way counter-clockwise will considerably cut high end frequencies, leaving a very bassy tone.

### Troubleshooting

If the expected outcomes listed in the previous three steps are not met, consult the Troubleshooting guide.

---

## Installing the Circuit

If everything checks out with the circuit test, you can go ahead and install the parts into the body of the guitar.

### 1. Disconnect Necessary Components

1. De-solder the humbucker entirely.
2. De-solder the output jack entirely. Disconnect the wires from the output jack itself rather than the volume pot.

### 2. Place Components into the Body

1. Screw the humbucker into its slot in the body and run the wires into the electronics cavity.
2. With the rest of the circuit stil intact, fasten the pots into their slots in the electronics cavity.
3. Slide the knob caps onto the pot knobs.
4. Run the wires that were connected to the output jack through to the output jack slot in the body.

### 3. Reconnect the Disconnected Components

1. Re-solder the humbucker wires to the volume pot.
2. Resolder the output jack wires to the output jack.

### 4. Connect the Bridge Ground

While not pictured in the diagram, your guitar body should have a wire running from one of the bridge peg slots into the electronics cavity.

1. If the body doesn't have that wire, cut and strip the ends off one more black wire.
2. Run the wire from the electronics cavity into the bridge slot through the small hole in the cavity wall.
3. Fray the end of the wire that's in the bridge slot and press the frays into the wall.
4. Solder the other end to the volume pot casing.

---

## Conclusion

With the completion of this guide, you have successfully wired a single humbucker setup with volume and tone control. Plug in your guitar, test each knob, and enjoy your new sound. If you’d like to expand later, this setup also makes it easy to add coil-splitting or a second pickup.