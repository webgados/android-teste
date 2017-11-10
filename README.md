# Teste para candidatos à vaga de desenvolvedor Android

[![WebGados](https://webgados.com.br/v2_assets/img/logo-webgados-cel.png)](https://webgados.com.br)

Esse teste é público. Candidatos para o teste devem implementar a aplicação solicitada e criar uma issue com um link para um repositório com a solução do mesmo.

### Objetivo do teste
Implementar um aplicativo nativo para Android, de preferência utilizando a linguagem Kotlin, que consulte uma API e mostre uma lista de anúncios (com foto).

### Requisitos
  - Seguir as diretrizes do Android Material Design Guidelines
  - Fazer cache das imagens
  - Se não houver internet, continuar exibindo os anúncios já baixados e mostrar uma label indicando falta de conexao
  - Tela responsiva - Touch feedback (ao clicar em um anúncio abrir uma nova tela contedo uma label com o "_id" do anúncio selecionado)

### Ganha + pontos se tiver
  - Testes unitários. Ex: Mockito
  - Teste funcionáis. Ex: Expresso
  - Utilizar a linguagem Kotlin
  - Armazenar os dados utilizando Room Persistence Library
  - Construir o código utilizando a arquitetura AAC (Android Architecture Components)
  - Documetação do código

### Tela (Lista de Anúncios)

Deve ser feita uma lista, em que cada elemento tenha a imagem, o titulo, idade, peso, preço e informações do vendedor conforme abaixo:

![Lista de Anuncios](https://i.imgur.com/bXF4PhR.png)

### API:
Endpoint para pegar anúncios

> Link: https://webgados.com.br/anuncios-example

### Propriedades do anúncio na API:

- Titulo to anúncio -> "title"
- Idade: "years" e "months"
- Peso: "average_weight"
- Tipo de peso: "weight_type"
- Valor: "unit_value" (o valor contem um inteiro já com centavos, dividindo por 100 você obtem o valor real, exemplo: 120000 = R$ 1.200,00
- Avatar do vendedor: "seller_avatar" (Se não tiver mostre qualquer imagem padrao)
- Nome do vendedor: "seller_name"
- Tipo do vendedor: Deixa sempre "corretor" (sem chave definida na api)
- Avaliação do vendedor: "seller_rating"
- Nome da cidade: "farm.city"
- Sigla da estado: "farm.state"
- Distância: Deixa sempre "30km"  (sem chave definida na api)


### Critérios de avaliação:
- Organização do código: desacoplamento e legibilidade contam;
- Flexibilidade do sistema para adição/remoção de funcionalidades;

### Como vamos avaliar:
O código do aplicativo será clonado de algum repositório público e será executado através do Android Studio sobre diferentes dispositivos emulados;
Vamos ler o código;

### Assets
Os assets necessários estão neste repositório na pasta "assets".

### Dúvidas?
Envie um e-mail para: gabriel.stein@webgados.com.br
