# Sistema-de-temperatura 

**Contextualização:**
ligar o climatizador apenas quando a temperatura ambiente atingir um limite e desligar automaticamente quando o quarto esfriar.

**Explicação:**

**Montagem:**
!<img width="3024" height="4032" alt="image" src="https://github.com/user-attachments/assets/ebf86468-941c-4ee1-871d-a1a2cb844e12" />

**Regra de negócio:**
int limite = 40;
if (temperature > limite ){
digitalWrite(buzzer,HIGH);
delay(1000);
