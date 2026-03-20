# Microsservi-os-com-Spring-Boot-e-RabbitMQ
Este projeto apresenta uma aplicação baseada em arquitetura de microsserviços utilizando Java e Spring Boot, com comunicação assíncrona por meio do RabbitMQ.

A ideia principal é demonstrar como diferentes serviços podem funcionar de forma independente, trocando informações através de mensagens em filas, ao invés de chamadas diretas. Isso torna o sistema menos acoplado, mais organizado e mais fácil de escalar.

No funcionamento do sistema, um serviço atua como produtor, enviando mensagens para o RabbitMQ. Essas mensagens ficam armazenadas em filas até que outro serviço, chamado consumidor, as receba e processe. Esse modelo permite que os serviços continuem funcionando mesmo se algum deles estiver temporariamente indisponível.

Além disso, o projeto ajuda a entender conceitos importantes como mensageria, filas, comunicação assíncrona e divisão de responsabilidades entre serviços, que são muito utilizados em sistemas modernos.
