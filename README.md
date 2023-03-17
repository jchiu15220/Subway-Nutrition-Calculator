# Subway-Nutrition-Calculator

An Excel workbook that calculates and displays the nutritional information of a customised sandwich and sides from Subway.

## Sheets
**There are 10 sheets that contain nutritional information for sandwich ingredients and sides.**

6 of these are used in calculations. All the values in these sheets are for a standard 6-inch sandwich or wrap, unless otherwise specified.
- Meat: Nutritional information of sandwich meats
- Bread: Nutritional information of sandwich breads
- Vegetables: Nutritional information of vegetables, both standard size and unit size
- Cheese: Nutritional information of sandwich cheese, both standard size and unit size
- Toppings: Nutritional information of sandwich toppings
- Dressings: Nutritional information of sandwich dressings and seasonings

2 of these are the original nutritional information documents, which were downloaded online from the Subway website.
- OG sheet 1
- OG sheet 2

2 of these are the re-formatted versions of the original documents.
- Cleaned sheet 1
- Cleaned sheet 2

**There are 4 sheets that the user will find relevant.**
- Sandwich UI: Allows user to select sandwich ingredients and displays the sandwich's nutritional information 
- Sides UI: Allows user to select sides, and displays the sides' nutritional information
- Meal UI: Displays the summed nutritional information values of the sandwich and sides
- Nutritional Info: Displays nutritional information of each sandwich ingredient and each side

## Calculators
**Sandwich UI**
1. The user selects their sandwich ingredients in *Sandwich UI*, under Sandwich Form.
2. The user presses the 'Calculate button', and nutritional information is calculated and displayed in nutritional summary tables in *Sandwich UI (Summary), Meal UI (Summary), Nutritional Info*.
3. To clear the sandwich selections, the user can press the 'Clear selections' button.

**Sides UI**
1. The user selects their sides in *Sides UI*, under Sides Form.
2. The user presses the 'Calculate' button, and nutritional information is calculated and displayed in nutritional summary tables in *Sides UI (Summary), Meal UI (Summary), Nutritional Info*.
3. To clear the sides selections, the user can press the 'Clear selections' button.

**Meal UI calculation**
1. The user makes their selections in Sandwich UI and Sides UI, and the selections will automatically appear under Meal in *Meal UI*.
2. The user presses the 'Calculate' button, and the nutritional information of the sandwich and sides is calculated and displayed in *Sandwich UI (Summary)* and *Sides UI (Summary)*, respectively. The sum of these values is also displayed in *Meal UI (Summary)*.
3. To clear the sides selections, the user can press the 'Clear side selections' button.
4. To clear the sandwich selections, the user can press the 'Clear sandwich selections' button.
5. To clear both sandwich and side selections, the user can press the 'Clear all selections' button.
