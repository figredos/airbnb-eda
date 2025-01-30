# Respostas

1. Faça uma análise exploratória dos dados (EDA), demonstrando as principais características entre as variáveis e apresentando algumas hipóteses de negócio relacionadas. Seja criativo!

- [(relatório)](./report/report_pt.pdf)

2. Supondo que uma pessoa esteja pensando em investir em um apartamento para alugar na plataforma, onde seria mais indicada a compra?

- O apartamento indicado para fazer compra é em Manhattan, pois é o lugar com maior retorno de investimento, além de ter o maior potencial de retorno.

- [(pergunta de negócio 6)](./report/report_pt.md#6-a-localização-afeta-diretamente-o-preço)

3. O número mínimo de noites e a disponibilidade ao longo do ano interferem no preço?

- De forma muito irrelevante, o valor obtido da correlação do mínimo de noites e o preço foi de 0.04, enquanto o da disponibilidade ao longo do ano foi de 0.08. Apesar de influenciarem de forma ou outra o preço, a relevância dessa influência é muito baixa.

- [(pergunta de negócio 7)](./report/report_pt.md#7-o-número-mínimo-de-noites-e-a-disponibilidade-ao-longo-do-ano-interferem-no-preço)

4. Existe algum padrão no texto do nome do local para lugares de mais alto valor?

- A palavra que mais aparece nas 100 propriedades de maior valor é "luxury", com 12 aparições seguida de "apartment", e "bedroom" com 10.

- [(pergunta de negócio 8)](./report/report_pt.md#8-existe-algum-padrão-no-texto-do-nome-do-local-para-lugares-de-mais-alto-valor)

5. Explique como você faria a previsão do preço a partir dos dados. Quais variáveis e/ou suas transformações você utilizou e por quê? Qual tipo de problema estamos resolvendo (regressão, classificação)? Qual modelo melhor se aproxima dos dados e quais seus prós e contras? Qual medida de performance do modelo foi escolhida e por quê?

- As respostas sobre transformações estão contidas no relatório, e o tipo de problema a ser resolvido é de regressão

- [(Modelagem)](./report/report_pt.md#modelagem)

6. Supondo um apartamento com as seguintes características:

```python
{
    'id': 2595,
    'nome': 'Skylit Midtown Castle',
    'host_id': 2845,
    'host_name': 'Jennifer',
    'bairro_group': 'Manhattan',
    'bairro': 'Midtown',
    'latitude': 40.75362,
    'longitude': -73.98377,
    'room_type': 'Entire home/apt',
    'minimo_noites': 1,
    'numero_de_reviews': 45,
    'ultima_review': '2019-05-21',
    'reviews_por_mes': 0.38,
    'calculado_host_listings_count': 2,
    'disponibilidade_365': 355,
}
```

Qual seria a sua sugestão de preço?

- [(Calculando preço para dado)](./report/report_pt.md#calculando-preço-para-dado)

7. Salve o modelo desenvolvido no formato .pkl.

- [(modelo.pkl)](./models/model.pkl)

8. Um vídeo curto explicando o desenvolvimento de suas entregas deste desafio, como você planejou e executou as atividades propostas.

- [link](https://google.com)
