# Coal-Based Power Generation

## Overview of Coal Combustion Technologies

- Pulverized coal combustion (>90% of plants) and Fluidized Bed combustion (<10%) are most commonly used
- Gasification-based plants are very limited in number
- In Pulverized coal combustion units, Run of Mine (ROM) coal or washery middling is used
- Requirements include:
  - GCV > 3500 kcal/kg or ash < 45% in coal
  - High ash content creates difficulties in plant operation and increases cost
  - Grinding of coal to -75 μm is required
  - Coal handling section (CHP) ends at grinding of coal
- Presently biomass pellets are also mixed with crushed coal and ground in mill

### Fluidized Bed Combustion (FBC)

- For high ash coal: reject coal, lignite, coal slurry fines, coal washery tailings, etc. are used in FBC
- Co-firing of other fuels is very easy for FBC: biomass, municipal solid waste, coke powder, etc.
- Crushing of coal to -10 mm is required in FBC
- Coal handling section (CHP) ends at crusher, no grinding required
- Typically, bigger plants of 100 MW or more in single unit are Pulverized fired
- Smaller plants of 5-20-30 MW in single unit are FBC based
- Older plants (installed before 2000) have much lower capacity
- Newer plants have much larger capacity due to improvements in technology

## Coal Handling Plant (CHP)

- CHP receives coal from mines, feed size about 1000 mm
- Coal is unloaded by wagon tripler, trucks, or bottom discharge wagon
- All movement of coal is through conveyor belts (abrasive index is important)
- Coal is either stored in stockpile or directly fed to CHP for crushing and burning
- Initial crushing to below -50 mm, followed by -12.5/3 mm crushing
- Suitable size screens are also placed
- Crushed coal is fed to bunker/silo with storage capacity for 12-18 hour plant operation
- Silos convert the process from batch to continuous mode
- FBC plant CHP ends here, with coal burned directly in the combustor

### Additional Processing for Pulverized Combustion

- From silos, coal is sent to pulverizer (mill) - Hardgrove Grindability Index (HGI) is important
- Primary air is also supplied to blow/transport powdered coal (-75 μm) to combustor (particle density is important)
- Coal is burned in combustor
- After combustion, bottom ash, fly ash, and flue gas are generated
- These are captured by cyclone separator, ESP, flue gas desulfurizer unit, etc. as required
- Fuel oil is used for initial ignition as well as to maintain the desirable flame temperature inside boiler

## Power Generation Principles

- Electricity is induced in varying magnetic field (interaction between electrical coils & magnetic field)
- In a turbine, magnet rotates and electricity is generated in electrical cables
- Rotational movement is created by fluid releasing energy at turbine blades
- Fluid should have high kinetic energy to be released at turbine blades and converted to:
  - Rotational energy → Electromagnetic energy → Electricity
- High temperature steam drives steam turbine in thermal power plant
- Based on Fleming's left hand rule: interaction between electrical coils & magnetic field induces electricity

## Power Plant Operation

- Power plant operates at constant output capacity (e.g., 500 MW)
- Based on design, plant needs constant steam quality (temperature and pressure) and mass flow rate (kg/min) to generate desired power
- Steam is used as operating fluid: medium to transport energy from combustor to turbine
- Steam quantity (mass flow rate) and quality (pressure & temperature) must be maintained by the boiler by burning coal at desirable heat release rate
- Coal must be burned properly with desirable heat release rate (kcal/min)
- Coal's Gross Calorific Value (GCV) is important, but combustion rate is most critical

### Coal Feed Requirements

- Pulverizer must grind coal to -75 μm within desired time (hard coal takes longer for grinding)
- Primary air flow rate must match design to transport coal particles (with desired density) to the boiler
- Coal GCV, combustion rate are all correlated and must be as per design

#### Model Calculation of Coal Feed Rate:
- For 500 MW plant, output is 500 MW (1 MW = 860,420.8 kcal/h)
- Plant overall efficiency (Rankine cycle, generator, etc.): ~40%
- Heat output required = 500 MW ÷ 0.40 (in kcal/h)
- Coal GCV: e.g., 5000 kcal/kg
- Coal feed rate = Heat required ÷ GCV

### Operating Temperatures

- For FBC based plants, temperature is about 850-900°C
- High sulfur coal may be used in FBC unit
- Ash Fusion Temperature (AFT) is important in design of pulverized boiler
- Maximum temperature is decided based on AFT and other parameters
- Super thermal, ultra super thermal plants are classified based on maximum steam temperature and pressure
- Design depends on metallurgical limits of boiler tube material, combustion technology, and grade of coal available

### Power Grid Considerations

- Auxiliary power is required for plant operation and running equipment before plant generates its own electricity
- Grid connectivity is essential - isolated single plants cannot operate
- Electricity peak demand, lean demand, and sudden demand fluctuations are important factors
- Electricity must meet standard requirements (frequency: 50 Hz)

## Boiler Design and Operation

Inside the boiler, water is converted to steam in three different sections:

### Economizer
- Used to increase feed water temperature from ~30°C to about 100°C
- Uses low temperature heat available inside boiler
- Mostly waste heat released from flue gas is utilized here

### Evaporator
- In this zone, water is vaporized from liquid phase to vapor phase
- Only latent heat of phase change is required
- This is a significant amount as latent heat is higher than sensible heat

### Superheater
- In this zone, steam is superheated from about 100°C to desired conditions for the turbine
- Typical conditions around 560°C, 200 bar (varies from plant to plant)
- High temperature flue gas (~1300°C) is used for this purpose

## Working Fluid Characteristics

- Any fluid (gas/vapor/liquid) can be used as working fluid with specific quality parameters
- It must have higher heat transport capacity to transfer energy from boiler to turbine
- High specific heat capacity (Cp), latent heat (λ) allow it to carry more heat with lower temperature differences
- Must be easily available (to meet plant demand), cheap, non-toxic, environmentally friendly, non-corrosive, etc.
- Boiling temperature must match heat transport requirements and turbine profile

### Water as Working Fluid

- Pure water is primarily used in thermal plants for normal cycle
- Mercury (Hg) was used in earlier designs
- Some organic liquids are used in low temperature Rankine cycle (combined cycle plants)
- Water can transport more heat as steam at high temperature and pressure
- Steam temperature vs. enthalpy relationship is important - water must be at high pressure and temperature to transport desired energy
- Changes in steam pressure/temperature can lead to phase change of water from vapor to liquid, which is highly undesirable and can damage the turbine
- Pumps are used to pressurize liquid water and send it to the boiler

## Electricity Generation Process

- Turbines convert kinetic energy available in steam to rotational energy
- Rotor containing armature (electrical cable) rotates near magnetic field
- Due to variations of magnetic field, electricity is induced in armature, converting mechanical energy to electrical energy
- Produced electricity is stepped up - voltage (volts) is increased and current (amps) is reduced as per grid/consumer requirements
- A separate electrical power transmission unit handles this process

## Condenser Function

- Purpose of condenser is to recycle the working fluid from vapor phase to liquid phase
- It removes unused heat from steam and transfers it to cooling tower/nearby water body
- Unused steam must be condensed immediately to increase pressure difference across turbine so it rotates at high speed
- Some water vapor is lost at condenser, so makeup water is continuously added as working fluid

### Water Quality Requirements

- Steam with minerals (dissolved salts, chemicals, organic compounds) can be corrosive at high temperature
- Water is purified to the highest standards (almost pure H₂O, zero Total Dissolved Solids)
- A separate water treatment plant handles this process
- Nearby large water body (river, large lake) is essential
- Similarly, ash handling section, Electrostatic Precipitator (ESP), cyclone, etc. are included for pollution control

## Plant Efficiency

- Efficiency of Rankine cycle is determined by thermodynamics:
  - About 42% to 46% in steam turbine
  - Due to other losses in system, overall efficiency is typically below 35%
  - Well-proven technology, most widely used worldwide
- Overall efficiency = η(boiler) × η(cycle) × η(turbine) × η(generator)
- η = 1 - q₂/q₁ (where q₁ is heat input, q₂ is heat rejected)

### Other Operational Factors

- Auxiliary Fuel: Liquid Fuel, Fuel Oil
- Auxiliary Power Consumption: Electricity consumed in plant operation
- Coal Handling Plant (CHP) also consumes electricity
- Fly ash utilization: Solid waste transferred to other consumers/plants
- Power transmission to grid
- Steam pressure vs. efficiency relationship is important
- Reheating cycle, medium and low pressure turbines: Based on plant complexity/simplicity desired and process control aspects

## Cogeneration

- In many industrial applications, heat or steam is also required for material processing
- In such plants, waste heat or steam released from power generation unit is sent to material processing section
- Plants using fuel for both electricity generation and heat are called cogeneration plants
- This approach increases overall energy efficiency and reduces pollution levels

## Gas Turbine Power Generation

- A gas turbine generates power by burning fuel to create hot gases that rotate the turbine
- Based on Brayton cycle for power production
- Process:
  - Air is compressed by rotor (compressor) and sent to combustor
  - Fuel is burned at high temperature and pressure, generating flue gas
  - Flue gas rotates the turbine, which is connected to generator to produce electricity
  - Some energy generated is used to operate the compressor
- Coal, liquid fuel, gaseous fuel can be used
- Efficiency is about 30-35%
- Advantages: Less installation time and cost, quick start and stop
- Disadvantage: Higher operating cost as it mostly uses liquid/gaseous fuel

## Combined Cycle Power Generation

- Two or more power generation cycles operated in series to increase energy efficiency
- Exhaust energy from one power generation cycle is used in next cycle
- Example: GT+ST cycle
  - First cycle: Gas Turbine (GT) cycle generates electricity
  - Exhaust flue gas is used to generate steam and produce electricity using Rankine cycle (Steam Turbine, ST)
- Other configurations: GT+GT, ST+ST, or ST+GT
- Major advantage: Increased efficiency (e.g., GT (200 MW) + ST (100 MW) is more efficient than GT 200 MW alone)
- Disadvantage: Complex plant operation, higher investment cost
- Dual cycle is also used in many ST-based plants

## Integrated Gasification Combined Cycle (IGCC)

- In IGCC, coal is used to fulfill multiple purposes in a single plant:
  - Coal gasification with removal of pollutants and recovery of valuable resources
  - GT-based power generation
  - ST-based power generation
  - Cogeneration of heat if required

### IGCC Process Flow

- Coal is gasified to produce CO, H₂, CH₄ and other gas mixture (syngas)
- During gasification, recovery/removal of sulfur is carried out
- Syngas is purified to remove H₂S, NH₃, etc.
- Syngas is used as fuel gas in gas turbine
- Electricity is generated in gas turbine
- Exhaust heat is used to generate steam for ST-based power generation
- Heat produced during gasification is used as byproduct for cogeneration of steam or other applications
- In parallel, syngas can also be used for production of chemicals (coal to chemicals)

### IGCC Advantages and Disadvantages

- Advantages:
  - Higher energy efficiency
  - Minimum pollution
  - Production of valuable chemicals
- Disadvantages:
  - Complex network of energy transfer
  - Higher investment cost
  - Multiple products to handle and marketing challenges

## Summary

- Coal is the major fuel used in power generation
- Rankine cycle-based plants are most commonly used
- Gas turbine and combined cycle are less popular despite operational advantages
- Energy efficiency of Rankine cycle is about 42%
- Steam quality is a major concern for power generation, indirectly affecting coal quality and combustion requirements
- IGCC can be used for electricity generation as well as for other downstream plants
- Despite being a cleaner technology compared to direct combustion methods, IGCC is not widely adopted for power generation due to operational complexity