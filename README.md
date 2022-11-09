# Microcontroladores - Caixa de Emoções

Integrantes
- André Monteiro Sanches Garcia&emsp;–&emsp;19.01230-6
- Arthur Castanheda Sarnadas&emsp;&nbsp;&emsp;–&emsp;19.00756-6
- Giovanni Brandini B. Benuthe&emsp;&emsp;–&emsp;19.00043-0
- Guilherme Bernardelli Zeigler&emsp;&emsp;–&emsp;19.02453-3

## Projeto
Nosso projeto consiste em um amigo virtual interativo que é muito emotivo.<br/>Suas emoções estarão evidentes onde quer que você esteja então não esqueça de sempre deixá-lo feliz !! 😄

## Objetivos
O objetivo do projeto é estabelecer a configuração de um sistema controlado por raspberry pi e programado em node.js.<br/>
O sistema deve fazer requisições para trocar dados com um dashboard na nuvem Ubidots em tempo real.

## Ferramentas / Hardware
Utilizamos um Raspberry Pi 3 Model B+ acoplado a uma tela touchscreen para Raspberry de 7 polegadas.<br/>
As ferramentas de desenvolvimento foram o Node-Red e scripts de configuração do linux PI OS.<br/>
O dashboard em nuvem foi desenvolvido na própria plataforma Ubidots.

## Metodologia
O projeto foi inicialmente pensado e feito de maneira mais simples para Raspberry PI Pico e migrado para Raspberry PI 3.<br/>
Apesar da programação utilizando Node Red ter sido feita do zero, a ideia do projeto manteve-se e os botões físicos que alteravam as emoções da "EmoBox" converteram-se em botões virtuais.

## Diagrama de Blocos

![Diagrama em branco](https://user-images.githubusercontent.com/79452579/194165596-9e2ce5d2-525a-4607-b50a-4fcba2e127af.png)

## Resultados
O projeto é capaz de abrir o navegador em tela cheia e mostrar ao usuário uma interface interativa, feita com Node Red, com as opções de emoção a serem selecionadas.
Ao selecionar uma emoção o emoji aparece ao lado, correspodendo à emoção escolhida dentre:<br/> Feliz: 😄 Triste: 😔 Medo: 😱 Pensativo: 🤔 e Tímido: 😊<br/>
Simultaneamente um dashboard na nuvem recebe a emoção selecionada e mostra para que essa possa ser vista de qualquer lugar.<br/>
O grupo conseguiu atingir os objetivos propostos e o projeto funciona de maneira fácil, rápida e concisa, sem ter apresentado falhas nos vários testes executados.

## Vídeo (Youtube)
Link para o vídeo explicativo: https://www.youtube.com/watch?v=kir3gmoO1-I


