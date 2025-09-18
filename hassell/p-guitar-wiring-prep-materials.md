# Wiring a Single-Humbucker Setup: Preparing Materials

The purpose of this guide is to provide an overview of materials needed to wire a simple single-humbucker circuit in an electric guitar and how to properly prepare them for easiest application. Intended for budding hobbyists seeking to delve into the world of guitar circuitry. You will be able to translate skills learned in this and the subsequent guides in this repository to more complex circuits.

This guide is intended for Les Paul or Les Paul Junior models.

## Prerequisites

### Materials

* One Humbucker
* Two Split Shaft 500K potentiometers
  * The larger the casing the easier they are to work with.
* Potentiometer knobs
  * Ensure they are compatible with Split Shaft knobs, not smooth shaft. 
* A mono output jack
* A spool of red and a spool of black stranded tinned copper wire
  * You can find single spools that have both.
* A spool of solid core copper wire
* A .022uf tone capacitor

### Tools

* Soldering Iron, between 40W and 80W. Anything less than 40W will be too weak.
* Solder; any kind will work.
* A wire stripper
* A screwdriver set
* Electrical tape
* A permanent marker

### Skills

You should have some prior experience soldering. If you don't, follow a [tutorial video](https://www.youtube.com/watch?v=rK38rpUy568) and practice for a few hours before continuing with this guide.

---

## Component Breakdowns

### Potentiometers

![Potentiometer diagram](/hassell/assets/images/screenshots/potentiometer-diagram.png)

A *potentiometer* (which I'll refer to as a "pot" from now on) is a type of rotating resistor that will control your guitar's *tone* and *volume* (hence why you need two). They are what you will be soldering on, so it's important to get acquainted with their parts.

#### Lugs

* Lug 2 is connected to the carbon track, a type of resistant wiper (think windshield) that controls the amount of electrical current diverted to the outer lugs (Lugs 1 and 3). Turning the knob left will divert the current to Lug 1 while turning the knob right will divert the current to Lug 3.
* Lugs 1 and 3 will serve different functions across the volume and tone pots, so the important thing to remember is one will receive current and one will not.

### Hot Wires vs Ground Wires

*Hot wires* carry active electrical current, *ground wires* serve as a safety path in case of a short ciruit. Think of hot wires as carrying the sound and ground wires as blocking excess noise.

In this procedure, hot wires will be **red**, ground wires will be **black**.

---

## Preparing Materials

### 1. Determine the humbucker hot and ground wires.

* If your humbucker has only two wires, you have a **2-conductor humbucker**.
  * The **black** wire is the hot wire
  * the **white** wire is the ground wire
* If your humbucker has four wires, you have a **4-conductor humbucker**.
  * The **black** wire is the hot wire
  * The **yellow** or **green** wire is the ground wire (you will only have one or the other).

> **Note:** if you have a 4-conductor humbucker, ensure the two wires that are NOT the hot wires are soldered together and taped off with electrical tape. Failure to do so will cause major noise bleed and a weak sound.

### 2. Orient the Pots

Flip both pots so the knobs are facing down and the flat metal casing and lugs are pointing up. with **Lug 3** on the left (refer to pot diagram for specific lug placement).

### 3. Label Pot Casings

With a permanent marker, label one pot with **V** for volume and the other with a **T** for tone on the back of the casings (the flat side). Since both are 500k pots, it doesn't matter which is which.

### 4. Prepare Threaded Wires

1. Cut four 3.5-inch wires from the threaded spools, two black and two red.
2. Strip the ends

### 5. Prepare the Solid Wire

1. Strip a 1 inch section off the end of the solid core spool.
2. Cut half of the stripped section off. You should be left with a 0.5-inch fully-stripped wire.

### 6. Tin the Wires

Apply a small amount of solder to the stripped ends of the five wires you just cut AND the humbucker hot and ground wires, just enough to coat the ends. This will make it easier to solder them to the pots.

### 7. Prepare the Capacitor

If the capacitor has extra long legs, cut each leg to just under 0.5 inches.

---

## Next Steps

Once your materials are prepped, you're ready to start putting things together. Move on to the [Wiring a Single-Humbucker Setup: Connecting Components](/hassell/p-guitar-wiring) guide.
