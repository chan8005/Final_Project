Possible project subjects:

1.) Monte Carlo
	* to study equilibrium properties of a sys


2.) Molecular Dynamics -giordano text notes pg 230 (245), sample code on pg 405
	* complimentary to monte carlo instead of EQ we look at how fast sys will go to EQ
	
	* Simulate dynamics using microscopic equitions of motion
	
	* Like Euler's method but Euler has too much error with each step
	
	* Verlet Method employed
		* see appendix one 
		
	* solves verlet equations for every particle in the system
	
	* use periodic boundary conditions
	
	* have to initialize particle position and velocities before using verlet equations
	
	* This project seems feasible and very applicable to my summer research. 


DAY ONE: Notes
* I have decided to go with the MD simulations project. I will first begin by writing a code to create a box that will contain one particle and add in components that make the simulation more realisitc and interesting such as inculding forces, making it a periodic boundary and so on. 


OUtline: 
### 1. Identify general area
    * This project will use Molecular Dynamics (MD) to simulate water molecules heating up in a sphere. The focus, will not be MD and instead it will be the analysis of the data given by the simulation. 
    

### 2. Relevent Controlling equations
   * equations for the MD simulation (this will be included in the background/intro section):
       * equations of motion for each particle:
       
$\frac{\mathrm{dv_{ix}} }{\mathrm{d} t}= a_ix$

$\frac{\mathrm{dv_{iy}} }{\mathrm{d} t}= a_iy$

$\frac{\mathrm{dv_{iz}} }{\mathrm{d} t}= a_iz$

$\frac{\mathrm{dx_{i}} }{\mathrm{d} t}= v_ix$

$\frac{\mathrm{dy_{i}} }{\mathrm{d} t}= v_iy$

$\frac{\mathrm{dz_{ix}} }{\mathrm{d} t}= a_iz$

### 3. Specific Scenario: 
	*  about a 1000 molecules of water in a sphere. THe starting temperature of the system will be below freezing, then the system will be SLOWLY heated  un past 100 degrees celcius. 
	
	*The analysis will focus on properties such as Density as a function of radius, time, and temperature. I will be applying numerical methods to this section

### 4. Numerical method
	* I will be applying the numerical method in the analysis section. exact methods will be determined soon
### 5.boundary condtions
	* the boundary conditions will come from the parameters we specify for the simulation.
	

### 7. Outline of work

20th - 22:
create a plan of what values I will be extracting from the simulations and how I will be analyzing them. Intro completed

Benchmark 2: have the simulations run, have the results

Benchmark 3: have analysis completed

Benchmark 4: have presentation completed

