# Define constants
# Average depth of the oceans (in meters)
average_depth_meters = 3688

# Total area of the oceans (in square kilometers)
# 361 million square kilometers (361,000,000 km²)
total_ocean_area_km2 = 361_000_000

# Convert the total area of the oceans to square meters (1 km² = 1,000,000 m²)
total_ocean_area_m2 = total_ocean_area_km2 * 1_000_000

# Calculate the volume of water in cubic meters
total_ocean_volume_m3 = average_depth_meters * total_ocean_area_m2

# Convert the volume to liters (1 cubic meter = 1,000 liters)
total_ocean_volume_liters = total_ocean_volume_m3 * 1_000

# Print the result
print(f"Volume of water in the oceans: {total_ocean_volume_liters:.2e} liters")
# Catalina
