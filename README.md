<!-- Título -->
# Atribuindo e Declarando Variáveis em C

***Conteúdo da Aula:***

Como verificamos, a declaração de variáveis no **C** pode ser feita em qualquer lugar em nosso código-fonte:

* Basta você definir o tipo da variável e depois o seu nome.
* Opcionalmente, você também pode definir um valor inicial para ela.

Veja o exemplo abaixo;

```c
// <tipo da variável> <nome da variável> [ = <valor inicial>]
int a;
int b = 0;
```

Nada nos impede de inclusive **“duplicar”** o valor das variáveis, fazendo a atribuição de valor entre elas:

```c
int a = 0; // a vale "0"
int b = a; // b agora também vale "0"
```

Não se esqueça:

* Uma variável só é **“enxergada”** e pode ser utilizada do ponto em que foi declarada em diante;
* Você só conseguirá utilizar uma variável da linha em que ela foi declarada em diante.

Veja o exemplo abaixo:

```c
int main() {
    a = 3; // Não irá funcionar: a variável "a" ainda não foi declarada
    int a = 0;
    a = 2; // Essa linha irá funcionar: a variável "a" foi declarada na linha anterior!
}
```

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-atr-dec-var-c-var-tip-dad-c-log-par-pro-com-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-atr-dec-var-c-var-tip-dad-c-log-par-pro-com-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-atr-dec-var-c-var-tip-dad-c-log-par-pro-com-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-atr-dec-var-c-var-tip-dad-c-log-par-pro-com-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-atr-dec-var-c-var-tip-dad-c-log-par-pro-com-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-atr-dec-var-c-var-tip-dad-c-log-par-pro-com-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
