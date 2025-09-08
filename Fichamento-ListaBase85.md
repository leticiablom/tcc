# Exploiting Vision-Language Models in GUI Reuse

Niu, Victoria; Niu, Nan; Alshammari, Walaa; Bhowmik, Tanmay; Iluru, Naga Mamata; Teeleti, Padmaja Vaishnavi; Zhang, Jianzhang. "Exploiting Vision-Language Models in GUI Reuse". Publicado em: [10.7945/nkr8-zq38](https://doi.org/10.7945/nkr8-zq38)

## 1. Fichamento de Conteúdo

O artigo investiga como Modelos de Visão-Linguagem (VLMs), uma técnica de inteligência artificial, podem aprimorar o processo de prototipagem de interfaces gráficas de usuário (GUI). O problema central abordado é que as ferramentas atuais são boas em recuperar GUIs existentes com base em uma consulta, mas oferecem pouco suporte para o reuso efetivo dessas GUIs na criação de novas. Para resolver essa lacuna, os autores propõem um "_reuso centrado na GUI", onde uma única interface pode gerar múltiplas direções de reuso. O método empregado foi um estudo empírico com 73 estudantes universitários, que realizaram tarefas de redesenho de GUIs a partir de recomendações geradas tanto por VLMs quanto por um método tradicional baseado em linguagem natural (NL). Os resultados demonstraram que os VLMs foram significativamente superiores ao método NL para sugerir direções de reuso. Contudo, os "elementos focados", que são partes específicas da GUI sugeridas como ponto de partida para as modificações, não foram consistentemente alterados pelos participantes. Adicionalmente, uma avaliação de criatividade feita por _designers_ experientes concluiu que os protótipos criados por humanos eram mais inventivos do que os gerados por uma IA generativa.

## 2. Fichamento Bibliográfico

* _GUI-centered reuse_ (reuso centrado na GUI) é uma abordagem onde a interface gráfica é tratada como o elemento principal, da qual podem derivar múltiplas direções de reuso (representadas por frases-chave), em vez de ser apenas o resultado de uma busca por uma consulta específica 
* _Vision-Language Models (VLMs)_ (Modelos de Visão-Linguagem) são modelos de IA treinados com vastos conjuntos de dados de imagem-legenda. No estudo, eles são usados para analisar uma imagem de GUI e recomendar tanto a direção de reuso mais adequada (frase-chave) quanto um elemento específico na tela para iniciar a modificação 
* _Focused GUI element_ (elemento de GUI focado) é um componente específico da interface (como um botão ou um ícone) que é sugerido ao _designer_ como um ponto de partida para realizar as alterações de reuso, com o objetivo de reduzir o esforço cognitivo necessário para a tarefa 
* _Cognitive distance_ (distância cognitiva) é um conceito informal que descreve o esforço intelectual necessário para um desenvolvedor levar um sistema de um estágio a outro. O artigo explora se a recomendação de um "elemento focado" ajuda a reduzir essa distância durante o reuso de GUIs
* _Clever reuse_ (reuso inteligente) é definido como um atributo primário da criatividade no trabalho prático de engenharia de software. O estudo utiliza essa perspectiva para avaliar a qualidade e a criatividade dos resultados de reuso produzidos tanto por humanos quanto por IA

## 3. Fichamento de Citações

* _"While contemporary approaches retrieve GUIS relevant to a user's query, little support exists for the actual reuse, i.e., for using an existing GUI to create a new one."_
* _"Our results show that VLMs significantly outperform the NL method in making reuse recommendations, but surprisingly, the focused GUI elements are not consistently modified during reuse."_
* _"Clever reuse is a primary attribute of creativity in practitioners daily work [7]."_
* _"The focused GUI elements are generally revised more often than the non-focused ones, but the differences are not significant. How to best tackle cognitive distance in the actual change part of GUI reuse thus remains an open challenge."_
* _"This may suggest that, currently, compared to generative Al, humans are better at sketching new GUI designs that embrace a high degree of cleverness and creativity."_
* _"A puzzling result, as shown in Fig. 8, is that the NL- based method performed the worst in making reuse direction recommendations."_
