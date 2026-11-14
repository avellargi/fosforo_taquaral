<img src= "images/imagem (1).png"/>

<h1 align="center">Modelo para o controle da taxa de crescimento da concentração
de fósforo na Lagoa do Taquaral</h1>

<p align="center">
  <img src="images/header (3).png" />
</p>

Este repositório contém o código-fonte desenvolvido para a Entrega Final da disciplina "Equações Diferenciais" do segundo semestre do Bacharelado em Ciência e Tecnologia da Ilum. O objetivo do trabalho é investigar 

se é possível identificar o grupo taxonômico de um organismo a partir do seu viés de uso de códons, isto é, da frequência com que cada um dos 64 códons aparece em seu genoma [1]. Para isso, foram comparados cinco algoritmos de aprendizado de máquina (regressão logística, k-vizinhos mais próximos, árvore de decisão, floresta aleatória e gradient boosting) e um modelo baseline, utilizando o conjunto de dados "Codon Usage", disponível no UCI Machine Learning Repository [2]. Os hiperparâmetros de cada algoritmo foram otimizados com a biblioteca Optuna, e o desempenho dos modelos foi avaliado por validação cruzada e, ao final, em um conjunto de teste separado.

## Tecnologias Utilizadas
- Python (3.13.7): linguagem utilizada para o desenvolvimento do projeto;

- pandas (2.3.3): utilizada para leitura, organização e manipulação de dados;

- NumPy (2.2.6): foi empregada para manipulação de arrays e operações matemáticas;

- Matplotlib (3.10.6): utilizada para a construção de gráficos e visualização dos resultados;


## Acesso ao código
As informações detalhadas do projeto, incluindo a fundamentação teórica, a formulação matemática e a resolução tanto analítica quanto numérica estão disponíveis no repositório em: [código](https://github.com/avellargi/ml_codon_usage/tree/main/code)

## Autoria
| <img src="https://github.com/avellargi.png" width=115><br><sub>[Giovanna Avellar Machado](https://github.com/avellargi)</sub> |
| :--: |
Giovanna Avellar Machado - Aluna do Segundo Semestre do Bacharelado em Ciência, Tecnologia e Inovação da Ilum - Escola de Ciência 

## Professor Orientador
| <img src="https://github.com/user-attachments/assets/17dfa7bf-5ca9-42df-b63e-917827fc6308" width=115><br><sub>[Prof. Dr. Daniel Roberto Cassar](http://lattes.cnpq.br/1717397276752482)</sub> |
| :--: |
Daniel Roberto Cassar - Docente Pesquisador da Ilum – Escola de Ciência. Doutorado em Ciência e Engenharia de Materiais (UFSCar) e Pós-Doutorado pela UFSCar. Atua na área de Informática de Materiais.

## Referências Bibliográficas
[1] PARVATHY, Sujatha Thankeswaran; UDAYASURIYAN, Varatharajalu; BHADANA, Vijaipal. Codon usage bias. Molecular Biology Reports, v. 49, n. 1, p. 539-565, 2022. DOI: 10.1007/s11033-021-06749-4. Disponível em: https://pmc.ncbi.nlm.nih.gov/articles/PMC8613526/. Acesso em: 21 set. 2026. <br>
[2] HALLEE, L.; KHOMTCHOUK, B. B. Codon usage [Dataset]. UCI Machine Learning Repository, 2020. Disponível em: https://doi.org/10.24432/C5KP6B. Acesso em: 21 set. 2026. <br>

P.S. As referências estão ordenadas em ordem de aparição no documento.

<img src= "images/imagem (2).png"/>
