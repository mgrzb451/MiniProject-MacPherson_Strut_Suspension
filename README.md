# MacPherson Strut Suspension - Design and Analysis
This is a mini project focused on learning about different suspension systems present in modern electric vehicles. This one focuses most deeply on understanding the design and workings of the **MacPherson Strut Suspension**

# Design
To understand how each component works and what its functions are the best way is to design your own! So I designed a simplified MacPherson Strut Suspension system of a single front wheel. I based my works loosely on a YT video and geometry presented there

<img width="556" height="750" alt="image" src="https://github.com/mgrzb451/MiniProject-MacPherson_Strut_Suspension/blob/main/assets/motion.gif" />
<img width="710" height="759" alt="image" src="https://github.com/mgrzb451/MiniProject-MacPherson_Strut_Suspension/blob/main/assets/3d0.jpg" />
<img width="893" height="821" alt="image" src="https://github.com/mgrzb451/MiniProject-MacPherson_Strut_Suspension/blob/main/assets/3d1.jpg" />
<img width="1371" height="820" alt="image" src="https://github.com/mgrzb451/MiniProject-MacPherson_Strut_Suspension/blob/main/assets/3d2.jpg" />
<img width="1010" height="814" alt="image" src="https://github.com/mgrzb451/MiniProject-MacPherson_Strut_Suspension/blob/main/assets/3d3.jpg" />
<img width="920" height="811" alt="image" src="https://github.com/mgrzb451/MiniProject-MacPherson_Strut_Suspension/blob/main/assets/3d4.jpg" />


## Wheel, cause I'm a child 🤦🏻‍♂️
I got this idea for a Batman themed Wheel Rim...yes, I'm a child 😅

<img width="992" height="1056" alt="image" src="https://github.com/mgrzb451/MiniProject-MacPherson_Strut_Suspension/blob/main/assets/wheel3D_0.jpg" />
<img width="992" height="1056" alt="image" src="https://github.com/mgrzb451/MiniProject-MacPherson_Strut_Suspension/blob/main/assets/wheel_render1.jpg" />

# Lower Arm Analysis
I performed some simple structural analysis of the Lower Arm as a preliminary step to an idea for some projects down the line I had.
Two subcases will be explored:
1. Heavy breaking
2. Sharp cornering 

<img width="888" height="442" alt="image" src="https://github.com/mgrzb451/MiniProject-MacPherson_Strut_Suspension/blob/main/assets/fem0.jpg" />

## External Loads Calculations
The Forces applied to the FEM are based on the Mass of the **BYD Seal Premium (RWD, 82.5 kWh)** of $2055 \text{ kg}$
<img width="786" height="208" alt="image" src="https://github.com/user-attachments/assets/23b37463-8c8c-4a7a-9b9f-4af3a87738c6" />

The accelerations used in the following calculations are based on data I was able to gather from the the most reputable and trust-worthy sources I could find on the Internet

## Subcase 1 - Heavy Breaking
The car is breaking with a decelaration of $a = 2 \text{ G}$ A longitudinal Force of $10.08 \text{ kN}$ is acting in the `-X` direction
<img width="678" height="97" alt="image" src="https://github.com/user-attachments/assets/3b6f555a-8581-43c5-bb93-736bbe3a616b" />

## Subcase 2 - Sharp Corner
The car is going through a sharp corner at a high rate of speed resulting in a lateral Force of $5.04 \text{ kN}$ acting on the Arm in the `Y` direction

## Results
Subcase 1 at the top ⬆
Subcase 2 at the bottom ⬇

### Displacement and Average Stress
<img width="1536" height="820" alt="image" src="https://github.com/mgrzb451/MiniProject-MacPherson_Strut_Suspension/blob/main/assets/fea_result0.gif" />

### Strain Energy
By examining the Strain Energy contour plots we can determine which areas of the structure will benefit most from increasing stiffness in terms of decrasing the resultant displacements and stress
<img width="794" height="875" alt="image" src="https://github.com/mgrzb451/MiniProject-MacPherson_Strut_Suspension/blob/main/assets/strain_energy0.jpg" />






