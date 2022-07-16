Release notes


Development notes

5/5/18:
developed a syntax for json snippets, started storing some for the rainbow sheep add on.  expanded the random sheep color set function to include all colors at even distribtuion.  figured out that this is actually creating a component group with the sheep_xxxx (color) for each one.   for rainbow sheep, i only want one new component group sheep_rainbow.  so i need to move the random color assignment to someplace else.  I think moving it to the loot table is best.  then a rainbow sheep can be dyed any color but always gives a random color when sheered.

base funtionality
sheering a sheep calls the sheep_sheer.json loot table, which has simple function that says set the color from the data. but this doesn't explain anythine.

todo
need 1 new component group.
need 1 new action (maybe) sheering a rainbow sheep
need 1 new loot table for rainbow sheep.  replace oob function with random function to set color value directly, ignoring the color value of the rainbow sheep.  thus a pink rainbow sheep can give blue wool, etc.