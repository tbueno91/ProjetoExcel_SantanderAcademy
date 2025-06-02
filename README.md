# ProjetoExcel_SantanderAcademy

Este repositório contém um projeto em Microsoft Excel desenvolvido para auxiliar na **simulação de investimentos** pessoais, utilizando fórmulas financeiras, formatações inteligentes e estruturação modular de dados. O projeto foi criado como parte da formação na **Santander Academy**.

---

## 📌 Objetivo

A planilha permite ao usuário simular o crescimento do patrimônio com base em três parâmetros principais:

- Aporte mensal
- Rendimento estimado da carteira
- Tempo de investimento (em anos)

Com isso, é possível projetar o valor futuro do patrimônio, calcular rendimentos estimados e planejar metas financeiras de maneira prática e acessível.

---

## 📂 Estrutura do Projeto

O arquivo `.xlsx` possui duas planilhas principais:

### 🧾 Planilha1 – Simulação de Investimentos

- Projeção de patrimônio com base em valores de entrada
- Cálculo de rendimento com base em percentuais mensais e anuais
- Uso de fórmulas financeiras como `FV()` para simulação de valor futuro
- Estrutura replicável para diferentes períodos e aportes

### 🗃️ Planilha2 – Dados Auxiliares

- Geração de identificadores únicos por concatenação de células
- Base auxiliar para alimentar estruturas e automatizar controles

---

## 🧮 Principais Fórmulas

### `=FV(taxa_mensal, qtd_anos * 12, aporte * -1)`
> Calcula o valor futuro de um investimento com aportes mensais constantes

### `=patrimonio * rendimento_carteira`
> Apura o rendimento anual estimado com base no patrimônio acumulado

### `=D16 * 30%`
> Cálculo de taxa adicional sobre um valor de entrada (ex: imposto, corretagem)

### `=$B$3 & "-" & C3`
> Concatenação de identificadores únicos na Planilha2

---

## ✅ Boas Práticas Utilizadas

- Estrutura modular e separação entre cálculo e dados
- Fórmulas com referências absolutas para fácil replicação (`$D$23`, `$A28`, etc.)
- Organização por seções lógicas (entradas, projeções, resultados)
- Uso adequado da função `FV()` com todos os argumentos financeiros esperados

---

## 📎 Requisitos

- Microsoft Excel (recomendado Excel 2016 ou superior)
- Ou software compatível com fórmulas e formatação avançada (.xlsx)

---

## ✍️ Autor

**Thomas Bueno Vaneli do Carmo**  
Projeto desenvolvido durante formação pela **Santander Academy**.  
