# Projeto IV - Análise de Voos Domésticos Atrasados e Cancelados em Janeiro de 2023 nos EUA

## Descrição do Projeto

Análise de dados de voos domésticos nos EUA para identificar padrões de atrasos e cancelamentos em janeiro de 2023. O projeto visa auxiliar o Bureau of Transportation Statistics (BTS) a entender melhor os fatores que influenciam o tráfego aéreo, como feriados e condições climáticas adversas.

## Informações sobre o Projeto

### Cliente, Contexto, Objetivos e Hipóteses

O Bureau of Transportation Statistics (BTS) é um órgão estadunidense responsável pela coleta, análise e divulgação de dados sobre o sistema de transporte do país, fazendo parte do Departamento de Nacional de Transportes. A DataLab foi contratada para auxiliar na análise destes dados. O objetivo da análise solicitada foi examinar as companhias operantes de voos domésticos no país, principalmente indicadores de voos cancelados e atrasados. Com os resultados desenvolvidos, o órgão americano poderia reconhecer alguns problemas que influenciaram o fluxo de tráfego aéreo no país durante o período de janeiro de 2023.

### Questões de Negócios

1. **Feriados nacionais influenciaram no aumento de atrasos de voos em janeiro de 2023?**
   - Feriados analisados: 01 e 02 de janeiro (Ano Novo) e 16 de janeiro (Dia de Martin Luther King).

2. **Condições climáticas adversas foram um fator determinante para o aumento do número de cancelamentos de voos em janeiro de 2023?**
   - Condições adversas consideradas: névoa (fog), chuva de forte intensidade (heavy intensity rain), fumaça (smoke), tempestade (thunderstorm), tempestade com chuva forte (thunderstorm with heavy rain) e tempestade com chuva leve (thunderstorm with light rain).

3. **Quais são as 5 companhias aéreas com as maiores taxas de atraso e cancelamento em janeiro de 2023?**
   - Análise da quantidade absoluta e quantidade normalizada.

4. **Os cinco aeroportos com maior fluxo de voos em janeiro de 2023 são os que mais sofreram cancelamentos neste período?**

### Hipóteses

1. Os feriados nacionais nos EUA influenciaram no aumento dos atrasos de voos em janeiro de 2023.
2. Condições climáticas adversas, como névoa, chuva de forte intensidade, fumaça, tempestade, tempestade com chuva forte e tempestade com chuva leve, foram fatores determinantes para o aumento do número de cancelamentos de voos em janeiro de 2023.
3. As 5 companhias aéreas com maior fluxo de voos domésticos estão relacionadas com as maiores taxas de atraso em janeiro de 2023 nos EUA.
4. Os cinco aeroportos com maior fluxo de voos em janeiro de 2023 são os que mais sofreram cancelamentos durante este período.

## Informações sobre a Equipe e Ferramentas

### Equipe

- **Bruna Paiva**
  - GitHub: [bsap16](https://github.com/bsap16)
  - LinkedIn: [Bruna Paiva](http://www.linkedin.com/in/bruna-paiva16)
  - E-mail: brunasap16@gmail.com

- **Bruna Pereira**
  - GitHub: [pereirasbruna](https://github.com/pereirasbruna)
  - LinkedIn: [Bruna Pereira](https://www.linkedin.com/in/brunapereiras/)
  - E-mail: brunapereiradossantos@live.com

### Ferramentas

- **Linguagem para limpeza de dados**
  - Python (Google Colab)

- **Visualização de dados**
  - Power BI
  - Figma

- **Apresentação dos dados**
  - Google Apresentações

- **Apresentação dos dados via vídeo**
  - Loom

## Limitações e Conclusões

### Limitações Encontradas

- Corte temporal de somente um mês no ano (janeiro de 2023);
- Falta de informação sobre a quantidade de passageiros;
- Sem ID único de cada voo informado no dataset;
- FL_CODE (código companhia aérea + número de voo) não são valores únicos. Existem casos em que o mesmo FL_CODE possui origens e destinos diferentes;
- Voos realizados somente em um corte específico de tempo (janeiro de 2023), sendo difícil gerar predições concretas;
- Valores nulos relativos a atraso no dataset eram importantes para análises referente a este evento. Muitos valores omitidos. Se esses valores fossem informados, possivelmente as análises realizadas sobre os motivos de atraso gerariam informações diferentes.

### Recomendações

- Utilização de ferramentas para Big Data, visto que o arquivo é grande e demanda tempo e recursos para manipulação em ferramentas básicas;
- Cruzar informações com outros meses do ano, para assim gerar predições mais concretas referentes às companhias aéreas e aeroportos.

### Conclusões

- Feriados modificam a logística do aeroporto e da companhia aérea. Nestes dias atípicos é necessária uma atenção redobrada nos processos;
- Condições climáticas adversas possuem valores baixos de taxa de cancelamento, não tão significativas quanto o esperado;
- A maior capacidade do aeroporto possui relação com a quantidade de cancelamento dos voos, entretanto, não tão significativo quanto o esperado. Cancelamentos geralmente estão relacionados com a segurança da operação do voo e maiores aeroportos possuem maiores fluxos de voo, logicamente possuindo uma quantidade maior de cancelamentos. Entretanto, ao analisar a taxa de cancelamento por aeroportos, o ranking apresenta aeroportos não reconhecidos como de alto fluxo. Para reconhecer os motivos desta diferença, é necessária uma análise mais robusta;
- No turno da noite ocorre um pico de cancelamentos e atrasos. Necessário maiores análises para reconhecer possíveis motivos.


## Materiais Gerados

- Dashboard no Power BI;
- Apresentação de slides para os clientes.