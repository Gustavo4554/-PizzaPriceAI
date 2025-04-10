# 🍕 Previsor de Preço de Pizza com Streamlit

Este projeto utiliza **Python**, **pandas**, **scikit-learn** e **Streamlit** para prever o preço de uma pizza com base no seu diâmetro. A aplicação treina um modelo de **regressão linear** a partir de um dataset (`pizzas.csv`) contendo tamanhos e preços de pizzas.

## 🚀 Como funciona

O modelo é treinado para aprender a relação entre o diâmetro da pizza e seu preço. Ao informar o diâmetro desejado, a aplicação retorna uma estimativa de quanto custaria uma pizza com esse tamanho.

## 📦 Requisitos

- Python 3.7+
- streamlit
- pandas
- scikit-learn

Você pode instalar os requisitos com:

```bash
pip install -r requirements.txt
```

> **Dica**: Crie um arquivo `requirements.txt` com o seguinte conteúdo:
> ```
> streamlit
> pandas
> scikit-learn
> ```

## 🧠 Treinamento do modelo

O modelo é treinado diretamente no código a partir do arquivo `pizzas.csv`. O arquivo deve conter pelo menos duas colunas:
- `diametro`: tamanho da pizza em centímetros.
- `preco`: valor da pizza em reais.

Exemplo de conteúdo do `pizzas.csv`:

```csv
diametro,preco
20,25
25,35
30,45
```

## 💻 Como executar

Basta rodar o comando abaixo no terminal:

```bash
streamlit run app.py
```

## 🖼️ Interface

A interface permite que o usuário digite o diâmetro desejado e veja na tela o preço previsto para a pizza, com uma pequena animação 🎈 quando o resultado aparece.

## 📁 Estrutura do projeto

```
📁 seu-projeto/
├── app.py
├── pizzas.csv
└── README.md
```

## 📌 Observações

- O modelo é simples e serve apenas para fins educativos.
- Ideal para quem está começando com Machine Learning e quer ver resultados rápidos com Streamlit.
