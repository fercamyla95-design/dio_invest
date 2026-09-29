# 🧮  DIO - Santander - Excel com IA e Claude

### 1- Projeto **Invest Agro**: uma planilha de simulação de investimentos feita no Excel durante o bootcamp **DIO + Santander**, com o **Claude** como apoio na construção das fórmulas e na organização das tabelas.

🔗 **[Acesse a planilha no OneDrive](https://1drv.ms/x/c/aa302b7b523f2ab6/IQDbD1rrzbUfTJJqdPNKhh6dAawQ61It3qodvUoXfXI_fkg?e=G6J1hI)**

![Invest Agro](img/capa.jpeg)

---

## 🎯 Objetivo
Simular quanto um investimento mensal pode render ao longo do tempo com juros compostos, mostrando o patrimônio acumulado e a renda mensal (dividendos) em diferentes prazos.

## 🧮 Como a planilha funciona

### 1. Investimento mensal (entradas)
| Campo | Exemplo |
|---|---|
| Quanto investir por mês? | R$ 500,00 |
| Por quantos anos? | 5 |
| Taxa de rendimento mensal | 1,08% |
| **Patrimônio acumulado** | calculado com `VF` |
| **Dividendos mensais** | patrimônio × taxa |

### 2. Cenários
Compara o mesmo aporte mensal em cinco prazos:

| Prazo | Patrimônio acumulado | Dividendo mensal |
|---|---|---|
| 2 anos | R$ 13.615,43 | R$ 136,15 |
| 5 anos | R$ 41.902,01 | R$ 419,02 |
| 10 anos | R$ 121.728,83 | R$ 1.217,29 |
| 20 anos | R$ 563.524,50 | R$ 5.635,24 |
| 30 anos | R$ 2.166.952,41 | R$ 21.669,52 |

### 3. Configurações

- **Salário:** R$ 5.000,00
- **Rendimento da carteira:** 1% ao mês
- **Sugestão de investimento:** 30% do salário (R$ 1.500,00)

## 🔧 Fórmulas utilizadas

```excel
=VF(taxa; anos*12; -aporte)        ← patrimônio acumulado
=patrimônio * rendimento_carteira  ← dividendo mensal
=salário * 30%                     ← sugestão de investimento
```
Os prazos dos cenários são multiplicados por 12 para converter anos em meses, já que a taxa é mensal. Em inglês, a função é `FV`.

## 🤖 Como o Claude ajudou
- Explicando a função `VF` e seus argumentos (taxa, número de períodos, pagamento);
- Sugerindo a estrutura da planilha (entradas, cenários e configurações);
- Revisando as fórmulas e apontando erros.

## ▶️ Como usar
1. Abra a planilha (link acima) no Excel ou no Excel Online.
2. Altere o valor mensal, o prazo e a taxa nas células de entrada.
3. Veja o patrimônio, os dividendos e os cenários atualizarem automaticamente.

## ⚠️ Aviso
Simulação com fins educacionais. A taxa de 1,08% ao mês é um valor fixo de exemplo e **não é garantia de rentabilidade**. Isto não é recomendação de investimento.

## 📚 Aprendizados
- Juros compostos com aportes mensais usando `VF`
- Simulação de cenários com fórmulas reaproveitáveis

### 2. 📊 Declaração de Imposto de Renda com Excel
Projeto desenvolvido durante o bootcamp da **DIO**, utilizando **Microsoft Excel** para organizar e consolidar informações necessárias à preparação da Declaração de Imposto de Renda.
A proposta do projeto é transformar diferentes informações financeiras em uma estrutura organizada, facilitando o preenchimento e a conferência dos dados antes da declaração.

## 🎯 Objetivo
Criar uma planilha estruturada para centralizar informações financeiras e organizar os principais dados utilizados no processo de preparação da declaração de Imposto de Renda.
O projeto também reforça conhecimentos fundamentais de **Excel, organização de dados, fórmulas e estruturação de informações**.

## 🗂️ Estrutura da planilha
A planilha está dividida em quatro seções principais:

### 👤 1. Dados do Titular
Área destinada ao cadastro das informações básicas do titular, como:
- Nome
- CPF
- Data de nascimento
- Demais informações cadastrais

### 🏦 2. Informes de Rendimento Bancário
Seção destinada à organização dos informes de rendimento fornecidos pelas instituições financeiras.
Também possui um campo para consolidação dos valores informados.

### 💰 3. Notas Bancárias ou Extratos de Holerites
Área destinada ao registro das entradas financeiras ao longo dos meses.
Os dados são organizados por:
- Data
- Categoria
- Valor
Essa estrutura permite centralizar diferentes fontes de entrada e facilitar a visualização das informações financeiras.

### 📋 4. Dados
Base auxiliar utilizada pela planilha, contendo informações de instituições bancárias e outros dados de apoio ao preenchimento.

## 🛠️ Tecnologias e ferramentas
- Microsoft Excel
- Fórmulas e recursos de planilha
- Organização e estruturação de dados

## 📚 Aprendizados
Este projeto contribuiu para a prática de conceitos fundamentais de Excel, especialmente:
- Organização de dados;
- Estruturação de planilhas;
- Utilização de fórmulas;
- Consolidação de informações;
- Criação de uma estrutura prática para controle financeiro.

## 🔗 Projeto
A planilha completa está disponível no OneDrive:
**[Acessar o projeto no Excel](https://1drv.ms/x/c/aa302b7b523f2ab6/IQB89Gng6UwOTZYPcviFS__LAayfzJudDjiTNs4wO4CYxuk?e=WSfDfX)**
> O arquivo disponibilizado neste repositório serve como apresentação do projeto desenvolvido durante o bootcamp. Para acessar a versão da planilha, utilize o link acima.

## 📌 Observação
Este projeto tem finalidade **educacional**, desenvolvido como parte do aprendizado em Excel e organização de dados. A planilha é uma ferramenta de apoio à organização das informações e não substitui a orientação de um profissional contábil ou as ferramentas oficiais utilizadas para a declaração.

### 👩‍💻 Projeto desenvolvido durante estudos na DIO
**Bootcamp:** Santander — Excel com Inteligência Artificial  
**Tecnologia principal:** Microsoft Excel






