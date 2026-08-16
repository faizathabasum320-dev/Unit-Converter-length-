# Unit-Converter-length-
Converts between meters, feet, inches, and kilometers
factors = {"m": 1, "km": 1000, "ft": 0.3048, "in": 0.0254}
v = float(input("Value: "))
frm = input("From (m/km/ft/in): ")
to = input("To: ")
meters = v * factors[frm]
print(round(meters / factors[to], 4))
