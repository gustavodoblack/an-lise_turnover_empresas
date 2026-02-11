📊 Análise de Turnover de Funcionários
📌 Sobre o Projeto

Este projeto tem como objetivo realizar uma Análise Exploratória de Dados (EDA) para investigar possíveis fatores associados ao turnover (evasão de funcionários).

A análise foi conduzida utilizando Python, com foco em:

Manipulação e tratamento de dados (Pandas)

Análise exploratória

Estatística descritiva

Visualizações com Matplotlib e Seaborn

Interpretação técnica dos resultados

O projeto simula um cenário real de People Analytics, no qual uma empresa deseja entender o que pode estar influenciando a saída de colaboradores.

🎯 Problema de Negócio

O turnover é um dos principais desafios estratégicos das empresas, podendo gerar:

Aumento de custos com recrutamento

Perda de conhecimento organizacional

Queda de produtividade

Impacto na cultura e no clima organizacional

O objetivo da análise foi responder à seguinte pergunta:

Os dados disponíveis conseguem explicar ou indicar fatores associados à saída de funcionários?

📂 Descrição do Dataset

O dataset contém informações de 1.000 funcionários e inclui as seguintes variáveis:

Age – Idade

Gender – Gênero

Department – Departamento

Job_Title – Cargo

Years_at_Company – Tempo de empresa

Satisfaction_Level – Nível de satisfação (0 a 1)

Average_Monthly_Hours – Média de horas trabalhadas por mês

Promotion_Last_5Years – Promoção nos últimos 5 anos (0 ou 1)

Salary – Salário anual

Attrition – Indicador de saída (0 = permaneceu, 1 = saiu)

🛠 Tecnologias Utilizadas

Python

Pandas

Matplotlib

Seaborn

Jupyter Notebook

🔎 Etapas da Análise
1️⃣ Importação e Estruturação dos Dados

Leitura do dataset

Definição da coluna Employee_ID como índice

Verificação de tipos de dados

2️⃣ Validação da Qualidade dos Dados

Verificação de valores nulos

Verificação de registros duplicados

Análise estrutural do dataset

Resultado:
✔ Dataset limpo
✔ Sem valores nulos
✔ Sem duplicidades

3️⃣ Análise Descritiva

Foram analisadas médias e distribuições das variáveis numéricas, incluindo:

Idade média

Tempo médio de empresa

Salário médio

Nível médio de satisfação

Observação importante:
A variável Attrition está praticamente balanceada (≈50% saída e 50% permanência).

4️⃣ Comparações por Turnover

Foram realizadas análises comparativas entre funcionários que saíram e os que permaneceram, avaliando:

Idade

Tempo de empresa

Nível de satisfação

Horas trabalhadas

Promoções

Salário

Resultado:
As médias apresentaram diferenças mínimas entre os grupos.

5️⃣ Análises Visuais

Foram utilizados:

Boxplots

Scatterplots

Tabelas cruzadas

Análise de correlação

As visualizações não indicaram padrões claros que expliquem o turnover.

6️⃣ Correlação

A correlação entre Attrition e as variáveis numéricas apresentou valores próximos de zero.

Isso indica ausência de relação linear significativa entre as variáveis analisadas e o turnover.

📊 Principais Conclusões

Após a análise exploratória completa:

Nenhuma variável apresentou impacto significativo no turnover.

As diferenças entre os grupos são estatisticamente pequenas.

A correlação entre as variáveis e a evasão é praticamente inexistente.

O dataset aparenta ser artificial ou balanceado intencionalmente.

Conclusão técnica:

Os dados disponíveis não apresentam evidências estatísticas suficientes para explicar a evasão de funcionários.

🧠 Aprendizados Demonstrados

Este projeto demonstra:

Estruturação lógica de análise

Validação de qualidade dos dados

Aplicação de estatística descritiva

Uso adequado de visualizações

Interpretação baseada em evidências

Maturidade analítica ao não forçar conclusões

🚀 Próximos Passos

Possíveis evoluções do projeto:

Aplicação de modelo de Regressão Logística

Testes estatísticos (t-test, qui-quadrado)

Análise de importância de variáveis

Construção de modelo preditivo

Criação de dashboard interativo

👨‍💻 Autor

Gustavo de Andrade
Analista de Dados | Python | Análise Exploratória
Focado em raciocínio analítico estruturado e tomada de decisão orientada por dados.
