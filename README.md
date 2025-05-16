📚 Classificação de Imagem com Hugging Face Transformers
Este notebook foi desenvolvido como parte da formação em Machine Learning da Pretalab, com o objetivo de aplicar conceitos de classificação de imagem utilizando modelos pré-treinados disponíveis na biblioteca transformers.

🧠 Contexto Geral
Neste projeto, utilizamos um pipeline de classificação de imagens para prever o conteúdo de uma imagem com base em modelos de deep learning já treinados. A proposta é mostrar como, com poucas linhas de código, é possível utilizar modelos poderosos como o google/vit-base-patch32-384 para tarefas de visão computacional.

As etapas principais do notebook incluem:

Download de uma imagem via URL

Utilização de pipeline da Hugging Face para classificar a imagem

Interpretação dos resultados

🛠️ Tecnologias Utilizadas
Python 3.11
Google Colab
Hugging Face Transformers
PIL (Python Imaging Library)

▶️ Como Executar
Abrindo o notebook no Google Colab:

Monte seu Google Drive (se necessário):
from google.colab import drive
drive.mount('/content/drive')

Execute as células na ordem, clicando no botão de play (▶️) à esquerda de cada célula ou usando Ctrl + F9 para rodar tudo.

Observação: Alguns modelos da Hugging Face requerem autenticação com token (HF_TOKEN) para acesso completo. Para isso, crie uma conta gratuita em https://huggingface.co e configure seu token, se necessário.

