# Digital Communication Project


  Try Diffrent Modulation Scheme with Matlab Simulink and Give breif explanation to them .

## BPSK
 - Binary Phase Shift Keying (BPSK) is a two phase modulation scheme, where the 0’s and 1’s in a binary message are represented by two different phase states in the carrier signal: θ=0∘ for binary 1 and θ=180∘ for binary 0.
 
            
      - **s1(t)** = Accos(2πfct),0≤t≤Tb for binary 1
      
      - **s0(t)** = Accos(2πfct+π),0≤t≤Tb for binary 0
## FSK
- Frequency-shift keying (FSK) is a frequency modulation scheme in which digital information is transmitted through discrete frequency changes of a carrier signal.The technology is used for communication systems such as telemetry, weather balloon radiosondes, caller ID, garage door openers, and low frequency radio transmission in the VLF and ELF bands. The simplest FSK is binary FSK (BFSK). BFSK uses a pair of discrete frequencies to transmit binary (0s and 1s) information.With this scheme, the "1" is called the mark frequency and the "0" is called the space frequency.
    
## QAM
- Quadrature amplitude modulation (QAM) is the name of a family of digital modulation methods and a related family of analog modulation methods widely used in modern telecommunications to transmit information. It conveys two analog message signals, or two digital bit streams, by changing (modulating) the amplitudes of two carrier waves, using the amplitude-shift keying (ASK) digital modulation scheme or amplitude modulation (AM) analog modulation scheme. The two carrier waves of the same frequency are out of phase with each other by 90°, a condition known as orthogonality and as quadrature.

 - QAM has types indicating the number of points in the grid is usually a power of 2 (2, 4, 8, …). Since QAM is usually square, some of these are rare—the most common forms are 16-QAM, 64-QAM and 256-QAM. 

## QPSK
- Quadrature Phase Shift Keying (QPSK) is a form of phase modulation technique, in which two information bits (combined as one symbol) are modulated at once, selecting one of the four possible carrier phase shift states. The QPSK signal within a symbol duration Tsym is defined as

   -  **s(t)** = Acos[2πfct+θn] , 0≤t≤Tsym,n=1,2,3,4 ————−(1)
   
    where the signal phase is given by:

   -  **θn** = (2n−1)π4————−(2)


