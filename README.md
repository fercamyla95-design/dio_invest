# 🧮  DIO - Santander - Excel com IA e Claude

Projeto **Invest Agro**: uma planilha de simulação de investimentos feita no Excel durante o bootcamp **DIO + Santander**, com o **Claude** como apoio na construção das fórmulas e na organização das tabelas.

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






