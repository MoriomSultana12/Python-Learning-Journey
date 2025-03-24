## Question 1 : Write a program to prompt the user for hours and rate per hour using input to compute gross pay. Pay the hourly rate for the hours up to 40 and 1.5 times the hourly rate for all hours worked above 40 hours. Use 45 hours and a rate of 10.50 per hour to test the program (the pay should be 498.75). You should use input to read a string and float() to convert the string to a number. Do not worry about error checking the user input - assume the user types numbers properly.


hrs = input("Enter Hours:")    # Prompt for hours input
hrs = float(hrs)               # Convert input to float

rate = input("Enter the rate:")    # Prompt for rate input
rate = float(rate)                 # Convert input to float

# Check if hours are greater than 40 to calculate overtime
if hrs > 40:
    overtime_hrs = hrs - 40                        # Calculate overtime hours
    overtime_pay = overtime_hrs * (rate * 1.5)     # Calculate overtime pay
    regular_pay = 40 * rate                        # Calculate regular pay
    gross_pay = regular_pay + overtime_pay         # Total gross pay
else:
    gross_pay = hrs * rate                         # Calculate gross pay if no overtime

print("Pay:", gross_pay)                           # Print the total pay
