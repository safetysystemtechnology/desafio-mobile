# Desafio de programação mobile IOS

A idéia deste desafio é nos permitir avaliar melhor as habilidades de candidatos à vagas de programador, de vários níveis.

Este desafio deve ser feito por você em sua casa. Gaste o tempo que você quiser, porém normalmente você não deve precisar de mais do que algumas horas.

## Instruções de entrega do desafio

1. Envie um e-mail com seu cv para `selecao@safetysystemtechnology.com.br`
1. Faça um clone deste repositório.
1. Em seguida, implemente o projeto tal qual descrito abaixo, em seu clone local.
1. Por fim, envie um pull request com seu email na descriçao.

## Descrição do projeto

Você deve criar um aplicativo que irá listar os repositórios públicos mais populares relacionados à Java no GitHub, usando a [API do GitHub](https://developer.github.com/v3/) para buscar os dados necessários.

O aplicativo deve exibir inicialmente uma lista paginada dos repositórios, ordenados por popularidade decrescente (exemplo de chamada da API: `https://api.github.com/search/repositories?q=language:Java&sort=stars&page=1`).

Cada repositório deve exibir Nome do repositório, Descrição do Repositório, Nome / Foto do autor, Número de Stars, Número de Forks.

Ao tocar em um item, deve levar a lista de Pull Requests do repositório. Cada item da lista deve exibir Nome / Foto do autor do PR, Título do PR, Data do PR e Body do PR.

Ao tocar em um item, deve abrir no browser a página do Pull Request em questão.

Você pode se basear neste mockup para criar as telas:

![mockup](https://raw.githubusercontent.com/myfreecomm/desafio-mobile-android/master/mockup-android.png)

Sua aplicação deve:

- fazer mapeamento json -> Objeto . Ex: GSON / Jackson / Moshi / etc
- usar um arquivo .gitignore no seu repositório
- possuir boa cobertura de testes unitários no projeto.

Você ganha mais pontos se:

- usar padrões de projeto
- persistir os dados localmente
- criar testes funcionais
- fazer cache de imagens

Será um grande diferencial:

- contribuir em projetos open source
- conhecimento nos princípios SOLID
- conceitos de arquitetura como (DDD, clean architecture)
- ter conhecimento em desenvolvimento web

## Avaliação

Seu projeto será avaliado de acordo com os seguintes critérios.

1. Sua aplicação preenche os requerimentos básicos?
1. Você documentou a maneira de configurar o ambiente e rodar sua aplicação?
1. Você seguiu as instruções de envio do desafio?

## Referência

Este desafio foi baseado neste outro desafio: https://bitbucket.org/suporte_concrete/desafio-android
