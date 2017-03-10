# Project's proposal
Improve existing software development process using some methods learned in the course.
The project I am working at is a real-time system for pen and touch detection, we are creating a new platform that will allow us to perform touch detection algorithms in user space on the CPU.
The work includes migrating some of the code from the dedicated digitizer, and sending raw data from the hardware to the OS.
The project is to Reuse components from the digitizer code (both will be in C++) and adding new Algorithms for better touch experience.
elements to be used from the course:
1. Reuse
2. Refactoring
3. Regression tests - we will record raw data sent from digitizer an write scripts to run the touch component with that input, 2 types of tests we are thinking of : bit exact with previous version where it is relevant, qualily tests which will test that the result is in an expected interval.
