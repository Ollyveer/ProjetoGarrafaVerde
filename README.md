#  Projeto Garrafa Verde

Sistema de monitoramento da **temperatura** e da **turbidez** de rios e lagos utilizando Internet das Coisas (IoT).

---

##  Sobre o Projeto

O **Projeto Garrafa Verde** foi desenvolvido com o objetivo de monitorar a qualidade da água por meio da coleta automática de dados de **temperatura** e **turbidez**.

Os dados são adquiridos por sensores conectados a um **ESP32-C3 Mini** e enviados para um **ESP32-S3 Xiao**, responsável pela comunicação com a plataforma **ThingSpeak**, onde as informações podem ser visualizadas em tempo real.

Esse sistema permite o acompanhamento remoto das condições da água, possibilitando futuras aplicações em monitoramento ambiental.

---

##  Objetivos

- Monitorar a temperatura da água;
- Monitorar a turbidez da água;
- Enviar os dados para a nuvem utilizando IoT;
- Exibir os dados em tempo real através do ThingSpeak.

---

#  Componentes Utilizados

 Componente = Função 

 ESP32-C3 Mini = Leitura dos sensores 
ESP32-S3 Xiao = Comunicação com a Internet 
 Sensor SHT31 = Temperatura 
 Sensor de Turbidez DigiKey V1.0 = Medição da turbidez 
 ThingSpeak = Plataforma IoT para armazenamento e visualização 

---

#  Funcionamento

O sistema realiza continuamente a leitura dos sensores.

1. O sensor **SHT31** mede a temperatura da água.
2. O sensor de turbidez mede o nível de partículas presentes na água
3. O ESP32-C3 Mini realiza a aquisição dos dados.
4. As informações são enviadas ao ESP32-S3 Xiao.
5. O ESP32 conecta-se à rede Wi-Fi.
6. Os dados são enviados para o ThingSpeak.
7. O usuário acompanha as medições remotamente através do dashboard.

---


#  Esquema de Ligação

A figura abaixo apresenta a montagem do circuito utilizada durante o desenvolvimento.


![Fluxograma](fluxo.jpg)

---

#  Monitoramento

Os dados enviados podem ser visualizados diretamente na plataforma ThingSpeak.



![dashboard](dashboard.jpg)

Acesse o dashboard público do projeto:
https://thingspeak.mathworks.com/channels/3430238


---

#  Autores

- Bruna
- Giovanna
- Gabryella
- Stefany

---

# Data

21/07/2026

## Esquema de Ligação 

