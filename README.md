# PUSH_BUTTON
Arduino code for push b utton


int readPin = 13;

void setup()
{
  pinMode(readPin, INPUT);
  
  Serial.begin(9600);
}

void loop()
{
  
  
  Serial.println(analogRead(readPin));
   
}

