# **PULL UP e PULL DOWN nas GPIOS**

* PULL UP usado quando GPIO é configurado como ENTRADA e o sinal para reconher acionamento é nível baixo "0"
* PULL DOWN usado quando GPIO é configurado como ENTRADA e o sinal para reconher acionamento é nível alto "1"

É feito isso porque, ao configurar a GPIO como entrada, para o microcontrolador, existe um limiar de tensão que ele não sabe se nível alto ou baixo.
