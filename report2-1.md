'''
void setup() {
  size(800, 300);
  textSize(100);
}
int i, dir=1, sp=1;
void draw() {
  fill(255,255,80);
  background(50,50,50);
  text("Graphics", i, height/2);
  if(i>width) dir=-1;
  if(i<0) dir=1;
  i = i+dir*sp;
}
void keyPressed(){
  sp = key-'0'; // 0, 1, 2... 9
}
'''
