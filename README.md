# dxwifi-pa
##Project Overview
OreSat is a CubeSat-form factor nanosatellite being built to be placed into orbit as part of NASA’s CSLI/ELaNa program. OreSat current secondary mission objective is to be able to communicate via WiFi from space -- specifically, have data be transmitted from a COTS IEEE 802.11b module onboard the CubeSat to an inexpensive “DIY” ground station setup meant for K-12 STEM programs.

##Team Members
* Andrew Greenberg ([PSAS](http://psas.pdx.edu/) project Manager)
* Glenn LeBrasseur (RF mentor and consultant)
* Devin  Lorenzen (RF/Analog)
* Edward Sayers (Embedded Systems)
* Ben Wilson (Signal Prossessing)

##Project Specifications
###Must
* Operate in space environment in a CubeSat
  * Operate under industrial temperature range (-40° to +100°C)
  * Radiation robust (handles SEU / latch-up)
  * Use conduction, not convection, to cool.
* Operate in an amateur launch vehicle environment
  * Constant g load of 15g’s
  * Vibration of ? g’s (TBD: mil spec rating)
* Fit 1U CubeSat Form Factor ( < 10X10X10 cm)
* Have a output power greater than 25.2dBm (⅓ W)
* Have an average power consumption less than 6W
* Have a Tx gain greater than 15.2dB
* Have a Rx gain greater than 19dB
* Have a power added efficiency (PAE) greater than 60%
* Handle binary phase shift keying (BPSK) modulation
* Operate on a Vcc = (10,14.7,16.4)V
* Be FCC compliant
  * out of band harmonics must be -40dB below carrier 
* operate with a center frequency of 2.412GHz
* Have a bandwidth of 22MHz

###Should
* Have a PAE greater than 70%
* Operate under in a temperature range of -55° to +125°C
* Have a Tx Gain of 20dB
* Have a output power of 30dBm(1W)
* increase heat buffer by 10%
 
###May
* Have PAE greater than 80%
* Have a Tx gain of 30dB
* Have a power output of 40dBm (10W)
* Have an adjustable power output

##Notes
* Assuming linearity is not a design requirement.
