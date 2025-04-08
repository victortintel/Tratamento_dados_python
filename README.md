Preparação de Dados para Modelo Preditivo - Machine Learning<br><br>
📌 Visão Geral<br><br>
Este projeto tem como objetivo preparar um conjunto de dados para um modelo preditivo de Machine Learning, aplicando técnicas de limpeza, transformação e engenharia de features. O dataset utilizado contém informações sobre veículos, incluindo preços, modelos, anos e outras características relevantes.

🔍 Objetivos<br>
✔️ Realizar uma análise exploratória (EDA) para entender os dados.<br>
✔️ Tratar valores ausentes, outliers e inconsistências.<br>
✔️ Aplicar técnicas de pré-processamento (normalização, codificação, etc.).<br>
✔️ Engenharia de features para melhorar o desempenho do modelo.<br>
✔️ Documentar o processo para reprodutibilidade.<br><br>

🔍 Por Que é Importante?<br>
✔️Dados brutos costumam ser incompletos, inconsistentes ou não padronizados.<br>
✔️Modelos preditivos exigem dados numéricos, estruturados e limpos para funcionar corretamente.<br>
✔️Uma preparação adequada pode melhorar a acurácia do modelo em mais de 50%.<br><br>

📊 Principais Etapas<br>
1. Coleta e Entendimento dos Dados<br>
✔️Identificar as fontes de dados (CSV, APIs, bancos de dados).<br>
✔️Definir o objetivo do modelo (ex.: prever preços de veículos, classificar modelos).<br><br>

2. Limpeza de Dados (Data Cleaning)<br>
✔️Tratar valores ausentes:<br>
✔️Excluir linhas com NaN ou preencher com média/mediana.<br>
✔️Remover outliers: Usar IQR ou Z-Score para detectar valores extremos.<br><br>

3. Transformação de Dados<br>
✔️Codificação de variáveis categóricas:<br>
✔️Converter texto em números (ex.: "SUV" → 1, "Sedan" → 2).<br><br>

🛠️ Técnicas Aplicadas<br><br>
1️⃣ Limpeza de Dados<br>
✔️Tratamento de valores ausentes (NaN).<br>
✔️Detecção e remoção de outliers (IQR, Z-Score).<br>
✔️Padronização de unidades e formatos (ex.: datas, texto).<br><br>

2️⃣ Transformação de Dados<br>
✔️Codificação de variáveis categóricas:<br>
✔️One-Hot Encoding (para categorias sem ordem).<br>
✔️Label Encoding (para categorias ordinais).<br>
✔️Normalização/Padronização (MinMaxScaler, StandardScaler).<br><br>

3️⃣ Engenharia de Features<br>
✔️Criação de novas variáveis (ex.: "idade_veiculo" = ano_atual - ano_fabricacao).<br>
✔️Seleção de features (correlação, importância).<br><br>

4️⃣ Visualização<br>
✔️Gráficos para análise exploratória:<br>
✔️Histogramas, boxplots, heatmaps (correlação).<br>
✔️Scatter plots para relações entre variáveis.<br><br>

🚀 Como Executar
Pré-requisitos
Python 3.x

Jupyter Notebook

Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn<br><br>

📞 Contato<br>
Feito por Victor Tintel.<br>

LinkedIn: https://www.linkedin.com/in/victor-tintel<br>

GitHub: https://github.com/victortintel<br>
