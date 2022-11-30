# Buffer Overflow Atack
*Noviembre 30 de 2022*, Ramón Peinado Ruiz



Buffer overflow o desbordamiento de buffer, es una vulnerabilidad o anomalía donde un programa escribe datos en un buffer*(Región de memoria usada temporalmente para almacenamiento de datos)* y sobrepasa el limite de este mismo sobrescribiendo las posiciones contiguas(*Donde se puede ejecutar codigo malicioso*).



Normalmente este tipo de fallos se usan para ejecutar código en un equipo, en algunos casos llegan a tomar el control del equipo o los convierte en zombies para ataques DoS.



Los atacantes aprovechan esta vulnerabilidad sobrescribiendo espacios de memoria real donde se pueden incluir instrucciones para abrir un shell.

Se puede dar en:

- SO's
- Protocolos

Consecuencias:

- Denegación de servicio del software.
- Tomar control del EIP para ejecutar código.
- Tomar control del EIP desde la cuenta de un usuario con privilegios.



### Registros de CPU

Registros de CPU donde se pueden dirigir el desbordamiento del *buffer*:

- **EIP**: indica la siguiente dirección de memoria que el ordenador debería ejecutar.
- **EAX**: almacena temporalmente cualquier dirección de retorno.
- **EBX**: almacena datos y direcciones de memoria.
- **ESI**: contiene la dirección de memoria de los datos de entrada.
- **ESP**: se usa para referenciar el inicio de un hilo.
- **EBP**: indica la dirección de memoria del final de un hilo.

