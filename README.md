# electrical-substations
# Electrical Substation Calculator

print("ELECTRICAL SUBSTATION CALCULATOR")

# Input values
primary_voltage = float(input("Enter primary voltage (V): "))
secondary_voltage = float(input("Enter secondary voltage (V): "))
primary_current = float(input("Enter primary current (A): "))

# Calculate transformer turns ratio
turns_ratio = primary_voltage / secondary_voltage

# Calculate apparent power
apparent_power = primary_voltage * primary_current

# Calculate secondary current for an ideal transformer
secondary_current = apparent_power / secondary_voltage

# Display results
print("\n--- SUBSTATION RESULTS ---")
print("Transformer Turns Ratio =", round