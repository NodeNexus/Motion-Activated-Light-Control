int pirPin = 7;
int ledPin = 8;

void setup() {
  pinMode(pirPin, INPUT);
  pinMode(ledPin, OUTPUT);
  Serial.begin(9600);
}

void loop() {
  if (digitalRead(pirPin) == HIGH) {
    digitalWrite(ledPin, HIGH);
    Serial.println("Motion detected! Light ON");
  } else {
    digitalWrite(ledPin, LOW);
  }
  delay(500);
}
