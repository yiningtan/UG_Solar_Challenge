### UG_Solar_Challenge 
Flexible Learning Week Undergraduate Solar Farm Prediction Modelling Challenge 


## Variables
# temperature_2m (C)
Measures the temperature of the air at a given location and altitude, at 2 metres above ground

# relative_humidity_2m (%)
Measures the amount of water vapour relative to the total amount of water vapour that can exist in the current temperature of the air  

# dew_point_2m (°C)
Measures the temperature at which water vapour in a sample of air (in this case, at 2 metres above ground) at constant barometric pressure condenses into liquid water 

# precipitation (mm)
Measures the amount of water that reaches horizontal ground on the earth’s surface, and is expressed as a vertical depth of water or the water equivalent of solid precipitation

# cloud_cover (%)
Measures the amount of clouds covering the sky (0% means no visible cloud) 
Note: if cloud cover in several layers is fifty percent, then only a low percentage of sky will be visible
Examples:
- low, medium and high cloud cover of 50% each may add up to 100% cloud cover, but not to 150%.
- low and medium cover of 50% or less combined with a high cloud cover of 100% will add up to 100% cloud cover, but can be much more translucent than below a low cloud cover of 80%, 
    depending on the cloud types within the high cloud cover.
- low and medium cloud cover of 50% each may add up to 60% total cloud cover, because some clear sky can still be seen.

# shortwave_radiation (W/m²)
Measures radiation at wavelengths shorter than 4 microns aka solar radiation; heats the Earth's surface but not the atmosphere

# direct_radiation (W/m²)
Measures solar radiation that reaches the Earth’s surface directly without being diffused

# diffuse_radiation (W/m²)
Measures absorbed, scattered and reflected sunlight 

# direct_normal_irradiance (W/m²)
Meausures the amount of solar radiation received per unit area by a surface that is always held perpendicular (or normal) to the rays that come in a straight line from the direction of the sun at its current position in the sky

# global_tilted_irradiance (W/m²)
Measures the total radiation received on a surface with defined tilt and azimuth, fixed or sun-tracking, i.e. the sum of the scattered radiation, direct and reflected, and is a reference for photovoltaic (PV) applications, and can be occasionally affected by shadow

# terrestrial_radiation (W/m²)
Measures the heat radiated from Earth, terrestrial radiation reflected from the overlying opaque atmospheric layer is also absorbed
Note: Atmosphere is heated by long-wave terrestrial radiation 


# Instant values
All instant variables are for the exact time the values is stated, i.e. 100 W/m^2 at 10:00. All other values above are the "backwards value", i.e. 10:00 represents the time interval between 09:00 and 10:00. For production of solar energy, the "backwards value" is more useful as it encompasses the entire duration. 
- shortwave_radiation_instant (W/m²)
- direct_radiation_instant (W/m²)
- diffuse_radiation_instant (W/m²)
- direct_normal_irradiance_instant (W/m²)
- global_tilted_irradiance_instant (W/m²)
- terrestrial_radiation_instant (W/m²)

  
References: 
- https://content.meteoblue.com/en/research-education/specifications/weather-variables/clouds
- https://content.meteoblue.com/en/research-education/specifications/weather-variables/radiation
- https://www.pveducation.org/pvcdrom/terrestrial-solar-radiation

  
