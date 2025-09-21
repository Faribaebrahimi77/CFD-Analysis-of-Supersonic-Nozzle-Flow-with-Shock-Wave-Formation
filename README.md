# CFD-Analysis-of-Supersonic-Nozzle-Flow-with-Shock-Wave-Formation
Comprehensive CFD analysis of supersonic flow in a convergent-divergent nozzle investigating shock wave formation, flow separation, and the effects of varying back pressure conditions on nozzle performance.
<img width="499" height="314" alt="image" src="https://github.com/user-attachments/assets/c2c5bdb0-aa70-469c-a8a2-3a9bdca876d1" />
🏗️ Nozzle Configuration

Geometry Type: Convergent-Divergent (C-D) Nozzle
Flow Regime: Compressible, supersonic flow
Operating Conditions: Multiple back pressure ratios
Mach Number: Designed for supersonic exit conditions
Analysis Focus: Shock wave characteristics and flow behavior
<img width="631" height="605" alt="image" src="https://github.com/user-attachments/assets/0291c890-e3ad-4f67-8676-81b061fbcb60" />
Multi-Condition Analysis
The study examines three distinct operating scenarios with varying back pressure conditions:
Case 1: Over-Expanded Flow (Low Back Pressure)

Flow Characteristics: Supersonic flow throughout divergent section
Exit Conditions: Under-expanded jet formation
Shock Structure: External oblique shocks at nozzle exit
Performance: Maximum thrust but potential flow instability

Case 2: Shock-in-Nozzle Flow (Moderate Back Pressure)

Flow Characteristics: Normal shock wave inside divergent section
Shock Location: Variable position based on pressure ratio
Flow Transition: Supersonic to subsonic across shock
Exit Conditions: Subsonic flow with pressure recovery

Case 3: Separated Flow (High Back Pressure)

Flow Characteristics: Flow separation due to adverse pressure gradient
Separation Point: Downstream of shock wave location
Flow Structure: Recirculation zones and unsteady behavior
Performance: Significant thrust loss and flow instability

Critical Flow Parameters

Pressure Ratio Analysis: P_back/P_total effects on flow structure
Mach Number Distribution: Supersonic acceleration and deceleration
Shock Wave Characterization: Normal shock strength and location
Flow Separation Criteria: Adverse pressure gradient limits

📊 Key Analysis Objectives
Shock Wave Analysis

✅ Shock Location Prediction: Position vs. back pressure relationship

✅ Shock Strength: Pressure jump and Mach number change

✅ Flow Recovery: Downstream pressure and velocity profiles

✅ Shock Stability: Steady vs. unsteady shock behavior

Flow Separation Investigation

✅ Separation Onset: Critical back pressure determination

✅ Separation Zone Characteristics: Recirculation pattern analysis

✅ Wall Pressure Distribution: Separated flow pressure signatures

✅ Reattachment Analysis: Flow recovery downstream

Performance Metrics

✅ Thrust Coefficient: Nozzle propulsive performance

✅ Discharge Coefficient: Mass flow efficiency

✅ Pressure Recovery: Total pressure losses

✅ Flow Uniformity: Exit flow quality assessment

🛠️ CFD Methodology
Numerical Approach

Solver Type: Density-based compressible flow solver
Turbulence Model: k-ω SST for viscous effects
Shock Capturing: High-resolution schemes for discontinuities
Time Integration: Steady-state with unsteady capability for separation

Boundary Conditions

Inlet: Total pressure and temperature specification
Outlet: Back pressure variation (multiple cases)
Walls: Adiabatic no-slip conditions
Symmetry: Axisymmetric or 2D planar flow

Grid Strategy

Mesh Type: Structured grid with shock refinement
Shock Resolution: Fine mesh near expected shock locations
Boundary Layer: Near-wall clustering for viscous effects
Adaptive Refinement: Dynamic grid adaptation for shock tracking

📊 Key Analysis Parameters
Flow Properties

✅ Mach Number Distribution: Subsonic to supersonic transition

✅ Pressure Ratio: Total to static pressure variations

✅ Temperature Distribution: Compressibility effects

✅ Density Changes: Compressible flow characteristics

✅ Velocity Profiles: Flow acceleration through nozzle
