# QOSF-task
Zero Noise Extrapolation (Task 3)

Zero-noise extrapolation (ZNE) is a noise mitigation technique. It works by intentionally scaling the noise of a quantum circuit to then extrapolate the zero-noise limit of an observable of interest. In this task, you will build a simple ZNE function from scratch:

Build a simple noise model with depolarizing noise 
Create different circuits to test your noise models and choose the observable to measure 
Apply the unitary folding method. 
Apply the extrapolation method to get the zero-noise limit. Different extrapolation methods achieve different results, such as Linear, polynomial, and exponential.
Compare mitigated and unmitigated results 
Bonus: Run your ZNE function in real quantum hardware through the IBM Quantum Service

Check the Mitiq documentation for references. You are not allowed to use the functions from Mitiq or any other frameworks where ZNE is already implemented. 
