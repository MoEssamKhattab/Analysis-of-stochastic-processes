# Analysis of Stochastic Processes
A GUI-based tool that allows the user to input any stochastic process, resulting in the ensemble and time statistics of such process.

# Requirements
## GUI Description
The GUI should do the following:
1. Allow the user enter a random process in the form of the ensemble, i.e. all the sample functions, each defined by two vectors; time and amplitude. Note that the time vector can be common to all the sample functions. An example .m file of the ensemble is attached.
2. Allow the user to perform and display the following:
    * Plot M sample functions of the ensemble of the process, where M is entered by the user.
    * Calculate and plot the ensemble mean of the process.
    * Calculate and plot the statistical auto-correlation function between the ith sample and the jth sample of the process, where i and j are entered by the user.
    * Calculate the time mean of the nth sample function of the process, where n is entered by the user.
    * Calculate the time auto-correlation function of the nth sample function of the process, where n is entered by the user.
    * Calculate and plot the power spectral density of the process.
    * Calculate the total average power of the process.

## Testing your GUI
Test your GUI for the random processes $X(t)$ and $Y(t)$, where,
1. $X(t)$ is defined as in the attached sample file.
2. $Y(t)$ is defined as
$$Y(t) = β sin(2πt),$$
where $0 ≤ t ≤ 2, β∼N(0, 1)$ 
3. $P(t)$ is a 10-bits Polar NRZ process, </br>
with $A=5 volts, Tb = 2 seconds$, and initial time shift, $α ∼ U(0, Tb)$.

4. $M(t)$ is a 10-bits Manchester code process, \ with $A = 5 volts, Tb = 2 seconds$, and initial time shift, $α ∼ U(0, Tb)$