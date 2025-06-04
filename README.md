# 📊 Simulador de Investimento

Este é um simulador simples feito em planilha eletrônica (Excel, Google Sheets, etc.), que ajuda a calcular o crescimento de um investimento mensal ao longo dos anos. O foco é em investimentos em FIIs (Fundos Imobiliários), com uma alocação proporcional conforme o perfil de investidor.

---

## 🔧 CONFIGURAÇÃO INICIAL

Antes de qualquer cálculo, é preciso informar:

- **Salário:** quanto a pessoa ganha por mês. Ex: `R$ 1.000,00.` A partir desse dado haverá uma sugestão de investimento: quanto seria interessante investir mensalmente com base nesse salário. Ex: `R$ 300,00`

---

## 💸 INVESTIMENTO MENSAL

Aqui definimos os parâmetros do investimento:

- **Quanto investir por mês?** Valor fixo que será aplicado mensalmente. Ex: `R$ 300,00`
- **Por quantos anos?** Período do investimento. Ex: `10`
- **Taxa de rendimento mensal:** Percentual de rentabilidade estimada ao mês. Ex: `1,079%`

Com essas informações, a planilha calcula:

- **Patrimônio acumulado:** Total estimado ao final do período.
- **Dividendos por mês:** Quanto esse patrimônio pode gerar em rendimentos mensais (assumindo a mesma taxa de 1,079%).

---

## 📈 CENÁRIOS FUTUROS

Com base na mesma taxa e no investimento constante, a planilha projeta o valor acumulado ao longo dos anos:

- **2 anos:** R$ 8.168,29  
- **5 anos:** R$ 25.133,07  
- **10 anos:** R$ 72.985,26  
- **20 anos:** R$ 337.559,52  
- **30 anos:** R$ 1.296.650,90  

---

## 👤 PERFIL DO INVESTIDOR

O perfil influencia na **distribuição dos investimentos**. Neste exemplo, o perfil é **Conservador**, o que afeta a divisão dos tipos de FII.

- **Valor mensal a investir:** R$ 300,00

---

## 🧱 TIPO DE FII

A planilha separa o investimento mensal entre os diferentes tipos de Fundos Imobiliários (FIIs):

| Tipo de FII         | Percentual | Valor      |
|---------------------|------------|------------|
| Papel               | 30%        | R$ 90,00   |
| Tijolo              | 50%        | R$ 150,00  |
| Híbridos            | 10%        | R$ 30,00   |
| FOFs                | 10%        | R$ 30,00   |
| Hotelarias          | 0%         | R$ 0,00    |
| Desenvolvimento     | 0%         | R$ 0,00    |

Os valores são calculados automaticamente com base no percentual e no valor mensal de investimento.

---

---

## 📝 Observações

- A rentabilidade é uma simulação. No mundo real, os rendimentos variam.
- A alocação de FII pode ser ajustada conforme o perfil: moderado, agressivo, etc.
- Ideal para quem quer começar a investir e visualizar o potencial de longo prazo.

