# Designing a consumer product to measure and categorise brain wave compositions and map them to actions

## Significant challenges
1. Sensitive probes to measure the low frequency, low voltage brain waves with poor physical contact
2. Making sure there is sufficient electrical insulation to ensure the user is safe
 
## Design decisions
Use **active** electrodes
-	High dry skin impedance can be omitted by using amplifier with very high input impedance.
-	**Active electrodes are safer than passive electrodes**. Because the dry skin-electrode impedance is very high, the isolation barrier is much higher and so the chance of electrocution is much smaller compared to passive electrodes.
-	Much more **consumer friendly** as they do not require any special skin preparation.

## Components used in EEG Active Electrode (see [pdf](https://github.com/iyop45/eeg/blob/master/EEG-AE.pdf))
- [TL062CD Op-amp 2x](http://www.mouser.co.uk/ProductDetail/Texas-Instruments/TL062CD/?qs=LfG3tU9ud8Dn8hoZrJ7g3A%3D%3D) < £0.576 each
Note: alternative op-amps could be tested and compared for performance. See [LT1115](http://m.linear.com/product/LT1115)

## Reading list
[Open EEG **important**](http://openeeg.sourceforge.net/doc/index.html)

[A Tutorial on EEG Signal Processing Techniques
for Mental State Recognition in Brain-Computer
Interfaces](https://hal.inria.fr/hal-01055103/file/lotte_EEGSignalProcessing.pdf)

[FPGA BASED BRAIN COMPUTER INTERFACE
SYSTEM](http://www.ijirse.com/wp-content/upload/2017/03/D575ijirse.pdf)
