# ComputationalThinking_old
Computational Thinking Computational thinking is solving big problems by breaking them into smaller, easier steps. 
import math

# Get the first point
x1 = float(input("Enter x1: "))
y1 = float(input("Enter y1: "))

# Get the second point
x2 = float(input("Enter x2: "))
y2 = float(input("Enter y2: "))

# Calculate the distance
distance = math.sqrt((x2 - x1)**2 + (y2 - y1)**2)

# Show the answer
print(f"Distance: {distance:.2f}")
