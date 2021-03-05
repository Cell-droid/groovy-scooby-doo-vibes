// # groovy-scooby-doo-vibes
// its in the name 


void setup (){

size (600, 600);

background (245, 116, 17);

//noStroke();

}
  

void draw () {

//background (#101010);

fill (random(0, 245), 252,0);

ellipse (random(width), random (height), 10,10);
   
  

fill (random (245), random (245), random (221));

//ellipse (random (width), random (height), 25,25);

ellipse (mouseX, mouseY, 25, 25);

fill (random (236), random (245), random (220));

textSize (100);

text ("ur", 250, 200);
 
 textSize (100);

text ("pretty", 150, 300);
 
 textSize (100);

text ("groovy,", 150, 400);
 
 textSize(100);

text ("man!", 160, 500);
 
 
 saveFrame ("output/celina_herrera-####.png");
  
}
