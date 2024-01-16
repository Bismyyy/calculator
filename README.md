# Initial amount of money
money = 50

# Cost of the item
cost = 15

# Tax rate
rate = 0.03

# Calculating the total cost including tax
total_cost = cost + (cost * rate)

# Calculating the remaining money after purchasing the item
remaining_money = money - cost

# Print the results
print(f"money: ${money}")
print(f"cost: ${cost}")
print(f"rate: {rate * 100}%")
print(f"Total cost (including tax): ${total_cost:.2f}")
print(f"Remaining money after purchase: ${remaining_money:.2f}")
