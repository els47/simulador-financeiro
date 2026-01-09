# 📊 Simulador Financeiro em Excel – DIO Invest

Este repositório contém um **simulador financeiro desenvolvido em Excel** como parte do desafio do bootcamp **Santander - Excel com Inteligência Artificial**, na plataforma da **DIO**. O objetivo do projeto é aplicar conceitos fundamentais de Excel na construção de uma ferramenta prática de **simulação de investimentos em Fundos Imobiliários (FIIs)**, auxiliando o usuário na tomada de decisões financeiras de forma simples e visual.

---

## 🎯 Objetivo do Projeto

Criar uma planilha automatizada capaz de:

* Simular investimentos mensais ao longo do tempo;
* Projetar patrimônio acumulado em diferentes horizontes (2, 5, 10, 20 e 30 anos);
* Estimar dividendos mensais;
* Sugerir alocação de investimentos em FIIs de acordo com o **perfil do investidor**;
* Utilizar recursos nativos do Excel para cálculos financeiros, organização de dados e visualização.

---

## 🧠 Conceitos e Funcionalidades Utilizadas

O simulador foi construído utilizando **recursos essenciais do Excel**, com foco em clareza, organização e reutilização de fórmulas:

### 🔢 Cálculos Financeiros

* **VF (Valor Futuro)** para projeção do patrimônio ao longo do tempo;
* Cálculo de **investimento mensal**, patrimônio acumulado e dividendos;
* Simulações considerando taxa de rendimento mensal e período de investimento.

### 🏷️ Intervalos Nomeados

* Uso de intervalos nomeados para facilitar a leitura das fórmulas;
* Maior organização e manutenção da planilha;
* Redução de erros em referências diretas de células.

### 🔗 Chaves Compostas

* Criação de chaves combinando **Perfil do Investidor + Tipo de FII**;
* Estrutura que permite buscas mais flexíveis e organizadas.

### 🔍 PROCV

* Utilizado para buscar percentuais de alocação de acordo com o perfil escolhido;
* Integração entre tabelas de apoio e a área principal do simulador.

### 🎨 Estilização no Excel

* Padronização visual com cores, títulos e seções bem definidas;
* Destaque para valores importantes (patrimônio, dividendos, totais);
* Gráfico de alocação para melhor visualização da distribuição dos investimentos.

---

## 🧩 Estrutura do Simulador

O arquivo está organizado em seções lógicas:

* **Configurações**: salário, rendimento da carteira e sugestão de investimento;
* **Investimento Mensal**: valor investido, período e taxa de rendimento;
* **Projeção de Cenários**: patrimônio e dividendos ao longo do tempo;
* **Perfil do Investidor**: conservador, moderado ou agressivo;
* **Distribuição por Tipo de FII**:

  * Papel
  * Tijolo
  * Híbridos
  * FOFs
  * Desenvolvimento
  * Hotelarias

Cada perfil possui percentuais distintos de alocação, definidos em tabelas auxiliares.

---

## 🛠️ Tecnologias e Ferramentas

* **Microsoft Excel**
* Fórmulas financeiras nativas
* PROCV
* Intervalos nomeados
* Gráficos do Excel

---

## 🚀 Como Utilizar

1. Abra o arquivo no Excel;
2. Informe os dados na seção de configurações;
3. Escolha o perfil do investidor;
4. Analise as projeções de patrimônio e dividendos;
5. Visualize a distribuição sugerida dos investimentos.

⚠️ Observação: este projeto tem **finalidade educacional** e não constitui recomendação de investimento.

---

## 📌 Aprendizados

Com este projeto foi possível:

* Consolidar conceitos de Excel aplicados a finanças;
* Criar uma solução prática e reutilizável;
* Organizar dados de forma estruturada;

Se você tiver sugestões ou melhorias, fique à vontade para contribuir! 😊

