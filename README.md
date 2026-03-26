# A320RMP
## A320 Radio Management Panel
_Made for MSFS2020, MobiFlight, RP2040, and the FlyByWire A32NX_

### What is this?
The A320RMP is a small desktop radio management panel for use with Microsoft Flight Simulator and MobiFlight, and is based off the Raspberry Pi RP2040 platform.

### Why was this made?
While flying on VATSIM with MSFS2020, I realized it was very difficult to switch frequencies through the mouse and scroll wheel in the FlyByWire A32NX. So, here is my version of the A320 RMP.

## Firmware
This RMP uses [MobiFlight](https://mobiflight.com) for its firmware and programming with a RP2040.<br>
MobiFlight Firmware and Project Files are in `mobiflight/` (`mfmc` and `mfproj`)<br>
**NOTE: RP2350/Pi Pico 2 will NOT work with MobiFlight. Only the RP2040 or Pi Pico 1 is compatible.**

## Pictures
### Schematic
`img/schematic.png`<br><img src="img/schematic.png" alt="Schematic" height=700>
### PCB
`img/pcb.png` - `pcb/A320RMPv1FinalGerber.zip`<br><img src="img/pcb.png" alt="PCB" height=700>
### CAD / Models
#### Knob
`img/knob.png` - `cad/knob.step`<br><img src="img/knob.png" alt="Knob" height="300"><br>
#### Case
`img/case.png` - `cad/case.step`<br><img src="img/case.png" alt="Case" height="300"><br>
#### Lid
`img/lid.png` - `cad/lid.step`<br><img src="img/lid.png" alt="Lid" height="300"><br>
#### Buttons
`img/button.png` - `cad/button.step`<br><img src="img/button.png" alt="Button" height="300"><br>
### Final Render
`img/final1.png`<br><img src="img/final1.png" alt="Final 1" width="600"/><br>
`img/final2.png`<br><img src="img/final2.png" alt="Final 2" width="600"/><br>
`img/final3.png`<br><img src="img/final3.png" alt="Final 3" width="600"/><br>

## BoM (General)
_Stasis BoM_ (`bom-stasis.csv`) _includes shipping, tax, fees, and required tools._<br>
_Below: General BoM_ (`bom-general.csv`)
| Name | Purpose | Quantity | Total Cost (USD) | Link | Distributor |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Waveshare RP2040+ | Pico USB-C | 1 | 14.99 | [Link](https://www.amazon.com/RP2040-Plus-High-Performance-Microcontroller-Compatible-Pre-soldered/dp/B09KZFJTV9) | Amazon |
| SMD Stencil | Soldering | 1 | 7.11 | [Link](https://jlcpcb.com) | JLCPCB |
| PCB | 5 minimum | 5 | 9.00 | [Link](https://jlcpcb.com) | JLCPCB |
| Flux 30g | Paste | 1 | 9.99 | [Link](https://www.amazon.com/gp/product/B0D3H8NZLP) | Amazon |
| Solder Paste 30g | Sn63/Pb37 | 1 | 12.99 | [Link](https://www.amazon.com/gp/product/B0BH4HRWGX) | Amazon |
| Female Header Pins | Header C7499336 | 5 | 1.20 | [Link](https://www.lcsc.com/product-detail/C7499336.html) | LCSC |
| SPST Switch | Switch C1788492, THT | 2 | 1.26 | [Link](https://www.lcsc.com/product-detail/C1788492.html) | LCSC |
| Multiplexer IC | Multiplexer C6525 | 2 | 1.42 | [Link](https://www.lcsc.com/product-detail/C6525.html) | LCSC |
| 7seg CT IC | 7seg Controller IC C6705351 | 4 | 6.28 | [Link](https://www.lcsc.com/product-detail/C6705351.html) | LCSC |
| Logic Level IC | TI Logic Lvl C155176, 3.3V to 5V | 2 | 0.66 | [Link](https://www.lcsc.com/product-detail/C155176.html) | LCSC |
| Green L0603 | LED C19273151, min 100 | 100 | 0.60 | [Link](https://www.lcsc.com/product-detail/C19273151.html) | LCSC |
| Rotary Encoder | Rot Enc C470754, THT | 3 | 6.24 | [Link](https://www.lcsc.com/product-detail/C470754.html) | LCSC |
| 22Kohm R0603 | Resistor C2907015, min 100 | 100 | 0.10 | [Link](https://www.lcsc.com/product-detail/C2907015.html) | LCSC |
| 220ohm R0603 | Resistor C22962, min 100 | 100 | 0.13 | [Link](https://www.lcsc.com/product-detail/C22962.html) | LCSC |
| 6digit 7segment Display | Display C47471 | 3 | 5.20 | [Link](https://www.lcsc.com/product-detail/C47471.html) | LCSC |
| 6x6mm Button | Button C49234152, min 20 | 20 | 0.61 | [Link](https://www.lcsc.com/product-detail/C49234152.html) | LCSC |
| 10uF C0603 | Capacitor C1591, min 20 | 20 | 0.35 | [Link](https://www.lcsc.com/product-detail/C96446.html) | LCSC |
| 0.1uF C0603 | Capacitor C1591, min 100 | 100 | 0.28 | [Link](https://www.lcsc.com/product-detail/C1591.html) | LCSC |
_plus Applicable Tax, Fees, Shipping, and Tools_

## A320RMP wouldn't be possible without:
* VATSIM, https://vatsim.net
* MobiFlight, https://mobiflight.com
* FlyByWire Simulations, https://flybywiresim.com
* Hack Club, https://hackclub.com
* Stasis, https://stasis.hackclub.com

### A shoutout to:
* Oakland vARTCC, https://oakartcc.org

### And most importantly,
* @witherman3000, https://witherman3000.com

<br>Thanks for looking through my project!<br>
`5NN TNX FER QSO DE KO6LVM SK CL`