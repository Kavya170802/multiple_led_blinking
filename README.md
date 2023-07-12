# multiple_led_blinking
/* 
  This program blinks LED connection to the pin number 13, 12, and 11 
*/  
int red = 13;
int green =12;
int yellow = 11;

void setup()  
{  
  pinMode(red, OUTPUT);  
  pinMode(green, OUTPUT);  
  
}  
void loop()  
{  
 // the first LED is made to blink one time  
  digitalWrite(red, HIGH);  
  delay(1000); // delay time in milliseconds  
  digitalWrite(red, LOW);  
  delay(1000);  
  // the second LED will blink two times  
  digitalWrite(green,  HIGH);  
  delay(500); // the duration is 0.5 seconds  
  digitalWrite(green, LOW);  
  delay(500);  
    
   digitalWrite(yellow,  HIGH);  
  delay(500); // the duration is 0.5 seconds  
  digitalWrite(yellow, LOW);  
  delay(500);  
  
  
    
}  
