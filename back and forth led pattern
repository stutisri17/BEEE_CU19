void setup()
{
  for(int i=10;i<=13;i++)
  {
    pinMode(i,OUTPUT);
  }
}


void loop()
{
  for(int i=10; i<=13; i++)
  {  allLEDSoff();
     if(i!=13)
     {
      digitalWrite(i,HIGH);
       delay(200);
       allLEDSoff();
       digitalWrite(i+1,HIGH);
       delay(200);
       allLEDSoff();
       digitalWrite(i,HIGH);
       delay(200);
     }
   else{
          digitalWrite(i,HIGH);
          delay(200);
           allLEDSoff();
           digitalWrite(i-3,HIGH);
           delay(200);
           allLEDSoff();
          digitalWrite(i,HIGH);
           delay(200);
   }
  }
}

 void allLEDSoff()
 {
   for(int i=10; i<=13; i++)
   {
    digitalWrite(i,LOW);
   }
      delay(200);
 }  
