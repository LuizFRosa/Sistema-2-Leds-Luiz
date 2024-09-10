# Sistema-2-Leds-Luiz

void setup() {
  // Configura o pino 11 como uma saída (para o LED ou outro dispositivo)
  pinMode(11, OUTPUT);
  // Configura o pino 9 como uma saída (para o LED ou outro dispositivo)
  pinMode(9, OUTPUT);
}

void loop() {
  // Acende o LED no pino 11
  digitalWrite(11, HIGH);
  // Aguarda 2 segundos (2000 milissegundos) com o LED aceso
  delay(2000);
  // Apaga o LED no pino 11
  digitalWrite(11, LOW);
  // Aguarda 1 segundo (1000 milissegundos) com o LED apagado
  delay(1000);
  
  // Acende o LED no pino 9
  digitalWrite(9, HIGH);
  // Aguarda 2 segundos (2000 milissegundos) com o LED aceso
  delay(2000);
  // Apaga o LED no pino 9
  digitalWrite(9, LOW);
  // Aguarda 1 segundo (1000 milissegundos) com o LED apagado
  delay(1000);
}
