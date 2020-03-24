##안동대학교 손호민

```
PFont f;
void setup(){
  size(700,500);
  textSize(72);
  f = createFont("굴림",64);
  textFont(f);
}

int i, sp=1;
void draw() {
fill(255,255,80);
background(50,50,50);
text("안동대 컴공 사랑합니다", 0, i);
if(i>700) i=1;
i = i+sp;
}

void keyPressed(){
sp = key-'0'; // 0, 1, 2... 9가 됨

}
```
