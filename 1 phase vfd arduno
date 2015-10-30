            // By:
            // Tejeshw Vardhan
            // the frequency will be varied by potentiometer 






            
  const int a=9;
  const int b=10;
  const int pot=A0;
  int v;
      int del()
                {
 
               
                }  
  
        byte arr[]={0,16 ,32, 48 ,63, 79,  94,  109, 123, 137, 150, 163, 175, 186, 196, 206, 215, 223, 231, 237, 243 ,247, 250, 253, 254, 255, 254, 253, 250 ,247 ,243, 237, 231, 223, 215, 206, 196, 186, 175, 163, 150, 137, 123 ,109, 94,  79,  63,  48,  32 , 16,  0 };

        byte arrayb[]={0 , 16 , 32,  48 , 63,  79,  94,  109, 123, 137, 150, 163, 175, 186, 196, 206, 215, 223, 231, 237, 243 ,247, 250, 253, 254, 255, 254, 253, 250 ,247 ,243, 237, 231, 223, 215, 206, 196, 186, 175, 163, 150, 137, 123 ,109, 94,  79,  63,  48,  32 , 16,0};
                       
            
    
   void setup() 
      {
                Serial.begin(9600);
                pinMode(a,OUTPUT);
                pinMode(b,OUTPUT);
   
      }

void loop()
     {
       v=10*analogRead(pot);
       Serial.println(v);
       
               for(byte i=0;i<50;i++)
               {
                analogWrite(a,arr[i]);
                delayMicroseconds(v);
               }
  
               for(byte p=0;p<50;p++)
   
              {
                analogWrite(b,arrayb[p]);
                delayMicroseconds(v);
              }
   
   
        }
                


