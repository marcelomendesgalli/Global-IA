# DISRUPTIVE ARCHITECTURES: IOT, IOB & GENERATIVE IA

## Integrantes
Vinicius Malavia Lorenzetti - RM: 553121
João Pedro Fontana - RM: 553343
Marcelo Galli - RM: 553654

## Vídeo
https://youtu.be/jfX4xhzpSxE

## Tema
O tema escolhido para o nosso projeto foi: **Análise de Dados e IA para a Redução de Gastos Energéticos**.

## Problemas
O setor elétrico enfrenta desafios significativos relacionados ao consumo de energia e à gestão de custos, incluindo:

- **Ineficácia no uso da energia**: Muitos consumidores não têm consciência de seu consumo, resultando em contas elevadas e desperdício de recursos.
- **Dificuldade de acesso aos serviços de pagamento e monitoramento**: Especialmente em áreas periféricas e rurais, onde o acesso às redes elétricas é limitado.
- **Falta de transparência e controle**: A comunicação ineficaz entre consumidores e fornecedores dificulta a resolução de problemas e a gestão financeira.

## Objetivo da Solução
Desenvolver uma solução baseada em análise de dados e inteligência artificial para analisar o consumo de energia e sugerir formas personalizadas de redução de custos. A proposta é implementar um sistema que:

- Monitore dados de consumo em tempo real.
- Alerta os usuários sobre comportamentos que podem levar ao desperdício.
- Sugira melhores práticas para o uso eficiente da energia.

## Aplicação de Conceitos e Técnicas de ML/IA
### Modelos Preditivos
- **Classificação com Random Forest**: Utilizado para categorizar o consumo de energia, identificando grupos com base em padrões de uso.
- **Regressão Logística**: Implementada para prever as categorias de consumo de energia (alto, médio, baixo), proporcionando uma abordagem adicional para entender os padrões de consumo e auxiliar na tomada de decisões.

### Análise de Dados
- **Análise Estatística Descritiva**: Para entender os padrões de consumo e identificar anomalias.
- **Visualização de Dados**: Usando bibliotecas como Matplotlib e Seaborn para ilustrar tendências de consumo e gerar relatórios.

### Detecção de Anomalias
- **Isolation Forest**: Para identificar comportamentos de consumo que se desviam do padrão esperado.

## Frameworks e Bibliotecas
- **Pandas**
- Uso: Manipulação e análise de dados, essencial para pré-processamento.
- Motivo: Facilita a leitura, limpeza e análise exploratória de dados.

- **Scikit-Learn**
- Uso: Implementação de modelos de Machine Learning, incluindo classificação e regressão.
- Motivo: Oferece uma ampla gama de algoritmos e é fácil de usar para desenvolvimento rápido.

- **Matplotlib e Seaborn**
- Uso: Visualização de dados e resultados de modelos.
- Motivo: Gráficos ajudam na interpretação visual de padrões no consumo de energia.

## Dataset
O dataset utilizado no nosso modelo foi obtido a partir de fontes abertas, contendo informações de consumo de energia de consumidores residenciais. Nele, temos dados de 2006 a 2011, porém utilizamos apenas os dados de 2006 a 2009. Link do dataset: https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption

## Ferramenta de Desenvolvimento
A ferramenta escolhida para o desenvolvimento deste projeto foi o **Google Colab**, uma vez que todos os integrantes do grupo já estavam familiarizados com a ferramenta, facilitando a colaboração em tempo real.

## Considerações Finais do Projeto
Ao longo deste projeto, exploramos como a aplicação de técnicas de Machine Learning e Inteligência Artificial pode transformar a forma como os consumidores abordam a redução de custos energéticos. Utilizando modelos preditivos, como a classificação com Random Forest e a regressão logística, buscamos entender melhor os padrões de consumo, permitindo intervenções mais eficientes e personalizadas.

A implementação de técnicas de análise e visualização de dados proporciona insights valiosos sobre o consumo, aumentando a conscientização e controle dos usuários sobre seus gastos com energia. Acreditamos que, ao integrar essas soluções, poderemos contribuir para um futuro mais sustentável e eficiente no uso de energia.

