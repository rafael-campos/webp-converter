# Conversor de Imagens para WebP

Este é um simples conversor de imagens para o formato WebP, desenvolvido para facilitar a conversão de imagens em lotes para o formato WebP, que oferece alta qualidade com tamanhos de arquivo menores em comparação com outros formatos de imagem.

## Requisitos

Certifique-se de ter o Node.js instalado em seu sistema antes de prosseguir. Você pode baixá-lo e instalá-lo em [nodejs.org](https://nodejs.org/).

## Instalação

Para começar, basta clonar este repositório e instalar as dependências:

```bash
git clone https://github.com/CarlosAndre147/webp-converter
cd conversor-de-imagens
npm install
```

## Uso

1. Coloque as imagens que deseja converter na pasta `src/imagens`.
2. Execute o seguinte comando para iniciar a conversão:

```bash
npm run webp
```

3. Aguarde até que todas as imagens sejam convertidas para o formato WebP na pasta `src/imagens/webp`.

## Biblioteca usada:

https://github.com/vkiss/simple-webp-converter
