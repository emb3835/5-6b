# 5-6b
class triangl {//float x;//float y;//float size;float speed = 2.5;float x1= 10;float x2= 15;float x3= 20;float y1= 10;float y2= 15;float y3= 10;float a;
triangl(float tempx1,float tempy1, float tempx2,float tempy2, float tempx3 ,float tempy3) {//x = tempX;//y = tempY;a = tempx1;a= tempy1;a = tempx2;a = tempy2;a = tempx3;a = tempy3;
}void move() {x1 -= random(-speed, speed);y2 += random(-speed, speed);x3 += random(-speed, speed);}void display() {triangle(x1,y1, x2,y2, x3 ,y3);}void setColor(){  int v = 255;  float speeds =50;  v += random(-speeds, speeds);  fill(v);}void setSize(){  }}
