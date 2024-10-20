
# Save Water AI
## Projeto Final da Disciplina de Aprendizagem de Máquina

Dada a importância da água para a vida humana, este estudo foi desenvolvido com base em dados disponibilizados por órgãos governamentais e fontes como o IBGE, a ANA (Agência Nacional de Águas e Saneamento Básico) e o World Bank Group. Utilizando técnicas de Inteligência Artificial, o projeto visa prever o consumo de água no Brasil e no mundo nos próximos anos, levando em consideração ações humanas, condições ambientais, crescimento industrial, entre outros fatores. O objetivo principal é entender como determinados processos afetam o consumo de água e, a partir disso, propor medidas para minimizar o uso desse recurso finito, a água potável.

## Engenharia de Dados - Coleta, Descrição e Tratamento
### Fontes dos Dados:
World Bank Group: [Link](https://data.worldbank.org)

Após a análise de diversas fontes governamentais e internacionais, foi constatado que a API do World Bank Group oferece dados bem estruturados e confiáveis, com poucos "furos". Por isso, decidimos utilizá-la como base de dados para este projeto. Algumas adaptações foram feitas para tentar organizar os dados e torna-los melhores para utilização. Esses processos estão descritos no primeiro tópico do arquivo **codes.ipynb**.

### Crescimento Populacional
Os dados sobre o crescimento populacional são essenciais para compreender a relação entre o aumento da população e o consumo de água ao longo dos anos.

### Crescimento Industrial
Analisar o crescimento industrial é crucial, pois o desenvolvimento econômico costuma aumentar o consumo de água, especialmente em setores como agricultura, manufatura e energia.

### Área Florestal
Os dados sobre a preservação de florestas e áreas verdes são importantes para entender o quanto os países estão preocupados com a conservação de seus recursos naturais e como isso impacta o consumo de água.

### Consumo de Água - Target
O consumo de água se refere à quantidade retirada das reservas naturais. A água potável é um recurso limitado, e entender como seu uso evoluiu ao longo dos anos nos ajuda a planejar ações para enfrentar um futuro de potencial escassez.

