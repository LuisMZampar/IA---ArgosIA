ArgosIA

Descrição do Projeto
ArgosIA é um sistema inovador de recomendação de produtos focado em entender o comportamento de compra de diferentes perfis de clientes e seus remetentes. Nosso objetivo é criar uma experiência de recomendação mais personalizada e precisa, 
capturando não apenas as preferências do cliente principal, mas também as de seus remetentes de compra, ou seja, pessoas para quem o cliente regularmente compra.

A aplicação permite que cada perfil de usuário escolha o público-alvo que ele deseja receber recomendações, filtrando por dados como gênero e idade. Com base nesse perfil, o sistema irá sugerir produtos relevantes, 
utilizando uma abordagem que cria uma espécie de "árvore genealógica" de remetentes de compra para cada usuário.

Funcionalidade Principal
Cada cliente pode associar perfis de remetentes ao seu próprio perfil, indicando para quem realiza compras regularmente. A partir dessa relação, 
o sistema consegue identificar os remetentes-alvo e recomendar produtos baseados nas preferências desses indivíduos.

Exemplo:
Uma senhora de 65 anos, que compra mensalmente para seu filho de 17 anos (remetente 1, sexo masculino) e para uma senhora de 84 anos (remetente 2, sexo feminino).
O sistema identifica que as recomendações devem levar em consideração o gênero e a idade dos remetentes associados ao perfil principal, fornecendo sugestões de produtos para o filho e a senhora de 84 anos, que são os "remetentes de compra" dela.

Objetivo
Nosso principal objetivo com o ArgosIA é proporcionar uma experiência de compra mais personalizada, oferecendo recomendações de produtos que realmente atendam às necessidades do cliente e de seus remetentes, 
facilitando a escolha de presentes ou compras frequentes. Assim, ampliamos a personalização do e-commerce, não apenas recomendando produtos para o cliente, mas também para os indivíduos que fazem parte de sua rotina de compras.

Tecnologias Utilizadas
Python para processamento e análise de dados.
Pandas para manipulação de dados e criação de perfis de clientes e remetentes.
Modelos de Machine Learning como Random Forest, SVM, e KNN para prever produtos recomendados com base no perfil de compra.

Como Funciona
O cliente cria um perfil e associa remetentes de compra ao seu perfil.
O sistema utiliza os dados de idade, gênero e histórico de compras do cliente e dos remetentes.
Com esses dados, os modelos de machine learning recomendam produtos que são relevantes para o cliente ou para os remetentes.
As recomendações podem ser ajustadas de acordo com as preferências do cliente, garantindo sugestões mais precisas e personalizadas.
