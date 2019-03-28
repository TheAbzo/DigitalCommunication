# DigitalCommunication Project

## BPSK

1. Binary Phase-shift keying is a digital modulation scheme that conveys data by changing, or modulating, two different phases of a reference signal (the carrier wave). 
The constellation points chosen are usually positioned with uniform angular spacing around a circle. This gives maximum phase-separation between adjacent points and thus the best immunity to corruption. 

2. **The 2 scatter diagrams** are produced by 2 constellation diagrams ,that shows the difference between source without noise and after noise.
  **The Ber** is produced by running `bertool` in command window then in **Theoratical Tab** we change value to -10:10 and press plot.
then in **Monte Carlo**Tab we add our file.slx and put our Ber variable name (in the block diagram) ,aslo change Eb/No range to -10:10 and run and record the points.

3. Scatter Diagram
![alt text](https://github.com/TheAbzo/DigitalCommunication/blob/master/scatter%20plots/BPSK%20scatter.png)

4. Ber Diagram (it also has QPSK)
![alt text](https://github.com/TheAbzo/DigitalCommunication/blob/master/Ber%20diagrams/QPSK_BPSK.png)

## QPSK

1. Quadrature Phase Shift Keying is a form of Phase Shift Keying in which two bits are modulated at once, selecting one of four possible carrier phase shifts (0, 90, 180, or 270 degrees). QPSK allows the signal to carry twice as much information as ordinary PSK using the same bandwidth.

2. **The 2 scatter diagrams** are produced by 2 constellation diagrams ,that shows the difference between source without noise and after noise.
  **The Ber** is produced by running `bertool` in command window then in **Theoratical Tab** we change value to -10:10 and press plot.
then in **Monte Carlo**Tab we add our file.slx and put our Ber variable name (in the block diagram) ,aslo change Eb/No range to -10:10 and run and record the points.

3. Scatter Diagram
![alt text](https://github.com/TheAbzo/DigitalCommunication/blob/master/scatter%20plots/QPSK.png)

4. Ber Diagram (it also has BPSK)
![alt text](https://github.com/TheAbzo/DigitalCommunication/blob/master/Ber%20diagrams/QPSK_BPSK.png)


## FSK

1. Frequency-shift keying, a modulation technique in which different frequencies in the carrier signal are used to represent the states of the source data.

2. **The 2 scatter diagrams** are produced by 2 constellation diagrams ,that shows the difference between source without noise and after noise.
  **The Ber** is produced by running `bertool` in command window then in **Theoratical Tab** we change value to -10:10 and press plot.
then in **Monte Carlo**Tab we add our file.slx and put our Ber variable name (in the block diagram) ,aslo change Eb/No range to -10:10 and run and record the points.

3. Scatter Diagram
![alt text](https://github.com/TheAbzo/DigitalCommunication/blob/master/scatter%20plots/fsk_.png)

4. Ber Diagram 
![alt text](https://github.com/TheAbzo/DigitalCommunication/blob/master/Ber%20diagrams/fsk.png)


## QAM16

1. 16 Point Quadrature Amplitude Modulation

2. **The 2 scatter diagrams** are produced by 2 constellation diagrams ,that shows the difference between source without noise and after noise.
  **The Ber** is produced by running `bertool` in command window then in **Theoratical Tab** we change value to -10:10 and press plot.
then in **Monte Carlo**Tab we add our file.slx and put our Ber variable name (in the block diagram) ,aslo change Eb/No range to -10:10 and run and record the points.

3. Scatter Diagram
![alt text](https://github.com/TheAbzo/DigitalCommunication/blob/master/scatter%20plots/qam16_.png)

4. Ber Diagram (it also has QAM64)
![alt text](https://github.com/TheAbzo/DigitalCommunication/blob/master/Ber%20diagrams/QAM16_64.png)


## QAM64

1. 64 Point Quadrature Amplitude Modulation

2. **The 2 scatter diagrams** are produced by 2 constellation diagrams ,that shows the difference between source without noise and after noise.
  **The Ber** is produced by running `bertool` in command window then in **Theoratical Tab** we change value to -10:10 and press plot.
then in **Monte Carlo**Tab we add our file.slx and put our Ber variable name (in the block diagram) ,aslo change Eb/No range to -10:10 and run and record the points.

3. Scatter Diagram
![alt text](https://github.com/TheAbzo/DigitalCommunication/blob/master/scatter%20plots/QAM64_.png)

4. Ber Diagram (it also has QAM16)
![alt text](https://github.com/TheAbzo/DigitalCommunication/blob/master/Ber%20diagrams/QAM16_64.png)






