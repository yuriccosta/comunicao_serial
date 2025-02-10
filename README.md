
# Comunicação serial

Este projeto demonstra o uso de um display OLED SSD1306 controlado via I2C utilizando a placa Raspberry Pi Pico. Além disso, o projeto inclui a manipulação de uma matriz de LEDs WS2818B e a leitura de botões para interações.

## Estrutura do Projeto

- `inc/ssd1306.h`: Definições e declarações para o controle do display SSD1306.
- `inc/ssd1306.c`: Implementação das funções para controle do display SSD1306.
- `DisplayC.c`: Código principal que inicializa o display, configura os LEDs e os botões, e gerencia as interações.
- `animacao_matriz.pio.h`: Biblioteca PIO para controle dos LEDs WS2818B.

## Uso

- **Interação com Botões**:
  - Pressione o botão A para alternar o estado do LED verde e atualizar o display com a mensagem correspondente.
  - Pressione o botão B para alternar o estado do LED azul e atualizar o display com a mensagem correspondente.

- **Interação via USB**:
  - Conecte a Raspberry Pi Pico ao computador via USB.
  - Envie caracteres via terminal serial para exibir números na matriz de LEDs e caracteres no display OLED.

## Vídeo de Demonstração
Assista à demonstração do projeto em execução:  
[Vídeo Demonstrativo](https://youtu.be/Sk6ZKTkPAhQ)  
