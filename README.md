# CIVE202_Spring2026_Group1_Project2_Repo

**Authors:**
Bryce Ripley, Brock Hoover, Ryan Kramer

Repository for CIVE 202 Spring 2026 Group 1 Project 2

The goal of this project is to automate the Nebraska Department of Transportation’s (NDOT) concrete mix design workflow by translating the existing Excel‑based “Mix Design” worksheet into a functional Python program. This process was done improve factors such as reliability, transparency, and repeatability of their concrete mix design process by moving away from the manual spreadsheet calculations and instead have them in a fully code driven system with inputs and outputs calculated automatically. 

This project will recreate the same logic that is used in the NDOT’s excel file that was provided, including material property inputs, water–cement ratio calculations, aggregate proportions, air content adjustments, and final batch weight computations for one cubic yard of concrete. The python code program that will be created will guide the user step by step with structured steps and input prompts to then produce a well formatted summary of the concrete mix design based on the user’s inputs. In addition, four realistic concrete mix scenarios will be researched, documented, and evaluated using the automated workflow that has been created to demonstrate accuracy and consistency. All work will be completed in a transparent, reproducible manner allowing NDOT to verify the results and incorporate this model into their digital tool calculations.  

# How to Use This Code:

1. Install the Jupyter Notebook and run the first two code cells, this will get the code ready for the input stage. 

2. Run the third code cell and input the information as the code tells you to input them.

3. Run the fourth code cell with the NDOT Mix Design Calculations
   
5. Run the fifth code cell to view your mix design calculation summary


Copy the output, which will give you information on the weights of the aggregates based on the inputted requirements, and the amount of water that is necessary, depending on the type of mix you are trying to do, you can refer to the NDOT mix designs standards as seen in this document: 
https://dot.nebraska.gov/media/g4qp4y0d/2017-specbook.pdf

For IP/IT Class 47B concrete, air content will need to be between 6.0% - 9.0%, the maximum water-cement ratio is .45, and the total allowed amount of cementious materials is 564lbs for a 1 cubic yard mix scenario with a acceptable range of total aggregate weight of 2,850 to 3,150lbs a cubic yard with a 30% coarse and a 70% fine split, refer to section 1002 for additional information on what is required

**Optional:**

If you want to run the predefined mix scenarios to see what the results are, run the sixth code cell. 

Scenario 1 is a typical Class 47BD composition, a type of concrete used in applications such as bridge decking
Scenario 2 is a typical Class SF composition, a concrete mix that includes silica fume as cementious material
Scenario 3 is a typical Class 47B composition, this would be the typical mix design used by NDOT for their projects
Scenario 4 is a Class 47B composition with a slightly reduced amount of fly ash, this is used in some NDOT applications
