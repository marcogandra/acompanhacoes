
# acompanhacoes

O objetivo do pacote `acompanhacoes` é possibilitar a portabilidade do dashboard desenvolvido para o acompanhamento de ativos de diferentes naturezas.

Este dashboard é uma POC ([proof of concept](https://en.wikipedia.org/wiki/Proof_of_concept)) para o desenvolvimento de um dispositivo que possibilite a automação do acompanhamento de ativos de renda variaável. O app shiny foi desenvolvido utilizando o framework [`golem`](https://thinkr-open.github.io/golem/index.html) que trás uma série de configurações que facilitam na hora de implementar o app em desenvolvimento. O app possui um script [Dockerfile](https://github.com/gomesfellipe/acompanhacoes/blob/master/Dockerfile) que é gerado automaticamente utilizando a função `golem::add_dockerfile()`.

Sinta-se a vontade para utilizar, reproduzir e modificar o código. O dashboard esta em desenvolvimento e qualquer ajuda será bem vinda!

## Instalação

Para instalar a versão de desenvolvimento do aplicativo execute os comandos:

``` r
devtools::install_github("gomesfellipe/acompanhacoes")
```

## Uso

Após instalar o pacote, execute os comandos para executar o dashboard no R:

``` r
library(acompanhacoes)
run_app()
```

Veja como é a tela do dashboard:

![](inst/app/www/dashboard.png)
