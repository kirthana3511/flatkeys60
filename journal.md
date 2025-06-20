# flatkeys build log

# total hours spent : 14

alright so here’s how this thing went down.

---

## june 9 – ideas & scribbles
- thought of making a compact choc keyboard
- 60 keys felt right — 5x12, nice grid, no weird gaps
- wanted it *thin*, no mx nonsense
- quick notes on choc switches, mbk keycaps, oled on top for fun
- decided to do pcb & 3d print myself because why not suffer

---

## june 10 – 3d mess
- opened fusion 360, started throwing rectangles around
- ended up making a layered case, not too thick, clean edges
- first draft looked okay-ish
- printed a rough one → forgot usb clearance lol → fixed
- stl ready, printer warm

---

## june 11 – wires on screen
- jumped into kicad, fresh file
- matrix setup: 5 rows, 12 cols → diodes on everything
- pro micro atmega32u4 like usual, oled on i2c
- added reset button because i always need it later and forget
- everything wired → no explosions yet

---

## june 12 – pcb spaghetti
- footprints in → routed all the switches → looked like spaghetti, cleaned it up
- had to fix the usb-c footprint orientation again (it’s always the usb…)
- ran the checks → 1 tiny error → fixed → cool
- gerbers out → we move

# june 20 - finally finished
- got busy w school lol, finally finshed, gonna submit today