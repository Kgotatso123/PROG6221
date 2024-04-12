# PROG6221

https://github.com/Kgotatso123/PROG6221.git
PART1 PROG6221

This C# code represents a simple console application for managing recipes:

1. Program class: This is the entry point of the application. It contains the `Main` method where the program execution begins. Inside the `Main` method, a `Recipe` object is instantiated to manage recipes. Then, it enters an infinite loop where it continuously prompts the user with a menu of options.

    - Option 1: Enter recipe details.
    - Option 2: Display the recipe.
    - Option 3: Scale the recipe by a factor provided by the user.
    - Option 4: Reset the quantities of ingredients.
    - Option 5: Clear the recipe.
    - Option 6: Exit the program.

2. Recipe class: This class represents a recipe and contains methods to manage its details.

    - Constructor: Initializes arrays for storing ingredient names, quantities, units, and steps.
    - DetailEntry(): Allows the user to enter details of the recipe, including ingredients and steps.
    - DisplayRecipe(): Displays the ingredients and steps of the recipe.
    - ScaleRecipe(double scale): Scales the quantities of ingredients by the provided scale factor.
    - ResetQuantities(): Resets the quantities of ingredients by halving them.
    - ClearRecipe(): Clears all recipe details by resetting the arrays to empty.

To compile and run the software:

1. Copy the provided code into a text editor and save it with a `.cs` extension, for example, `RecipeManager.cs`.
2. Open a command prompt or terminal window.
3. Navigate to the directory where you saved the `.cs` file.
4. Compile the program using the C# compiler. You can use the `csc` command (assuming you have the .NET SDK installed):

    csc RecipeManager.cs

   This command will generate an executable file (`RecipeManager.exe`).

5. Run the compiled executable:

    RecipeManager.exe

   This will start the program, and you can interact with it via the command line interface, following the menu options displayed.
