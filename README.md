# MagneticResonanceImaging
Codes for PulSeq Decoding , Timing and Synchronization Signal Generation, Ethernet upload and download. Enjoy!

These codes are developed as a part of my master's project at IIT Bombay, wherein I was involved with a reserch group working for the design of indegenous technology 1.5T MRI Scanner and, yes!!!, I was given the tough task to design the MASTER CONTROLER. This controlling system is distributed in 4 major sections:

# PulSeq Decoding (PSD)
PulSeq or Pulse Sequence is a text file that contains the excitation sequence of the various MRI subsytems, as in the three gradient coils (Gx,Gyand Gz), RF coils (RadioFrequency TxRx coils), receiver ADCs(Analog to Digital Converters) and delays involved in an MRI scan. The specifications for the pulses required for gradient and RF are also encoded and included in this file. Thus the PulSeq decoding step, decodes all these encoded data to extract the pulse shape and subsystem excitation information, which is then given to the Timing and Synchronization Signal Generation block for control of MRI sub-sytems in real time.

# Timing and Synchronization Signal Generation (TSSG)


# Laugh as much as you breathe, Love as long as you live! :D
