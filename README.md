# Lunar Lander

Exercício do Lunar Lander feito com DQN, devido a extensão da complexidade do problema é que foi o motivo para uso do DQN;

**Obs:** Foi usado duas redes neurais, a rede atualizada durante todo o treinamento e a rede target atualizada no término de um episódio. Outrora, outra observação é que foi feito somente 30 episódios, por motivos da memória RAM ter estourado dentre três tentativas com uma quantidade maior de episódios, partindo disso, o principal motivo foi atualização dos pesos da rede, porém a lógica para a atualização é bem direcionada e me serviu como aprendizagem.

## Análise dos resultados pelo gráfico

A partir do gráfico plotado, houve somente um caso de grande ocilação de reward total negativo em um episódio, pois os episódios manteram uma constância de resultados, e gostaria de acrescentar que houve um agrupamento de casos com recompensa positiva. Portanto, os resultados ficaram variando, mas se mantiveram numa faixa demonstrando uma certa constância.
