<p align="center">
  <img src="../../IMAGENS/storytelling.png" alt="Storytelling de Dados - Projeto Delivery" width="500px">
</p>

# Projeto Prático – Storytelling de Dados: Satisfação de Clientes em Delivery

## 🎯 Contexto do Negócio

Este projeto simula o cenário de uma **empresa de delivery** que atua nas principais capitais brasileiras e deseja entender melhor os fatores que influenciam a **satisfação dos clientes**.  
O foco é analisar como o **tempo médio de entrega** e o **volume de entregas** se relacionam com a **nota de satisfação** (0 a 10) em cada cidade, gerando **insights acionáveis** para melhoria do NPS (Net Promoter Score) e da operação logística. 

No case, a squad Nina da Hora atuou como um time de dados responsável por analisar os indicadores de cinco cidades e traduzir os resultados em uma narrativa clara para o time de negócios e operações.

## 📍 Escopo e Perguntas de Análise

As análises foram conduzidas para cinco capitais brasileiras:

- São Paulo  
- Rio de Janeiro  
- Belo Horizonte  
- Curitiba  
- Salvador  

Com base nesses dados, o projeto busca responder principalmente:

1. **Como o tempo médio de entrega impacta a satisfação dos clientes?**  
2. **Cidades com maior volume de entregas apresentam queda na nota de satisfação?**  
3. **Quais cidades precisam de atenção prioritária para melhorar o NPS?** 

## 📊 Dados e Variáveis

Para cada cidade, trabalhamos com:

- **Tempo médio de entrega** (em minutos)  
- **Satisfação média dos clientes** (nota de 0 a 10)  
- **Número de entregas no mês**

Essas métricas permitiram investigar a relação entre **eficiência operacional** (tempo/volume) e **percepção do cliente** (satisfação/NPS).

## 🧠 Metodologia e Storytelling

O projeto foi desenvolvido em formato de **notebook de análise** (Python/Colab), seguindo uma estrutura de storytelling de dados. Além disso, o design utilizado na apresentação da squad foi construído no **Canva**, reforçando a comunicação visual dos resultados e insights do projeto.

1. **Contextualização do problema**  
2. **Exploração das métricas por cidade**  
3. **Criação de gráficos usando bibliotecas Python**, comparando:
   - Tempo médio de entrega × satisfação  
   - Volume de entregas × satisfação  
4. **Identificação de padrões e destaques**, com foco nas cidades com melhor e pior desempenho  
5. **Síntese de um insight principal** a partir das análises  
6. **Recomendações práticas para o time de operações/logística**, orientadas à melhoria do NPS

## 💡 Principais Insights

- Cidades com **tempo médio de entrega mais alto** tendem a apresentar **notas de satisfação menores**, indicando que reduzir o tempo de entrega é um fator chave para a melhoria da experiência do cliente.  
- Em algumas capitais, o **alto volume de entregas** não necessariamente implica queda na satisfação, sugerindo que processos logísticos eficientes permitem escalar a operação mantendo boa percepção do serviço.
- Há cidades que se destacam positivamente, combinando **tempo de entrega competitivo** e **alta satisfação**, servindo como referência de boas práticas para outras regiões.

## ✅ Recomendações para o Negócio

Com base na análise, o projeto sugere ações como:

- Priorizar a **redução do tempo médio de entrega** nas cidades com satisfação mais baixa, revisando rotas, janelas de entrega, novas tecnologias e alocação de recursos.  
- Avaliar a necessidade de **reforço de frota** ou parcerias logísticas em horários de pico nas cidades críticas.  
- Acompanhar continuamente os indicadores de **tempo**, **volume** e **satisfação** por cidade, integrando essas métricas em painéis de monitoramento para suportar decisões de melhoria contínua do NPS. 

## 🛠️ Tecnologias e Ferramentas

- **Linguagem:** Python  
- **Ambiente:** Google Colab / Jupyter Notebook / Canva 
- **Bibliotecas:** `pandas`, `numpy`, `matplotlib` e/ou `seaborn` e `ploty`  
- **Abordagem:** Análise exploratória de dados (EDA) e storytelling com gráficos e texto

## 📁 Estrutura do Repositório

- `notebooks/`
  - `01_exploracao_inicial.ipynb`: primeiro notebook com a exploração dos dados e análises iniciais.
  - `02_storytelling_delivery.ipynb`: notebook principal com a narrativa de storytelling, gráficos e recomendações.
- `apresentacao/`
  - `storytelling_delivery_squad.pptx`: slides utilizados na apresentação da squad, construídos no Canva.
  
  
