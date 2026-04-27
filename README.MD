# EMT - Entangled Multiplexing Transceiver

an FTL communications system utilising:

* photon orientation
* virtual alpha-numeric-symbol ring
* weak measurement by laser
* magnetic orientation manipulation



# Simple description of operation

```

* input a character to the microcontroller,
* using magnetic fields to adjust the orientation of particle A on device A,
* using that particle's centre of spin-rotation (CoR) as a pointer (like Polaris - the north star),
* imagine a ring around particle A (this is actually a table assigning orientation values to alpha-numeric characters),
* when the magnetic field is applied to orient the particle A's CoR towards a character on its ring, 
* particle B on device B moves to the character "pointed at" by particle A,
* particle B is read by laser weak measurement,
* microcontroller infers the position and displays character

```





# Advanced Concepts & Designs:

```

* Entangled Photon generation via laser bombarded BBO crystal,
* route each entangled Photon pair to its place on its respective grid:
(first particles to top left hole, 2nd to next hole etc, 10 holes per row, 10 rows = 10 x 10 grid = 1 slab)
* separate electromagnetic coils around each Photon cavity,
* each row is aligned to the same direction (same character) for noise reduction,
* each row is aligned to each sequential character in the message,
* half the slab can be TX and half can be RX giving full-duplex transmission,
* transmission speed is dependant on size of grids, rest (read & verify) time between re-orients,
```

