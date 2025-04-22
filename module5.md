# Coal Properties and Their Effects on Combustion

## Chemical Composition and Its Impact

### Volatile Matter (VM)

- **Characteristics and Behavior**:
  - Low molecular weight hydrocarbons (present naturally or formed by heating)
  - Exists in gas/vapor phase, enabling better mixing with air through Brownian motion
  - VM combustion releases heat that ignites Fixed Carbon (FC)
  - High VM coal has lower ignition temperature (CH₄ ignites at atmospheric conditions)
  - Low VM coal (Jhama coal, coke, pet coke) has higher ignition temperature

- **Optimal Content**:
  - 20% VM minimum for trouble-free combustion
  - 25-30% VM is ideal; 35% VM is excessive
  - <20% VM may require blending with alternate fuels for proper ignition
  - FC/VM ratio should be ~1 (0.8-1.25) for optimal performance

- **Excessive VM Problems**:
  - Unstable combustion with rapid heat release
  - Excess temperature, tube overheating, refractory damage
  - Difficult fireball maintenance
  - High VM means lower FC content (petroleum products have 100% VM)
  - TGA/DTG curve becomes sharper with lower Ti and Tf

### Fixed Carbon (FC)

- **Characteristics and Behavior**:
  - Very high molecular weight, carbon-rich compounds
  - Residual carbon after heating coal at 925°C for 7 minutes
  - Most H and O released as VM; negligible/zero H content
  - Not pure carbon (FC differs from C in ultimate analysis)
  - Difficult to ignite but burns steadily once ignited
  - Provides stable heat release and smooth combustion
  - Generally contains more energy (GCV) than VM

- **Combustion Profile**:
  - TGA/DTG curve is flatter with higher Ti and Tf
  - Higher FC gives stable combustion/heat release in boilers

### Moisture Content

- **Classification and Properties**:
  - Always present in coal; indicates coal maturity
  - Peat/lignite: high moisture (>15%)
  - Bituminous/anthracite: low moisture (<5%)

- **Effects on Combustion**:
  - During heating, creates vacant pores as it escapes
  - Improves surface area for chemical reactions
  - Oxygen adsorption in pores (minor mass gain in TGA)
  - High moisture coal reacts more easily at higher rates
  - Low moisture coal has higher ignition temperature
  - Combustion behavior results from combined effect of maturity and surface area

### Mineral Matter and Ash

- **Composition**:
  - Inorganic salts of metals, P, S, Cl, etc.
  - Coal: Higher SiO₂, Al₂O₃ (85-95%) with minor Fe₂O₃, CaO, MgO, TiO₂, K₂O, Na₂O, P₂O₅
  - Biomass: Higher alkali oxides (CaO, MgO, Na₂O, K₂O)
  - MM converts to individual oxides during heating/oxidation
  - Alkali oxides cause greater boiler tube corrosion

- **Ash Fusion Issues**:
  - Ash Fusion Temperature (AFT) is a key parameter
  - Melted ash creates operational problems:
    - Sticks to refractory walls, boiler tubes, air valves, flue gas paths
    - Absorbs latent heat during phase change, reducing efficiency
    - Reduces heat transfer to tubes
  - Regular monitoring of ash composition needed
  - Coal sources have different ash compositions

- **Combustion Effects**:
  - Ash layer controls diffusion of O₂ and CO₂
  - Thicker ash layer slows gas diffusion and reaction rates
  - High ash coal has lower combustion and heat release rates
  - Less suitable for high-temperature applications

- **Operational Challenges**:
  - Higher ash reduces combustibles percentage and GCV
  - Increases solid waste generation (fly ash, bottom ash)
  - Creates crushing/grinding difficulties (abrasive, harder coal)
  - High ash coal requires finer grinding (around 50 μm) for efficiency
  - Ash deposits on boiler tubes reduce heat transfer

## Physical Properties and Their Impact

### Particle Size

- **Size Requirements by Process**:
  - Fluidized bed combustion: 2-10 mm particles
  - Pulverized combustion: <75 μm particles
  - Similar sizes for coal gasification

- **Size Trade-offs**:
  - Smaller particles: Higher handling costs, operational difficulty, pollution
  - Larger particles: Uncertain mineral matter/combustible distribution
  - High-temperature applications require smaller particles

- **Combustion Performance Effects**:
  - Larger particles increase ash layer thickness
  - Slower combustion rate and lower heat release
  - Increased unburned carbon
  - Longer residence time needed for complete combustion
  - Higher settling velocity and lower air retention time
  - Require higher air velocity for fluidization/primary air
  - Need effective ash layer removal mechanisms

### Particle Density

- **Composition Relationship**:
  - Higher density correlates with higher ash percentage
  - Generally results in reduced GCV and heat release rate

- **Mill Separation Effects**:
  - Lighter particles are transported to the combustor
  - Heavier particles report to mill reject
  - Primary air velocity designed for specific particle transport
  - Mills separate based solely on weight, not composition
  - Typical cutoff in Indian mills: specific gravity of 1.85
  - Valuable coal with SG >1.85 can be lost to rejects

- **Operational Impacts**:
  - Increases transportation and conveying costs
  - Requires higher primary air/fluidization velocity
  - Forms thicker ash layer during combustion
  - Increases unburned carbon
  - Requires longer residence time
  - Results in higher settling velocity and less air retention
  - Needs special ash removal mechanisms

### Grindability

- **Hardgrove Grindability Index (HGI)**:
  - Critical for pulverization efficiency
  - Grinding must complete within mill residence time
  - Hard coal (low HGI): Requires more grinding time
  - Soft coal (high HGI): Can result in overgrinding

- **Processing Consequences**:
  - Improper grinding increases unburned carbon and hydrocarbon emissions
  - Can increase fly ash generation and ESP load
  - May cause faster heat release if particles are too fine
  - Valuable coal lost if density exceeds design parameters

## Combustion Process Requirements

### Air Supply

- **Fundamental Principles**:
  - Combustion follows Le Chatelier's Principle
  - Coal combustion occurs in steps:
    1. C + O₂ → CO (initial)
    2. CO + O₂ → CO₂ (secondary)
  - Product gas removal drives reaction forward
  - Solid coal + O₂ → various hydrocarbons (H₂, CH₄, etc.) and CO
  - O₂ becomes limiting reactant as reaction proceeds

- **Air Staging**:
  - Primary air: Initial oxygen supply for fuel ignition
  - Secondary/tertiary air: Added at later stages for complete combustion
  - Multiple injection locations ensure complete combustion
  - Secondary air crucial for solid fuels to prevent high CO in flue gas

- **Fuel-Specific Requirements**:
  - Solid fuels: Secondary air essential
  - Liquid fuels: ~10% excess air
  - Gaseous fuels: ~5% excess air
  - Coal: ~20% excess air

- **Thermal Efficiency Factors**:
  - N₂ in air (80%) doesn't participate but absorbs heat
  - Heat loss = m·Cp·(Tout - Tin)
  - Excess air increases heat losses through:
    - Unused O₂ in flue gas
    - Additional N₂ requiring heating

### Combustion Calculations

- **Input Requirements**:
  - CHNSO analysis essential for calculations
  - MM% (1.1 × ash%) + moisture% + CHNSO% = 100%
  - Ultimate analysis on moisture-free coal avoids H source conflicts

- **Calculation Principles**:
  - Based on stoichiometric mole calculations
  - Elements converted from weight to mole basis
  - Key reactions:
    - C + O₂ → CO₂
    - S + O₂ → SO₂
    - 4H + O₂ → 2H₂O
  - Key molecular weights:
    - C = 12, O₂ = 32, S = 32, N₂ = 28
    - CO₂ = 44, SO₂ = 64, H₂O = 18

- **Flue Gas Determination**:
  - Gas composition converted using ideal gas law (PV = nRT)
  - Final flue gas includes:
    - CO₂, H₂O, SO₂ from combustion
    - Excess O₂ from air
    - N₂ from air and fuel

## Key Considerations for Optimal Combustion

- Coal properties significantly impact combustion behavior
- Standard characterization may not reflect actual combustion performance
- TGA/DTG burning profile analysis provides better combustion indicators
- Coal should be:
  - Properly sized for the combustion system
  - Matched to boiler design specifications
  - Supplied with appropriate primary and secondary air
- Inappropriate coal selection results in:
  - Combustion issues
  - Higher environmental pollution
  - Reduced energy efficiency