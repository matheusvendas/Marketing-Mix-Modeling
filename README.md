# Marketing-Mix-Modeling


## Marketing Mix Modeling (MMM): OLS vs. Bayesian (PyMC)

Este repositório documenta a construção e evolução de um modelo de Marketing Mix Modeling (MMM), contrastando a abordagem frequentista tradicional com a modelagem Bayesiana moderna. 

O foco prático é demonstrar como o **Viés de Seleção (Selection Bias)** e a **Multicolinearidade** nos canais digitais quebram as premissas da regressão linear, e como a modelagem Bayesiana resolve esses problemas matemáticos utilizando *Priors* informativas ancoradas em experimentos causais (Geo-Lift / Audience Splits).

### 🛠️ Tecnologias e Dependências

O projeto foi construído em Python. As principais bibliotecas utilizadas são:

- `numpy` e `pandas` (Manipulação e geração de dados sintéticos)
- `statsmodels` (Regressão Linear Múltipla / OLS)
- `pymc` (Motor de Inferência Bayesiana / MCMC)
- `arviz` (Diagnóstico e visualização das distribuições a posteriori)

Para instalar as dependências:
```bash
pip install pandas numpy statsmodels pymc arviz

