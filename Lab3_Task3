//Setup Canvas
function setup() {
  createCanvas(400, 400);
}

//Draw Function
function draw() {
  background(220, 130, 130);
  
  //Create 3 different Robots of Different Sizes
  drawRobot(0, 60, 120, 180, 0, 0, 1);
  drawRobot(77, 44, 144, 222, 100, 0, 1.3);
  drawRobot(33, 99, 225, 70, 50, 200, 1.6);
}

//Draw Robot Function
//Takes 4 colors, xposition, yposition and scale
function drawRobot(color1, color2, color3, color4, x, y, Scal){
  //"Rainbow" tiers of conditionals based on mouseY
  if(mouseY < 100){
    fill("hsla(" + color1 + ", 50%, 50%, .7)");
  }
  else if(mouseY >= 100 && mouseY <= 200){
    fill("hsla(" + color2 + ", 50%, 50%, .7)");
  }
  else if(mouseY > 200 && mouseY <=300){
    fill("hsla(" + color3 + ", 50%, 50%, .7)");
  }
  else{
    fill("hsla(" + color4 + ", 50%, 50%, .7)");
  }
  
  //Set translate and scale based on local variables
  push();
  translate(x, y);
  scale(Scal);
  
  //eyes
  ellipse(50, 50, 50);
  ellipse(100, 50, 50);
  ellipse(50, 50, 10);
  ellipse(100, 50, 10);
  //face
  rect(40, 90, 75, 20);
  rect(40, 100, 75, 2);
  pop();  
}
