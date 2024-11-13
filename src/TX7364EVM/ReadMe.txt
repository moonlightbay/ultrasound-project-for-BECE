**************************
*	TX7364 JYOTI
**************************


1) For LVDS Input Buffer,
	*The internal termination is not conisdered while creating the ibis model for the LVDS input buffers.
	*The user has to keep the external termination while simulating these models.

2) The SPI pins (SENP,SENM,SCLKP,SCLKM,SDATAP_0/1,SDATAM_0/1) are modelled in both "lvds mode" and "CMOS mode".
	Model name (for LVDS mode): lvdsspi
	Model name (for CMOS mode): cmosspi

3) The (BF_CLKP,BF_CLKM) pins have to be ac coupled (as per the data sheet).

4) The LVDS input buffer is simulated and verified by keeping a source impedance of 50 ohm and termination resistor of 100 ohm/400 ohm. For the BF_CLK pins the same configuration is ac coupled with 10nF capacitor.

5) The input buffer is simulated and verified using the 50 ohm/ 1k ohm source impedance.

6) The output buffer is simulated and verified using a 50 ohm load resistor and 10 nF load capacitor.



