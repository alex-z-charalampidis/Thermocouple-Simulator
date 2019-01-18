# Thermocouple-Simulator
A small thermocouple simulator to test specific thermocouple voltage response for specific temperatures.
It has capabilities such as finding the best thermocouple suited for given temperature range automatically,
user adjusted temperature step (variable simulation accuracy), supports 8 thermocouple types and even more capabilities
![alt text](https://github.com/zaggret/Thermocouple-Simulator/blob/master/readme-image.PNG?raw=true)
**Techinal Note**: Simulation is based on high order (usually higher than 8th order) thermocouple polynomials according to "ITS-90 Thermocouple Direct and Inverse Polynomials" document and assumes a referece junction at 0C. Also because voltage approximation is based on polynomials, converting mV back to degrees celcius will produce some small scale error. For further information along with Inverse/Direct polynomials consult https://www.omega.com/techref/pdf/z198-201.pdf
