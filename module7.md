# Coal Combustion Pollutants and Environmental Impact

## Types of Pollutants

### Solid Waste
- **Coal Ash**: Solid residue after combustion (solid waste materials from power plant)
  - **Bottom Ash**: Heavier ash particles that settle down
  - **Fly Ash**: Lighter ash particles that flow with flue gas
  - Chemical composition differs between bottom ash and fly ash
  - Contains various metal/non-metal oxides, some toxic and harmful to environment
  - Contributes to air, soil, and ground water pollution
  - Distribution varies based on combustion methods

### Emissions to Atmosphere
- **Particulate Matter**
  - PM10 and PM2.5 (power sector contributes 7% of PM2.5)
  - Biomass combustion releases nano-sized ash particles
  
- **Gaseous Pollutants**
  - **Sulfur Oxides (SOx)**: Power sector accounts for 51% of SO₂ emissions
  - **Nitrogen Oxides (NOx)**: Power sector accounts for 20% of emissions
  - **Carbon Dioxide (CO₂)**: Power sector accounts for 43% of emissions
  - **Unburned Hydrocarbons**:
    - Present in flue gas as tar, CO, hydrocarbons
    - Present in bottom ash and fly ash
  - **Heavy Metals**: Present in coal ash and emissions

## Environmental and Health Impacts

- **Air Quality Impacts**:
  - SOx, NOx, and mercury undergo chemical reactions to form compounds
  - These compounds can travel long distances (transport characteristics of air)
  - Severe negative impacts on human health from ambient air pollution
  
- **Health Effects**:
  - Fine particles and compounds contribute to death and serious respiratory illness
  - Causes asthma, chronic bronchitis, and other respiratory conditions

## Energy Generation Context
- As of May 2023, 50.7% of India's total installed capacity was coal-based
- Including other fossil fuels (diesel and gas), total fossil fuel capacity reaches about 56.8%

## Incomplete Combustion Issues

### Causes of Unburned Carbon in Ash
- Unburned carbon originates from incomplete combustion of coal due to various reasons:
  - Inadequate O₂ supply during combustion (limiting reactant)
  - Improper mixing of coal and air
  - Insufficient residence time in combustion zone (particles escape before complete combustion)
  - Particle density issues:
    - Very low density particles escape directly to flue gas exit
    - Very high density particles easily settle down in bottom ash
  - Coal characteristics factors:
    - Lower volatile matter causing delayed ignition (high difference between Ti and Tf)
    - Higher fixed carbon requiring longer combustion time
    - Higher burnout temperature of coal (flat DTG curve)
    - Larger coal particles (insufficient residence time)
    - Ash layer inhibiting gas diffusion

### Causes of Unburned Hydrocarbons in Flue Gas
- Unburned hydrocarbon gases/vapors like CH₄, H₂, aromatic and aliphatic compounds, along with CO may be present in flue gas due to:
  - Inadequate oxygen supply (primary cause)
  - Low combustion temperature
  - Excess primary air without secondary/tertiary air supply
  - Delayed combustion (higher ignition temperature of coal)
  - Insufficient time/oxygen for volatile matter combustion
  - High primary air velocity
  - Mismatch between coal characteristics and combustor design
  - Improper mixing of coal and air

## Combustion System Diagnostics

### Flue Gas Analysis
- Functions like a "blood test" for combustion systems
- Key components analyzed: CO₂, O₂, N₂, CO, HC, H₂, NOx, SOx

### Interpreting Flue Gas Results
- **Complete Combustion**: Presence of only CO₂, SOx
- **Incomplete Combustion**:
  - Presence of CO indicates incomplete combustion
  - Presence of H₂, HC confirms incomplete combustion
- **Other Indicators**:
  - N₂ is normal (originates from air)
  - NOx indicates excessive temperature in combustor
  - O₂ indicates excess air used or incomplete mixing of coal and air
  - Combined presence of CO and O₂ signifies major problems in combustion system

## Fly Ash Characteristics and Management

### Fly Ash Properties
- Particle size distribution of feed coal and fly ash particles is most important
- Pulverized coal is burned at <75 μm (maximum size, with 80% particles less than 75 μm)
- For coal with 30% ash content, residue coal particle size should theoretically be 22.5 μm (75×0.3)
- In actual practice, as mineral matter distribution in coal is not uniform, most ash particles are less than 10 μm
- Composition of mineral matter or fly ash is important as it may corrode or damage equipment

## Air Pollution Control Technologies

### 1. Cyclone Separator

#### Operating Principle
- Primarily works on centrifugal force (f = m·v²/r)
- Mass of particle (m) depends on density and size/diameter of particle

#### Efficiency Factors
- Larger particle diameter → higher centrifugal force → better collection efficiency
- Smaller particle diameter → lower centrifugal force → particles exit with flue gas
- Higher particle density → better separation
- Lower particle density → poorer separation
- Larger cyclone diameter → lower centrifugal force → lower separation efficiency

#### Performance Metrics
- **Collection efficiency**: Mass percentage of ash particles collected at bottom
- **Cut diameter**: Particle size in flue gas collected with 50% collection efficiency

#### Cut Diameter Formula
- d₅₀ = (9μBc / 2πNvi(ρp - ρ))^(1/2)
- Where:
  - μ = viscosity (Pa-s)
  - Bc = inlet width (m)
  - N = effective number of turns (5-10 for common cyclone)
  - vi = inlet gas velocity (m/s)
  - ρp = particle density (kg/m³)
  - ρ = gas density (kg/m³)
- Key parameters: Inlet gas velocity, cyclone diameter, particle density, viscosity of air

#### Advantages
- Overall cost of separation is low
- No operating cost, only installation cost
- Effective for larger ash particles (>10 micron)
- Can operate at higher temperatures, making them suitable for flue gas purification
- Can be constructed from ceramic, metals, and other durable materials
- Reduces load on downstream equipment like bag filters or ESPs by removing larger particles
- Very cost-effective solution

### 2. Bag Filter / Fabric Filter

#### Operating Principle
- Used in air purification by filtering the air through porous fabric
- One cloth/similar material with pores separates dust particles
- Flue gas is forced through the filter, with dust particles collected on the fabric surface

#### Performance Characteristics
- Very high collection efficiencies (about 99.9%) for both coarse and fine particles (0.01-100 μm)
- Fabric requires replacement every 2-4 years
- Hot gases must be cooled; operates in temperature range of 120°C-180°C
- Efficient for micron or nano-sized particles, depending on filter media
- Can be modified with ceramic or metallic filter in modern designs

#### Limitations
- Can only be used with low-temperature flue gas
- Not common in thermal power plants, more common in other coal-based industries
- Cannot operate at higher temperatures due to fire hazard
- Temperature increases may cause fire
- Should be used after cyclone separator and waste heat recovery
- Requires regular cleaning via shaking mechanism, vibration, or pulse jet

#### Design Parameters
- Pressure drop
- Air-to-cloth ratio
- Collection efficiency
- Fabric type
- Cleaning mechanism
- Temperature control
- Bag spacing
- Compartment design
- Space requirements and cost

### 3. Electrostatic Precipitator (ESP)

#### Operating Principle
- Utilizes electricity (high voltage DC) to capture ash particles
- Electrodes at high voltage create corona effect (ionized atmosphere)
- Corona effect charges passing particles
- Charged particles experience transverse electrostatic force pulling them toward collecting plates
- Plates periodically "rapped" (vibrated) to make collected particles fall into receiver basket

#### Process Flow
- Fly ash particles pass through electrodes
- Particles get charged due to corona effect and move to collector plates
- Collector plates carry opposite charge to particles
- Particles attracted to collector plates, removing them from gas stream
- Deposited particles occasionally removed by rapping or washing collector plates

#### Efficiency Formula
- η = 1 - e^(-wA/Q)
- Where:
  - η = fractional collection efficiency
  - w = drift velocity (m/min)
  - A = available collection area (m²)
  - Q = volumetric flow rate (m³/min)

#### Advantages
- Very high separation efficiency (99.9-100%)
- Low pressure drop
- Can handle high ash particle loads
- Can operate at higher temperatures
- Most efficient for thermal power plants, cement plants, etc.
- Often used with cyclone separator for cost-effective separation

#### Limitations
- Higher operating and installation costs
- Lower efficiency for smaller ash particles without increased voltage/electricity
- Efficiency depends on ash composition (electron affinity varies with molecules)
- ESP efficiency may vary if coal source changes

### 4. Settling Chamber / Tank

#### Operating Principle
- Used for larger ash particles at lower temperatures
- Water improves particle mass, causing faster settling (dry chambers have lower efficiency)
- Can add chemicals to water to remove gaseous pollutants if needed
- Ash particles captured in water slurry through slurry tank

#### Limitations
- Lower efficiency for smaller ash particles
- Requires efficient sprinklers with surface modifier addition for smaller particles
- Only larger ash particles can be effectively removed
- Dry settling tanks have lower efficiency but don't consume water
- Higher water consumption in wet/spray methods
- Low installation cost but higher operating and maintenance costs

### 5. Wet Scrubbers

#### Operating Principle
- Used for particles 0.2 mm or larger
- Works by spraying fine liquid droplets into incoming gas stream
- Droplets capture particles, liquid is then removed for treatment
- Rectangular or circular chamber with mounted nozzles
- Optimized droplet size (smaller droplets provide better cleaning)
- Polluted spray collected, particles settled out, liquid recycled

#### Advantages
- Can handle high-temperature gas (higher water consumption)
- Can handle high particle loading
- Loading fluctuations don't affect removal efficiency
- Can handle explosive gases with minimal risk
- Gas adsorption and dust collection handled in single unit
- Corrosive gases and dusts neutralized

#### Limitations
- High corrosion potential
- Effluent scrubbing liquid creates water pollution issues

### 6. Venturi Scrubber

#### Operating Principle
- Dirty gas enters chamber at high inlet velocities
- Liquid at low pressure added to gas stream at inlet throat
- Achieves efficiency around 95% for particles larger than 0.2 mm

## Comparative Analysis and Best Practices

- Cyclone separators most efficient for larger ash particles
- ESP and bag filters achieve nearly 100% efficiency but have higher costs
- ESP efficiency varies with ash composition
- Settling tanks/spray methods best for larger particles, especially in FBC plants
- Combination of 2-3 equipment types used to optimize cost efficiency
- Feed size coal and ash particle size must be continuously monitored for efficient ash removal