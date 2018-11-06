Desafio android
====

## Requisitos

- Kotlin
- ConstraintLayout
- Android 5+
- Faça um readme informando particularidades e justificativas para determinadas escolhas
- Fonte: OpenSans-Regular.ttf

## Sugestões

- Aplicar alguma arquitetura - MVVM, MVP, VIP, VIPER
- Framework para consumir os dados da API
- Procure enviar o relatório de cobertura de testes
- Feedback para o usuário e fluidez na navegação ganham pontos
- Teste instrumentado -> Espresso
- Teste unitário -> Qualquer framework, mas explique no readme as vantagens.

## Mockup

### Inicial

![](https://raw.githubusercontent.com/grupofleury/android-desafio/master/heroscreen.png)

### Detalhes

![](https://raw.githubusercontent.com/grupofleury/android-desafio/master/details.png)

## API

- As datas estão em milisegundos(UTC), devem ser formatadas para o TimeZone do local do celular e exibidas conforme o mockup
- O atributo "healthy" determina se é positiva ou negativa a situação, está no formato Boolean

      GET - http://5be19df804cb600013a61f1a.mockapi.io/api/v1/results
      GET - http://5be19df804cb600013a61f1a.mockapi.io/api/v1/results/{id}

## Como submeter?

Deverá ser enviado um PULL REQUEST com o seu teste.

### Como funciona?

- Fork deste repositório
- Clonar a partir do repositório que foi criada na sua conta
- Procure fazer o máximo de commits com todas as suas decisões
- Abra um Pull Request para este repositório

## Dúvidas

Consulte as issues para ver se outro DEV já não a fez e caso você não ache sua resposta, abra você mesmo uma nova issue.
