# Sistema de monitoramento compatível com dispositivos Apple e o HomeKit utilizando um Raspberry Pi

Esse trabalho aborda o desenvolvimento de um sistema de monitoramento 24 horas que seja compatível com o Iphone e o HomeKit
Autores: Samuel Barros Souza           (RA:20.01044-3);
         Lucas Granja Bernardo         (RA:19.00305-6);
         Lucas Bacich Martins          (RA:19.02421-5);
         Johannes Mattheus Krouwel     (RA:20.01248-9).

# 🚀 Introdução

A proposta desse projeto é a implementação de um sistema de monitoramento 24 horas com o Raspberry Pi a partir do programa OpenSource da HomeBridge. As imagens da câmera podem ser visualizadas através de qualquer dispositivo Apple, como Iphone, Ipad e MacBooks.

# 💻 Componentes Eletrônicos e Diagrama de Blocos

A tabela abaixo indica os componentes utilizados, bem como o preço deles (30/08/2023). Dessa maneira, é possível realizar um levantamento de custos. É importante ressaltar que não foram inclusos dispositivos Apple, mas é um material obrigatório para o sistema.

![Captura de tela 2023-09-11 211616](https://github.com/samuellbs/Camera_Rasp/assets/103770785/b1a81731-6f12-4745-911b-da8c26c12a7a)

A figura abaixo representa o diagrama de blocos do sistema.

![image](https://github.com/samuellbs/Camera_Rasp/assets/103770785/63ca8ebe-0c5a-48c8-9d98-0d1ea1a07e76)

#  ⚙️ Funcionamento do sistema

Para implementação do sistema, utilizou-se o software OpenSource da HomeBridge com a câmera 5mp do Raspberry Pi 4. A primeira etapa para funcionamento do sistema está descrita abaixo:

1. Baixe o Raspberry Pi Imager e o abra;
2. Abra a opção "Operating System" e seleicone "Other specific purpose OS";
3. Selecione a categoria de "Automação Residencial";
4. Selecione "HomeBridge, logo depois selecione o SD Card e escreva.

A segunda etapa é realizar a conexão do aplicativo da HomeBridge com o WiFi do local que o sistema será implementado. Desse modo, realizou-se os seguintes passos:

1. Ligar o Raspberry Pi 4 com teclado, mouse e monitor;
2. Realizar o login no programa HomeBridge, utilizando o nome de usuário Pi e a senha Raspberry;
3. Estabelecer a conexão WiFi (apenar a de 2.4GHz);
4. Logo depois de estabelecer a conexão, o programa fornece um código de oito dígitos que deve ser anotado;
5. No dispositivo Apple, o aplicativo "Casa" deve ser aberto e selecionar no campo superior "Adicionar Acessório";
6. Ao clicar em "Adicionar Acessório", é necessário digitar o código anotado na etapa 4;
7. O programa reconhece dois dispositivos (Raspberry Pi Câmera e HomeBridge).
8. A conexão foi realizada com sucesso.
   
Por fim, as imagens capturadas pela câmera podem ser visualizadas em tempo real de duas maneiras. A primeira é pelo aplicativo "Casa" ou pode ser acessada pelo "Centro de Controle" em qualquer dispositivo Apple vinculado ao mesmo ID Apple. Como também, realizamos a impressão 3D de uma case para proteger a câmera e melhorar sua estética. Abaixo estão imagens e vídeos que demonstram o funcionamento.

![case_1](https://github.com/samuellbs/Camera_Rasp/assets/103770785/f286963a-6cc2-4802-a0fa-77a4caf6faab)

![case_2](https://github.com/samuellbs/Camera_Rasp/assets/103770785/498979ed-6fc3-4ccb-96a0-06bf865ee50d)

https://github.com/samuellbs/Camera_Rasp/assets/103770785/f57c22b2-374b-4981-b463-2f1e159b3a97




