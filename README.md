# Análise de Correlação Canônica: Infraestrutura vs. Desenvolvimento Humano nos Municípios Brasileiros

📌 Sobre o Projeto
Este projeto aplica técnicas de estatística multivariada para investigar a relação entre o porte/infraestrutura urbana e os índices de desenvolvimento social dos municípios brasileiros. A análise utiliza Análise de Correlação Canônica (ACC) para identificar como variáveis de economia e serviço impactam diretamente o IDHM.

## 📊 Principais Resultados
1. Correlação entre os Pares Canônicos
A análise revelou uma correlação canônica de 0,36 no primeiro par, indicando uma associação moderada e positiva entre os blocos de dados.

Interpretação: O gráfico de dispersão mostra que, à medida que os scores de infraestrutura (Eixo X) aumentam, há uma tendência clara de elevação nos scores de desenvolvimento social (Eixo Y).

Distribuição: A elipse central demonstra que a maioria dos municípios brasileiros compartilha um perfil de infraestrutura e desenvolvimento básico, enquanto os outliers revelam cidades que conseguiram converter alta capacidade econômica em bem-estar social superior.

2. Influência das Variáveis (HE Plots)
Através do Hypothesis-Error Plot, identificamos os "motores" dessa relação:

Infraestrutura (Set X): Variáveis como Frota de Carros, Telefonia Fixa e População apresentaram as maiores cargas, sendo os principais preditores do modelo.

Desenvolvimento (Set Y): O IDHM Educação e IDHM Renda foram os indicadores mais sensíveis à infraestrutura municipal.

## 🛠️ Tecnologias Utilizadas
Linguagem R (v4.4+)

Pacotes Principais: CCA, candisc, ggplot2 e tidyverse.

## 📈 Conclusão
O estudo conclui que a infraestrutura urbana é uma condição facilitadora para o desenvolvimento humano. Municípios com serviços mais robustos tendem a apresentar melhores indicadores de educação e renda, embora a correlação de 0,36 sugira que a gestão pública e outros fatores regionais também desempenham papéis cruciais na qualidade de vida final da população.
