# DIY-SIM-PEDALS

These are my pedals for my racing setup, which I'll be using on my personl gaming setup. I didn't made other parts like "stearing", "gear" yet but I'm planing to make 'em!! But for now I'm realley exited to build this in irl!!


## Images (Tasveer)

<img width="1877" height="980" alt="1781898199606-z3j6qn" src="https://github.com/user-attachments/assets/8522b879-aa30-4658-9ae9-86bed4c72f96" />
<img width="1878" height="980" alt="1781898242252-ps019c" src="https://github.com/user-attachments/assets/c6d6a54c-bb96-4f7b-b739-341c52fa11dd" />
<img width="1858" height="975" alt="1781898239263-xr04bh" src="https://github.com/user-attachments/assets/d2503589-7c56-47ed-923b-4a601635c77c" />
<img width="1520" height="968" alt="1781898091012-3e7rf2" src="https://github.com/user-attachments/assets/915f7b32-f909-43bb-94a2-f0d0d27b11a0" />


##  Bill of Materials (BOM)

| Item | Purpose | Quantity | Total Cost (USD) | Purchase Link | Distributor |
|------|---------|:--------:|:----------------:|---------------|-------------|
| Springs | Tension | 4 | $5.50 | https://amzn.in/d/0eIVMHWZ | Amazon |
| L Joints | For connecting vertical and horizontal support | 1 | $2.00 | https://amzn.in/d/05FpWmgl | Amazon |
| Jumper Wire with Breadboard | Connections | 1 | $3.00 | https://amzn.in/d/0d2eNkw3 | Amazon |
| ESP32 | Microcontroller | 1 | $7.00 | https://amzn.in/d/0fZDF7oJ | Amazon |
| 2nd Filament | 3D Printing | 1 | $7.00 | https://amzn.in/d/05LWoKht | Amazon |
| Filament for 3D Printer | 3D Printing | 1 | $7.00 | https://amzn.in/d/0eveRcwI | Amazon |
| Potentiometers | Controlling accelerator, brake, and clutch | 3 | $8.00 | https://amzn.in/d/0eveRcwI | Amazon |

###  Total Estimated Cost
**$45.50 USD**


## Features

-Highly precise pedals.

-Just plugin & play!!

-Coustom DIY

-Presure sensetive springs

## Wiring Digram

```text
                     ESP32

                 +-------------+
                 |             |
3.3V ------------+-------------+-------------------+
                 |             |                   |
                 |             |                   |
                POT 1         POT 2              POT 3
             (Accelerator)   (Brake)           (Clutch)

 VCC ---------- 3.3V -------- 3.3V ----------- 3.3V
 GND ---------- GND --------- GND ------------ GND
 SIG ---------- GPIO34 ------ GPIO35 --------- GPIO32

                 +-------------+
                 |    ESP32    |
                 +-------------+
```

### Potentiometer Pinout

```text
          Front View

      +-------------------+
      |                   |
      |   Potentiometer   |
      |                   |
      +-------------------+

      Left     Middle      Right
      GND      SIGNAL       3.3V
```


# Enjoy XD
