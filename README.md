# Inches---Feet
Purpose:     convert inches to feet, using fact that there are 12 inches in 1 foot Pre-conditions (input):     number of inches (floating point) Post-conditions (output):     number of feet, floating point with 2 decimals rounded
**def main():
# Design and implementation

# 1. Output a message to identify the program, and a blank line
    print("Conversion of inches to feet")
    print()

# 2. Input amount of inches from user

    int_inches = float(input("How many inches? "))

# 3. Calculate number of feet
    # 12 inches in one foot
    feet = int_inches / 12

# 4. Output resulting feet and given number of inches
    print()
    print(int_inches, "inches is {:.2f} feet".format(feet))
    print()

main()

# end of program file**
