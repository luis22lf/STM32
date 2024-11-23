# **PULL UP e PULL DOWN nas GPIOS**

* PULL UP usado quando GPIO é configurado como ENTRADA e o sinal para reconher acionamento é nível baixo "0"
* PULL DOWN usado quando GPIO é configurado como ENTRADA e o sinal para reconher acionamento é nível alto "1"

É feito isso porque, ao configurar a GPIO como entrada, para o microcontrolador, existe um limiar de tensão que ele não sabe se é nível alto ou baixo.


# **PWM**

* Prescaler -> divisor que reduz a frequência do clock de entrada do temporizador.
Aqui no prescaler é usado um valor que torne as contas mais convenientes 	

 
* Frequencia do contador = Clock / (Prescaler + 1)

 
* ARR -> Contador do temporizador. Ele DETERMINA O PERÍODO da forma de onda (tempo de um ciclo).
	ARR = 1 / Frequencia desejada PWM / (1 / Frequencia do contador)


* Duty cycle % -> Porcentagem do período em que fica em nível lógico alto.
  
  Valor em razão do ARR
  
	_ex: Para um ARR de 1000, 50% de duty cycle é 500._
