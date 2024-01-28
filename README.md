# Projeto de SIN 492 - Reconhecimento de Padrões

## Descrição

Este repositório contém o código-fonte e o conjunto de dados utilizados no projeto desenvolvido durante a disciplina de verão SIN492 - Reconhecimento de Padrões.
O projeto consiste em implementar e avaliar os resultados de um modelo de aprendizado de máquina e uma rede neural, utilizando uma base de dados fictícia.

## Arquivos

1. **SIN_492_Modelo_K_NN.ipynb**: Notebook Jupyter contendo o código do projeto. Ele inclui a implementação dos modelos e as visualizações associadas.

2. **database.csv**: Base de dados para treinamento e validação.

## Executando o Notebook

Para executar o notebook e reproduzir os resultados, siga estas etapas:

1. Certifique-se de ter o ambiente [Python](https://www.python.org/downloads/) instalado.
2. Instale as dependências necessárias:

    ```bash
    pip install pandas scikit-learn matplotlib seaborn
    ```
3. *Importante*: Atualizar o endereço do arquivo .CSV no SIN_492_Modelo_K_NN.ipynb.

   ```python
   # Importando o arquivo .csv
    df = pd.read_csv('/content/drive/MyDrive/database')
   ```

4. Abra o notebook [Jupyter](https://jupyter.org/install):

    ```bash
    jupyter notebook SIN_492_Modelo_K_NN.ipynb
    ```
5. Execute as células do notebook sequencialmente para reproduzir os experimentos.
6. Alternativamente, utilize do [Google Colab](https://colab.research.google.com/drive/1rVy1FoXvQ4SFXKURmhgTbU_aw0MdGI65?usp=sharing) para abrir e executar o notebook.

## Participantes

- [Bruno Marques da Silva](https://github.com/BrunoMarques416)
- [Luís Fernando Almeida](https://github.com/luissaster)
- Marcella Clemente Alves

## Agradecimentos

Agradecemos os professores Leandro Henrique Furtado e Larissa Ferreira Rodrigues pelo conhecimento compartilhado conosco, além de todo o suporte durante a etapa de realização do projeto.
