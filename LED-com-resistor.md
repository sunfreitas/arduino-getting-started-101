  ## Acendendo um LED com a placa Arduino UNO
  
  ```
  void setup(){
  
    // A função pinMode informa ao Arduino qual pino será utilizado 
    // e sua função (entrada ou saída de energia).
    // Estamos configurando o pino 10 para saídad e energia.
    
    pinMode(10, OUTPUT);
    
  }
  
  void loop(){
    // Liga o LED
    digitalWrite(10, HIGH);
    
    //
    delay(2000);
    
    // Desliga o LED
    digitalWrite(10, LOW);
    
    //
    delay(500);
  }
  ```
  
  ### Excutando o código
  
  Antes de vermos o nosso primeiro código funcionando é preciso realizar algumas configurações. Vá no menu **Ferramentas**, 
  clique no item **Placa Arduino\/Genuino** e escolha o modelo do seu Arduino na lista.
  
  Em seguida, ainda no menu **Ferramentas**, clique no item **Porta** e selecione a porta utilizada pelo Arduino
  no seu computador.
