# python_social_distance_alert

## Open In Colab
Este projeto pode ser executado diretamente no Google Colab para facilitar a visualização e execução dos resultados.

## Notebooks

### Main [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KauaHenSilva/python_social_distance_alert/blob/main/main.ipynb)

Este repositório contém um Jupyter Notebook que demonstra a técnica de detecção de distanciamento social utilizando a biblioteca OpenCV. O notebook é otimizado para execução no Google Colab, permitindo testar e visualizar os resultados diretamente na nuvem.

#### Funcionalidade: Detecção de distanciamento social em vídeos.
Este notebook implementa a técnica de detecção de distanciamento social utilizando diferentes métodos de subtração de fundo.

#### Principais Funcionalidades:
- Carregamento de vídeos armazenados no Google Drive.
- Subtração de fundo utilizando os métodos GMG, MOG, MOG2, KNN e CNT.
- Utilização de 2 metodos para visualização do alerta.
- Exibição dos resultados diretamente no notebook.

## Como Usar no Google Colab
Para executar o notebook no Google Colab, siga os passos abaixo:

1. Acesse o Google Colab:
  - Abra o Google Colab.

2. Carregue o Notebook:
  - Clique em Arquivo > Abrir notebook.
  - Escolha a aba GitHub e insira o link deste repositório.
  - Selecione o notebook `main.ipynb`.

3. Conecte ao Google Drive (se necessário):
  - O notebook exige acesso ao Google Drive para carregar vídeos.

4. Execute as Células:
  - Conecte-se ao ambiente clicando em Conectar no canto superior direito.
  - Execute as células sequencialmente para processar o vídeo e visualizar os resultados.

5. Teste com seus Próprios Vídeos (Opcional):
  - Faça o upload de um vídeo diretamente no Google Colab usando:
    ```python
    from google.colab import files
    uploaded = files.upload()
    ```
  - Substitua o caminho do vídeo no notebook pelo arquivo enviado.
