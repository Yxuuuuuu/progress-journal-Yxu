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

@Sep 27
because most people have not finish their lesson and we cannot discuss what type of game we are going to make next, so I just try Godot for today and learn some basic function of it. 

@Oct 1
I keept working on learning Godot, and i create a character that suppose to move up down left right and been able to jump, however there is a bug and I could never run my program. I will keep working on solve this problem next class. 

@Oct 3
I still cannot solve the bug I had last class. I am not sure if it's my laptop's problem, but I will redo everything next class. 

@Oct 4
I redo everything start from the beginning but I still cannot solve the bug I had last class. I ask Alya to share her file with to check if it's my laptop's problem or it's my program's problem. 

@Oct 8
I cannot open Alya's file either, so I just delete and redownload Godot, Roshini helped me to fix the animation (I need to press a button to start the animation), but I was still unable to do the movement, so I will work on that next time. 

@Oct 9
Fieheeda helped me to solve the problem with the movement, I need to add the script to the main class some it can function both at character class and main class. So I kept watching the video and leaned how to add physics to a character or any other object. 

@Oct 10
This class I kept watching the video and did the landscape, I learned how to use the draw function and insert png into the game and add physics to those, also learned how to add different property of lanscape. However due to I was solving that bug I had for 3 class and I was a little behind, so I will work on the video and learn Godot after school. 

@Oct 15
This class I watched the 2 video in the class notebook and discuss what we are doing next with the others. We will use the style of agile because it is quick and efficient, we can divide large project into small pieces so it is easier for us to manage.  

@Oct 18
This class we are doing the requirements assignment to analysis functional requairments for a game, me and Fareedah are doing the movement and landing part. 

@Oct 29
Godot

@Oct 31
portfolio

@Nov 5
Game design, discussion, Godot, portfolio

@Nov 7
Portfolio

@Nov11-15
portfolio

@Nov 26 
godot
