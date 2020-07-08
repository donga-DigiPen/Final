# Programming Concepts


**cs099**
**Final Project**
**Dong-A Choi**
**Spring 2020**


## Shapes

What: It is shape something like circle

why: if we want to draw some shape like circle, ellipse or square we have to use these shapes function. 

how: circle(xposition,yposition,size)

code: 

       rect(0, 0, this.width, this.height)


## Colors

What: It is color something like red, green, blue….

Why: if we want to use colors we have to use these color function

How: fill(R,G,B,A) , fill(‘—‘)

Code: 

        fill(‘red’)


## Variables

What: where you store a value that can be changed

Why: if we use variables, we don’t have to type all of value change.

How: var = ---, let = ---, const = ---

Code: 

        let monster = 0; let door = 0; doorTimeElapsed = 0


## Conditional Satatements

What: It makes the condition like if()

Why: If we want to get some outcome which depend on the condition, we have to use these.

How: if() {}

else if() {},

switch() {

case 0:

break

}

Code: 

             if(door == 1 && doorTimeElapsed > 5) {

   	 door = 0

  	 doorTimeElapsed = 0

 	 }


## Loops

What: It’s calculate something looping

Why: we can make code about a lot of data simply.

How: for(let a =0; a < 30; a++) {

---

}

Code: 

           for(i=0; i<frames.length; i++) {

            }


## Functions

What: Functions get special values and print them out after calculation

Why: It can help to do soft coding

How: make function like function dig() {} and put dig() in draw()

Code: 

        function mousePressed() 

        {if(mouseX>0 && mouseX<30 && mouseY>200 && mouseY<230) {

        door = 1

        }}


## Classes

What: It’s about structure how to handle data.

Why: By changing one variable, we can change everyting else related to it.

How: class --- {

Constructor() {}

Update() {}

Draw() {}

Code: 

        class MainMenu{

        constructor(){

        const center_x = width / 2;

        this.play = new Button(center_x, height * 2/5, "Play");

        this.howToPlay = new Button(center_x, height * 3/5, "How To Play");

        this.credits = new Button(center_x, height * 4/5, "Credits");

        }

        Update() {}

        Draw() {}

        }


## Arrays

What: set of variables	

Why: when we make too many variables, we have to make variables one by one, but if we use array, we can put them on one variable.

How: for(i=0; i<cols; i++) {

colors[i] = []

for(j=0; j<rows; j++) {

}

}

Code: 
  
              let animation = []

	 for(let I = 0; I < frames.length; i++) {

              let fra = frames[i].frame

              let img = spritesheet.get(fra.x, fra.y, fra.w, fra,h)

              animation.push(img)

              }

