<img src="images/imagem (1).png"/>

<h1 align="center">Modelagem da dinâmica do fósforo total na Lagoa do Taquaral por equações diferenciais</h1>

<p align="center">
  <img src="images/header (3).png" />
</p>

Este repositório contém o código-fonte desenvolvido para a Entrega Final da disciplina "Equações Diferenciais" do segundo semestre do Bacharelado em Ciência e Tecnologia da Ilum. O objetivo do trabalho é modelar a concentração de fósforo total na Lagoa do Taquaral, em Campinas (SP), um corpo d'água urbano eutrofizado, e estimar o tempo necessário para que ela atinja o limite da Resolução CONAMA 357/2005 após a interrupção do lançamento de esgoto. Para isso, utiliza-se o modelo de balanço de massa de Vollenweider [1], na forma apresentada por Toné e Lima Neto [2], adaptado para incluir a liberação de fósforo pelo sedimento medida na lagoa [3]. A equação diferencial resultante é resolvida analiticamente, pela soma das soluções homogênea e particular, e numericamente, pelo método de Runge-Kutta de quarta ordem, e as duas soluções são comparadas. Por fim, simulam-se dois cenários de recuperação (interrupção do esgoto com e sem tratamento do sedimento).

## Modelo
O modelo é uma equação diferencial ordinária linear de primeira ordem:

```math
\frac{dP}{dt} = \frac{W_{ext}}{V} + \frac{r}{\bar z} - \left(\frac{1}{\tau} + k\right)P,
\qquad P(0)=P_0
```

em que $P(t)$ é a concentração de fósforo total (µg/L), $W_{ext}$ é a carga externa, $V$ o volume, $r$ a taxa de liberação de fósforo pelo sedimento, $\bar z$ a profundidade média, $\tau = V/Q$ o tempo de residência e $k$ o coeficiente de decaimento.

## Dados
- Morfometria, fósforo total, temperatura e liberação de fósforo pelo sedimento da Lagoa do Taquaral: tese de Hernández Piedrahíta (2002) [3].
- Tempo de residência (usado para estimar a vazão): Lago das Garças, São Paulo, Henry et al. (2004) [4].
- Coeficiente de decaimento: equação de Toné e Lima Neto (2020) [2].

## Tecnologias Utilizadas
- Python (3.13.7): linguagem utilizada para o desenvolvimento do projeto;
- NumPy (2.2.6): manipulação de arrays e operações matemáticas;
- pandas (2.3.3): organização dos parâmetros e dos resultados em tabelas;
- Matplotlib (3.10.6): construção dos gráficos.

## Acesso ao trabalho
O relatório completo do projeto, contendo a modelagem matemática, a dedução analítica da solução da equação diferencial e a análise dos resultados obtidos pelo método numérico, bem como todos os arquivos referentes ao Overleaf estão disponíveis em formato PDF em: [paper](https://github.com/avellargi/fosforo_taquaral/tree/main/paper)

## Acesso ao código
O notebook com a implementação do método de Runge-Kutta, a comparação com a solução analítica e os cenários de recuperação está disponível em: [code](https://github.com/avellargi/fosforo_taquaral/tree/main/code)

## Autoria
<div align="center">
<table>
  <tr>
    <td align="center"><img src="https://github.com/avellargi.png" width="115"><br><sub><a href="https://github.com/avellargi">Giovanna Avellar Machado</a></sub></td>
    <td align="center"><img src="https://github.com/buruna087.png" width="115"><br><sub><a href="https://github.com/buruna087">Bruna Henrique Fujihashi</a></sub></td>
    <td align="center"><img src="https://github.com/constantinovmurillo-boop.png" width="115"><br><sub><a href="https://github.com/constantinovmurillo-boop">Murillo Constantinov</a></sub></td>
  </tr>
</table>

Alunos do Segundo Semestre do Bacharelado em Ciência, Tecnologia e Inovação da Ilum – Escola de Ciência.
</div>

## Professor Orientador
<div align="center">
<table>
  <tr>
    <td align="center"><img src="https://github.com/viniciuswasques.png" width="115"><br><sub><a href="http://lattes.cnpq.br/1558070758473264">Prof. Dr. Vinícius Francisco Wasques</a></sub></td>
  </tr>
</table>

Prof. Dr. Vinícius Francisco Wasques - Docente Pesquisador da Ilum – Escola de Ciência (CNPEM). Doutorado em Matemática Aplicada.
</div>

## Referências Bibliográficas
[1] VOLLENWEIDER, R. A. Scientific fundamentals of the eutrophication of lakes and flowing waters, with particular reference to nitrogen and phosphorus as factors in eutrophication. Paris: OECD, 1968. (Relatório DAS/CSI/68.27). <br>
[2] TONÉ, A. J. A.; LIMA NETO, I. E. Modelagem simplificada do fósforo total em lagos e reservatórios brasileiros. Revista DAE, v. 68, n. 221, p. 142-156, 2020. DOI: 10.36659/dae.2020.012. <br>
[3] HERNÁNDEZ PIEDRAHÍTA, E. Caracterização limnológica e estudo do processo de sedimentação e liberação de fósforo da Lagoa do Taquaral – Campinas (SP). 2002. Tese (Doutorado) – Escola de Engenharia de São Carlos, Universidade de São Paulo, São Carlos, 2002. <br>
[4] HENRY, R.; CARMO, C. F.; BICUDO, D. C. Trophic status of a Brazilian urban reservoir and prognosis about the recovery of water quality. Acta Limnologica Brasiliensia, v. 16, n. 3, p. 251-262, 2004. <br>
[5] BRASIL. Conselho Nacional do Meio Ambiente. Resolução CONAMA nº 357, de 17 de março de 2005. Diário Oficial da União, Brasília, 18 mar. 2005. <br>

<img src="images/imagem (2).png"/>
