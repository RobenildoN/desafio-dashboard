# Dashboard de Vendas Xbox

Este projeto consiste em um dashboard de vendas criado no Microsoft Excel, com o objetivo de transformar dados brutos de assinaturas do Xbox Game Pass em informações visuais claras e úteis. Através da organização e visualização dos dados, é possível realizar uma análise eficaz do desempenho de vendas e auxiliar na tomada de decisões estratégicas.

---

## Objetivo do Projeto

O principal objetivo foi a criação de uma ferramenta de análise de dados que responda a perguntas de negócios específicas, como:

* **Faturamento Total:** Qual o faturamento total de vendas de planos anuais, incluindo todas as assinaturas agregadas?
* **Análise por Renovação Automática:** Qual o faturamento total de vendas de planos anuais, mas separado por planos com e sem auto-renovação?
* **Vendas de Assinaturas Adicionais:** Qual o total de vendas das assinaturas **EA Play** e **Minecraft Season Pass**?

---

## Dados Utilizados

A base de dados utilizada é composta pelas seguintes informações de assinantes, que foram obtidas do arquivo `Dashboard.xlsx - Bases.csv`:

* `Subscriber ID`: ID de identificação do assinante.
* `Name`: Nome do assinante.
* `Plan`: Tipo de plano de assinatura (Ultimate, Core, Standard).
* `Start Date`: Data de início da assinatura.
* `Auto Renewal`: Indica se a assinatura possui auto-renovação.
* `Subscription Price`: Preço da assinatura.
* `Subscription Type`: Frequência do pagamento (Mensal, Trimestral, Anual).
* `EA Play Season Pass`: Indica se a assinatura inclui o EA Play.
* `EA Play Season Pass Price`: Preço do EA Play.
* `Minecraft Season Pass`: Indica se a assinatura inclui o Minecraft Season Pass.
* `Minecraft Season Pass Price`: Preço do Minecraft Season Pass.
* `Coupon Value`: Valor de cupons de desconto aplicados.
* `Total Value`: Valor total da venda, incluindo o preço da assinatura e os preços dos passes adicionais, menos o valor do cupom.

---

## Estrutura do Projeto

O projeto em Excel está dividido nas seguintes planilhas:

* **Bases:** Contém os dados brutos dos assinantes e suas respectivas informações.
* **Cálculos:** Planilha utilizada para realizar as análises e responder às perguntas de negócio, servindo como base para as visualizações do dashboard.
* **Dashboard:** A visualização principal que apresenta os insights de forma clara e interativa.
* **Assets:** Contém os recursos de design, como a paleta de cores e logotipos, para garantir a consistência visual do projeto.

---

## Como Reproduzir o Projeto

Para visualizar e interagir com o dashboard, siga as instruções:

1.  Faça o download do arquivo `Dashboard.xlsx` para o seu computador.
2.  Abra o arquivo no **Microsoft Excel**.
3.  O dashboard já estará pronto para visualização na aba principal (`Dashboard`). Você poderá usar os filtros interativos para explorar diferentes métricas.
4.  Para entender as análises subjacentes, navegue até a planilha **Cálculos**.
5.  A base de dados original pode ser encontrada na planilha **Bases**.
