# LarsonScanner

int led1 =12;
int led2 =11;
int led3 =10;
int led4 =9;
int led =8;
void setup() {
  // put your setup code here, to run once:
  pinMode(led1,OUTPUT);
  pinMode(led2,OUTPUT);
  pinMode(led3,OUTPUT);
  pinMode(led4,OUTPUT);


}
  int ledjes =4;
void loop() {
  for(int i = 1; i<=ledjes; i++){
    
    digitalWrite((led + i),HIGH);
    delay(200);
    digitalWrite((led + i),LOW);
  }
 
  for(int i =3;i > 1; i--){
    digitalWrite((led + i),HIGH);
    delay(200);
    digitalWrite((led + i),LOW);
  }

 }
