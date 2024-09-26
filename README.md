# progress-journal-Yxu

@ Sep 6 2024
The environment we pick is Godot, and the language we are going to learn is C#. I am going to learn that through Codecademy. 


@ Sep 10 2024
Due to there are no totorial for C# using Godot, so we changed our idea and decided to learn GDscript instead. We used the "GDScript from 0" to learn that. 
I learned how to draw some basic shapes: 
  move forward()
  rotate()
also learned how to create a function by
  func name (parameter):


@ Sep 12 2024
I kept learning on GDscript. I learned how to create and define a variable and how to edit it by + - * /
  var name = 10
  name*=10
  name-=5
  var word = 'hello'
var in GDScript can be in many format include number and words. 
I learned the special varible 'delta' which can help to overcome the frame difference in different computers. Also we can use delta to create a loop: 
  func process(delta):
Also I learned how to use a if statement and '>' '<' '==' '!='
  if x>y
    y++


@ Sep 12 2024
I kept study GDScript. I learned the new code: 
  vector2(x,y)  //it can edit x value and y value at the same time, both the scale and position
  cell.x+=1  //infinite loop that add 1 to x
  while x>y  //while loop, if the statement is true, it will keep running
  for x in range(3)  //for loop, if the statement is ture it will keep running. in this example it will run if x <=2
  range(n)  //create a list from 0 to n-1
  array[x,y,z]  //create an array that contain x y and z
  for x in[a,b,c]  //create an for loop with an array


@ Sep 20 2024
I kept learning GDScript. I learned the new code:
  var name=[Vector2(a,b),Vector2(c,d)]  //create an array of vector2
  for cell in array:
    x.move_to(cell)  //create a for loop that moves through an array
  character  //a variable of character
  for character in "hello": //print all characters in "hello"
    print(character)
  round(decimal) //round a decimal, <0.4=0, >=0.5=1
  get_local_mouse_position()  //get the mouse position
  array.append(x)  //add x to array
The lesson is getting harder. lerp(), convert_to_world_corrdinates() are some code that I am confused with. 

@ Sep 24 2024
I kept learning GDScript. I am 3 lessons away from finish. I learned the new code:
  //Return the corresponding screen coordinates at the center of the cell.
  func convert_to_world_coordinates (cell):
    return cell*cell_size + cell_size / · 2
  append()  //appeend the first thing in an array
  pop_front()  //remove the first thing in an array
  pop_back() //remove the last thing in an array
  array_name [index] //get the value at index+1 in array 

@ Sep 26
I finished all lessons for GDScript. I learned the new code:
  //set the value of an object in an array
  var inventory = 
  {
    "shield": 5,
    "healing heart": 3,
    "sword": 1,
  }
  //edit the value of the object in the array inventory
  inventory["object"] += 1
  //for loop, print all items in the array inventory
  for item_name in inventory:
    print(item_name)
I also learned value types, even though they are all called var, but you cannot add an int with an String
  float=1.0: decimal
  int=1: integer
  String"Hi": word
  Vector2()=Vector2(10,10): vector with 2 variables
