# Projeto de Análise de Dados do Google Analytics

## Descrição do Projeto

Este projeto foi desenvolvido como parte de um processo seletivo, onde foram fornecidos dados públicos do Google Analytics para análise. O objetivo principal era explorar e entender o comportamento da audiência, identificar tendências de engajamento e propor ações estratégicas para otimizar a experiência do usuário e o desempenho do site. O prazo para a conclusão do projeto foi de **3 dias**, o que exigiu uma abordagem ágil e eficiente.

A análise foi realizada utilizando **Python** e diversas bibliotecas de manipulação e visualização de dados, como **Pandas**, **NumPy**, **Matplotlib**, **Seaborn** e **Scikit-learn**. O projeto foi aprimorado para incluir explicações detalhadas, tornando-o acessível não apenas para profissionais de negócios, mas também para pessoas da área de dados que desejam aprender e entender o processo de análise de dados.

---

## Objetivos do Projeto

- **Compreender a distribuição de visitas por canais de marketing**: Identificar quais canais (busca orgânica, redes sociais, tráfego direto, etc.) estão trazendo mais tráfego para o site.
- **Analisar o comportamento da audiência por tipo de dispositivo**: Verificar como os usuários estão acessando o site (desktop, mobile, tablet) e identificar tendências de uso.
- **Identificar mudanças ao longo do tempo**: Comparar os dados de **2016** e **2017** para detectar tendências e mudanças no comportamento da audiência.
- **Propor ações estratégicas**: Sugerir melhorias para aumentar o engajamento e a eficácia das campanhas de marketing.

---

## Metodologia

O projeto foi desenvolvido utilizando as seguintes ferramentas e bibliotecas:

- **Pandas**: Para manipulação e limpeza de dados, incluindo leitura de arquivos CSV, tratamento de valores ausentes e transformação de colunas.
- **NumPy**: Para operações matemáticas e manipulação de arrays, especialmente em cálculos estatísticos.
- **Matplotlib e Seaborn**: Para criação de visualizações claras e informativas, como gráficos de distribuição de visitas por canal de marketing e comportamento por dispositivo.
- **Scikit-learn**: Para tratamento de valores ausentes (`SimpleImputer`) e análise de correlação (`LinearRegression`).
- **Expressões Regulares (re)**: Para processar e limpar textos em colunas específicas, garantindo a consistência dos dados.

---

## Análise Exploratória

A análise exploratória foi realizada para entender a estrutura dos dados e identificar possíveis problemas, como valores ausentes. As colunas foram renomeadas para facilitar a compreensão e a manipulação dos dados. Algumas das colunas renomeadas incluem:

| Coluna Original         | Coluna Renomeada           | Descrição                                                                 |
|-------------------------|----------------------------|---------------------------------------------------------------------------|
| `Date`                  | `Data`                     | Representa a data em que os dados foram coletados.                        |
| `channel_grouping`      | `canal_de_marketing`       | Indica o canal de marketing que trouxe o visitante ao site.               |
| `device_category`       | `categoria_de_dispositivo` | Mostra o tipo de dispositivo usado pelo visitante (desktop, mobile, etc.).|
| `total_visits`          | `total_visitas`            | Contabiliza o número total de visitas ao site.                            |
| `total_pageviews`       | `total_paginas_visualizadas`| Mostra quantas páginas foram visualizadas pelos visitantes.               |
| `total_timeonsite`      | `tempo_total_no_site`      | Mede o tempo gasto pelos usuários no site.                                |

---

## Resultados

A análise revelou insights importantes sobre o comportamento da audiência:

### Distribuição de Visitas por Canal de Marketing
- **Busca Orgânica**: Dominou o tráfego, representando **36,2%** em 2016 e **38,8%** em 2017.
- **Tráfego Direto**: Manteve-se estável, com **25,2%** em 2016 e **24,4%** em 2017.
- **Redes Sociais**: A participação caiu de **7,7%** em 2016 para **6,6%** em 2017.

### Comportamento por Dispositivo
- **Desktop**: Ainda dominante, mas com queda de **78,7%** em 2016 para **74,3%** em 2017.
- **Mobile**: Aumentou de **17,9%** em 2016 para **22,3%** em 2017, refletindo a tendência global de migração para dispositivos móveis.

### Mudanças ao Longo do Tempo
- Houve uma migração significativa para dispositivos móveis e uma queda no tráfego das redes sociais.

---

## Conclusões e Recomendações

Com base nos resultados, foram propostas as seguintes ações estratégicas:

1. **Otimização Mobile**: Investir em uma experiência mobile mais robusta e responsiva.
2. **Estratégia de Redes Sociais**: Reavaliar e intensificar a presença nas redes sociais com campanhas direcionadas e conteúdo interativo.
3. **SEO**: Continuar investindo em SEO para manter e aumentar o tráfego orgânico.
4. **Fidelização de Usuários**: Criar estratégias para fidelizar usuários e aumentar as visitas diretas.

---

## Próximos Passos

O projeto pode evoluir com as seguintes análises adicionais:

1. **Análise de Cohort**: Para entender a retenção de usuários ao longo do tempo.
2. **Segmentação de Audiência**: Dividir a audiência em grupos com base em comportamento, demografia, etc.
3. **Testes A/B**: Para testar diferentes estratégias de marketing e otimização de site.
4. **Análise de Conversão**: Entender quais canais e dispositivos geram mais conversões (vendas, inscrições, etc.).

---

## Como Utilizar Este Projeto

Este projeto foi desenvolvido para ser acessível tanto para profissionais de negócios quanto para pessoas da área de dados. O código e as análises estão disponíveis para que qualquer pessoa possa replicar o processo, aprender com ele e aplicar as técnicas em seus próprios projetos.

### Passos para Execução:

1. **Instalação das Dependências**:
   Certifique-se de ter Python instalado e utilize o arquivo `requirements.txt` para instalar as bibliotecas necessárias.
   ```bash
   pip install -r requirements.txt
