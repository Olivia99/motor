# motor for final 

int leftMotorPin = 3;
int leftMotorSpeed = 150;
int MotorPin = 6;
int MotorSpeed= 150;
void setup(){
  // put your setup code here, to run once:
  pinMode(leftMotorPin, OUTPUT);
  pinMode(MotorPin, OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  analogWrite(MotorPin, 150);
  analogWrite(leftMotorPin, 150);
  
  delay(85);
 
  analogWrite(6,0);
  analogWrite(3, 0);

  delay(950);

 
}






