# IOT
Code 1:


void setup() {
  // put your setup code here, to run once:
  pinMode(D3, OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  digitalWrite(D3, HIGH);
  delay(1000);
  digitalWrite(D3, LOW);
  delay(2000);
}


Code 2:

void setup() {
  // put your setup code here, to run once:
  Serial.begin(115200);
}

void loop() {
  // put your main code here, to run repeatedly:
  Serial.printIn("Hallo!");
}

