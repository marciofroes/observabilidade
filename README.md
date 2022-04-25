
# Coletando métricas com Prometheus/Grafana

A observabilidade consiste em acompanhar o estado de execução de um sistema através da externalização de 
seu comportamento em tempo de execução. Ou seja, você deve tornar sua aplicação observável para uma fonte externa e o que deve ser observável da sua aplicação são os comportamentos que importam realmente para a experiência do usuário final.

O monitoramento consiste em acompanhar o estado de um sistema através de eventos registrados e executar ações como resposta a esses eventos. Essas respostas podem ser derivadas de ações reativas e proativas.

## Pré-Requisitos
Esse ambiente sobe uma stack do Docker Compose, então o pré-requisito para esse curso é ter o Docker e o Docker Compose instalado.

Também será necessário o Java — eu sugiro o uso da versão 1.8, o OpenJDK 1.8 