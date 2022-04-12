int REDled = 11;
int GREENled = 10;
int BLUEled = 9;
int POT = A0;
int x;

void setup() {
  Serial.begin(9600);
  pinMode(BLUEled,OUTPUT);
  pinMode(GREENled,OUTPUT);
  pinMode(REDled,OUTPUT);
}

void loop() {
  x = analogRead(POT);
  Serial.println(x);
  if (x<=146){
  analogWrite(REDled,255);
  analogWrite(BLUEled,0);
  analogWrite(GREENled,0);
  }
  else if(x>146&&x<292){
  analogWrite(REDled,233);
  analogWrite(GREENled,17);
  analogWrite(BLUEled,0);
  }
  else if(x>292&&x<438){
  analogWrite(REDled,255);
  analogWrite(GREENled,255);
  analogWrite(BLUEled,15);
  }
  else if(x>438&&x<584){
  analogWrite(REDled,0);
  analogWrite(GREENled,255);
  analogWrite(BLUEled,0);
  }
  else if(x>584&&x<730){
  analogWrite(REDled,0);
  analogWrite(GREENled,191);
  analogWrite(BLUEled,255);
  }
  else if(x>730&&x<876){
  analogWrite(REDled,75);
  analogWrite(GREENled,0);
  analogWrite(BLUEled,130);
  }
  else {
  analogWrite(REDled,172);
  analogWrite(BLUEled,245);
  analogWrite(GREENled,37);
  }

}
