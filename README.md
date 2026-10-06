# Gerador de QR Code

Um projeto simples para transformar um texto ou endereço de site em um QR Code. A página foi feita com HTML, CSS e JavaScript e se adapta a telas menores.

## Como usar

1. Abra o arquivo `index.html` em um navegador.
2. Digite um texto ou uma URL no campo.
3. Clique em **Gerar QR Code**.
4. O QR Code aparecerá no card.

É necessário estar conectado à internet para gerar a imagem, pois o projeto usa a API externa [QRServer](https://api.qrserver.com/).

> **Privacidade:** o texto ou a URL digitados são enviados à API QRServer para gerar o QR Code. Evite inserir informações pessoais ou confidenciais.

## Tecnologias

- **HTML** - estrutura da página.
- **CSS** - aparência, centralização, responsividade e animação do campo vazio.
- **JavaScript** - lê o texto informado e atualiza a imagem do QR Code.
- **QRServer API** - serviço externo que cria a imagem do código.

## Arquivos

```text
projeto01-qrcode/
├── index.html   # Página e lógica de geração
├── style.css    # Estilos da interface
└── README.md    # Informações sobre o projeto
```

## Como funciona

Ao clicar no botão, o JavaScript verifica se o campo contém algum texto. Se estiver preenchido, o conteúdo é usado como dado para solicitar uma imagem à API QRServer. Se estiver vazio, o campo recebe uma animação para chamar a atenção.

---

<p align="center">
  Desenvolvido por <a href="https://github.com/LucMNS"><b>LucMNS</b></a>
</p>