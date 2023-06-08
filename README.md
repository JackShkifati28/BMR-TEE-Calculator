# BMR/TEE-Calculator

## Description
In this program, we are creating a calculator that would measure the Basal Metabolic Rate (BMR) and the Total Energy Expenditure (TEE). BMR is the total number of calories that are burnt when a person is at rest, and the TEE is the total amount that will approximate physical activity. 

Our objective in this program is to create a diet calculator that would measure the BMR by entering the gender, height in feet and inches, age in years, and weight in pounds. However, the BMR formula is in measures of the metric system, so we would first need to write a method that would convert weight from pounds to kilograms (kg), and another method from feet and inches to centimeters (cm). Then, we will write another two methods that would calculate the formulas for BMR and TEE. 

When writing the method for TEE, we will need to use if statements that would set the conditions of the person's activity levels. We are measuring the person's activity level by 3 sets; 1 is light activity (BMR * 1.53), 2 is moderately active (BMR * 1.76), and 3 is vigorously active (BMR * 2.25). The results would give us the total amount of daily calories a person burnt given the conditions of the BMR and TEE.

We have chosen to use a method with a while loop in this program. This loop repeatedly executes a target statement as long as a given condition is true. We have chosen our condition to be if gender equals the character 'M' which represents male, or if character 'F' represents female, or when gender does not equal to character 'X' to exit the loop.

The most challenging part when writing this program was choosing the best way to structure it. There are so many different ways; in fact, I wrote it in two different ways, with both resulting in the correct output. The first version had everything read and printed out in my main method inside the while loop, but I realized that main was way too big. In the second version, I just printed out the results at the end of each method. This gave the same results; it just looked a lot better with the main not being so compacted. Personally, I prefer programs that are more science-related because they not only improve my programming skills but also educate me on the topic.

