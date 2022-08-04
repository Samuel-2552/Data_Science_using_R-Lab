# Data_Science_using_R-Lab
All Lab experiments of this lab in repo and Introduction to R.

# R Basic Commands:

![image](https://user-images.githubusercontent.com/104893913/182770859-c7068f71-9a7c-40db-a10a-2b7862dab1f7.png)

# Mathematical Operations in R:

![image](https://user-images.githubusercontent.com/104893913/182770976-b3fdd6e2-23bd-43ff-9be3-54d01373df19.png)
 R uses radians rather than degrees so multiply the result by 180 divided by π.
 
 # Assigning Values to Variables:
 
 Syntax: object.name = mathematical.expression
 
 ![image](https://user-images.githubusercontent.com/104893913/182773756-72a5c041-97b3-459f-aec4-8111d75e9bbb.png)

In these examples the '=' sign is used and in some '<-' symbol is used ,this is more flexible than the = sign because you can reverse the direction of the arrow.

# Using combine(c) Command:

Syntax: sample.name = c(item.1, item.2, item.3, item.n)

![image](https://user-images.githubusercontent.com/104893913/182775952-a905d918-2245-412a-be48-383505a5294c.png)

The simplest way to create a sample is to use the c() command. Everything in the parentheses is joined up to make a single item.
When you get larger samples and more values, the display may well take up more than one line of the display, and R provides a number at the beginning of each row so you can see “how far along” you are.
You can incorporate existing data objects with values to make new ones simply by incorporating them  as if they were values themselves.

# Text Items as Data:

Syntax: our.text = c(“item1”, “item2”, ‘item3’)

![image](https://user-images.githubusercontent.com/104893913/182777338-92ddba78-aa12-4314-a37f-2c2a053eca9d.png)

If the data you require are not numerical, you simply use quotes to differentiate them from numbers. 
There is no difference between using single and double quotes; R converts them all to double.
If you mix text and numbers, the entire data object becomes a text variable and the numbers are converted to text.

# Using scan() command:

Syntax: our.data = scan()

# Getting Text as Input:

Syntax: our.data = scan(what = 'character')
