// C++ code__
//__
int pin2 = 2;__
int pin3 = 3;__
int pin4 = 4;__

void setup()__
{__
  pinMode(pin2, OUTPUT);__
  pinMode(pin3, OUTPUT);__
  pinMode(pin4, OUTPUT);__
}__

void loop()__
{__
  digitalWrite(pin2, LOW);__
  digitalWrite(pin3, LOW);__
  digitalWrite(pin4, LOW);__
  delay(750);__
  
  digitalWrite(pin2, LOW);__
  digitalWrite(pin3, LOW);__
  digitalWrite(pin4, HIGH);__
  delay(750);__
  
  digitalWrite(pin2, LOW);__
  digitalWrite(pin3, HIGH);__
  digitalWrite(pin4, LOW);__
  delay(750);__
    
  digitalWrite(pin2, LOW);__
  digitalWrite(pin3, HIGH);__
  digitalWrite(pin4, HIGH);__
  delay(750);__
    
  digitalWrite(pin2, HIGH);__
  digitalWrite(pin3, LOW);__
  digitalWrite(pin4, LOW);__
  delay(750);__
  
  digitalWrite(pin2, HIGH);__
  digitalWrite(pin3, LOW);__
  digitalWrite(pin4, HIGH);__
  delay(750);__
    
  digitalWrite(pin2, HIGH);__
  digitalWrite(pin3, HIGH);__
  digitalWrite(pin4, LOW);__
  delay(750);__
    
  digitalWrite(pin2, HIGH);__
  digitalWrite(pin3, HIGH);__
  digitalWrite(pin4, HIGH);__
  delay(750);__
}__
