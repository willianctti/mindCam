# MindCam - Detecção de Objetos em Tempo Real

## Descrição

MindCam é uma aplicação web que utiliza inteligência artificial para detectar objetos em tempo real através da webcam do usuário. Desenvolvida com React e TensorFlow.js, esta aplicação demonstra o poder da visão computacional e do aprendizado de máquina diretamente no navegador.

## Funcionalidades

- Captura de vídeo em tempo real da webcam do usuário
- Detecção de objetos utilizando o modelo COCO-SSD
- Visualização dos objetos detectados com retângulos delimitadores e rótulos
- Processamento em tempo real para uma experiência interativa

## Tecnologias Utilizadas

- React.js
- TensorFlow.js
- COCO-SSD (modelo de detecção de objetos)
- Webcam API

## Como Executar

1. Clone este repositório:
   ```
   git clone https://github.com/seu-usuario/mindcam.git
   ```

2. Entre no diretório do projeto:
   ```
   cd mindcam
   ```

3. Instale as dependências:
   ```
   npm install
   ```

4. Inicie a aplicação:
   ```
   npm start
   ```

5. Abra o navegador e acesse `http://localhost:3000`

## Estrutura do Projeto

- `src/App.js`: Componente principal da aplicação
- `src/utilities.js`: Funções utilitárias para desenhar os retângulos de detecção
- `public/`: Arquivos públicos e HTML base

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias.

## Licença

Este projeto está licenciado sob a MIT License.

## Contato

Se você tiver alguma dúvida ou sugestão, por favor, abra uma issue neste repositório ou entre em contato através do meu perfil do GitHub.
