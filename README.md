# Workout progress tracker table generator

This small app is for generating a simple HTML table for an easy printable workout tracking sheet.

Upon running the app, it will create a file named `workout_table.html` on the desktop. It can then be opened by a browser and printed out.

At the beginning of the source file `Program.cs` a few parameters can be set to customize the generated table.

```cs
int columns = 5;
int cells = 14;
string[] repeatingStrings = { "Upper Body", "Lower Body", "Abs"};
```

 - `columns` to set the number of columns of the result table
 - `cells` to set the number of cells of the result table
 - `repeatingStrings` to set the repeated workout titles in the table cells

The above parameters would generate the following table:

![example table](/img/example.png)
