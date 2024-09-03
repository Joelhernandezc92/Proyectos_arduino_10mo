// C++ code
int counter;
int counter2;
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(10, OUTPUT);
}
void loop()
{
  digitalWrite(13, HIGH);
  delay(4000); // Wait for 4000 millisecond(s)
  digitalWrite(13, LOW);
  delay(0.1); // Wait for 0.1 millisecond(s)
  for (counter = 0; counter < 2; ++counter) {
    digitalWrite(13, HIGH);
    delay(300); // Wait for 300 millisecond(s)
    digitalWrite(13, LOW);
    delay(300); // Wait for 300 millisecond(s)
  }
  digitalWrite(3, HIGH);
  delay(4000); // Wait for 4000 millisecond(s)
  digitalWrite(3, LOW);
  delay(0.1); // Wait for 0.1 millisecond(s)
  for (counter2 = 0; counter2 < 4; ++counter2) {
    digitalWrite(10, HIGH);
    delay(500); // Wait for 500 millisecond(s)
    digitalWrite(10, LOW);
    delay(500); // Wait for 500 millisecond(s)
  }}
