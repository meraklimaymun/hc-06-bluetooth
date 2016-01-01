const int kirmizipin = 3;
const int yesilpin = 4;
const int mavipin = 5;
String readString;

void setup() {
  Serial.begin(9600);
  pinMode(kirmizipin, OUTPUT); 
  pinMode(mavipin, OUTPUT); 
  pinMode(yesilpin, OUTPUT); 
}

void loop() {
  while (Serial.available()) {
    delay(3);  
    char c = Serial.read();
    readString += c; 
  }
  if (readString.length() >0) {
    Serial.println(readString);
    
    if (readString == "mavi")     
    {
      analogWrite(mavipin, 0);
      analogWrite(kirmizipin, 255);
      analogWrite(yesilpin, 255);
    }
        if (readString == "kirmizi")     
    {
      analogWrite(mavipin, 255);
      analogWrite(kirmizipin, 0);
      analogWrite(yesilpin, 255);
    }
        if (readString == "yesil")     
    {
      analogWrite(mavipin, 255);
      analogWrite(kirmizipin, 255);
      analogWrite(yesilpin, 0);
    }
        if (readString == "beyaz")     
    {
      analogWrite(mavipin, 0);
      analogWrite(kirmizipin, 0);
      analogWrite(yesilpin, 0);
    }
        if (readString == "pembe")     
    {
      analogWrite(mavipin, 0);
      analogWrite(kirmizipin, 0);
      analogWrite(yesilpin, 175);
    }
        if (readString == "mor")     
    {
      analogWrite(mavipin, 150);
      analogWrite(kirmizipin, 155);
      analogWrite(yesilpin, 255);
    }
        if (readString == "sari")     
    {
      analogWrite(mavipin, 255);
      analogWrite(kirmizipin, 0);
      analogWrite(yesilpin, 0);
    }
        if (readString == "turuncu")     
    {
      analogWrite(mavipin, 255);
      analogWrite(kirmizipin, 0);
      analogWrite(yesilpin, 150);
    }
            if (readString == "turkuvaz")     
    {
      analogWrite(mavipin, 0);
      analogWrite(kirmizipin, 255);
      analogWrite(yesilpin, 0);
    }
    readString="";
  } 
}
