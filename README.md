# Space


import matplotlib.pyplot as plt

# Provided data
MHz = [0.3, 1, 2, 4, 8, 10]
dB = [-5, -3.9, -1, -2, -13, -10]

# Plotting the graph
plt.figure(figsize=(8, 6))
plt.plot(MHz, dB, marker='o', linestyle='-')

# Adding labels and title
plt.title('Attenuation (dB) per MHz')
plt.xlabel('MHz')
plt.ylabel('dB')

# Display the grid
plt.grid(True)

# Show the plot
plt.show()
