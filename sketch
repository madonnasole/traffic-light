
int GreenLed=10;
int YellowLed=11;
int RedLed=12;

void setup() {
pinMode(GreenLed,OUTPUT);
pinMode(YellowLed,OUTPUT);
pinMode(RedLed,OUTPUT);

digitalWrite(GreenLed,LOW);
digitalWrite(YellowLed,LOW);
digitalWrite(RedLed,LOW);

Serial.begin(9600);
}

void loop() {

digitalWrite(GreenLed,LOW);
digitalWrite(YellowLed,HIGH);
digitalWrite(RedLed,LOW);

Serial.println(" Light Mode : Yield ");
delay(1000);

digitalWrite(GreenLed,HIGH);
digitalWrite(YellowLed,LOW);
digitalWrite(RedLed,LOW);

Serial.println(" Light Mode : Go ");
delay(2000);

digitalWrite(GreenLed,LOW);
digitalWrite(YellowLed,LOW);
digitalWrite(RedLed,HIGH);

Serial.println(" Light Mode : STOP ");
delay(2000);
}
