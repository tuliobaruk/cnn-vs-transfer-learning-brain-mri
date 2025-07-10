# Notebook de Visualização com Grad-CAM

Este diretório contém o Jupyter Notebook utilizado para gerar os mapas de ativação (heatmaps) com a técnica **Grad-CAM** (*Gradient-weighted Class Activation Mapping*). O objetivo é visualizar quais regiões de uma imagem de MRI foram mais importantes para a decisão de classificação do modelo ResNet18.

## Requisito Importante

Para executar o notebook `gradcam.ipynb` corretamente, é necessário ter o modelo ResNet18 já treinado. O notebook espera encontrar o arquivo de pesos no mesmo diretório.

**Você tem duas opções:**

1.  **Copiar o Modelo:** Copie o arquivo `best_ResNet18_FineTuned.pth` da pasta `/Modelos Treinados` para dentro deste diretório (`/Notebook GRADCAM`).

    **OU**

2.  **Alterar o Caminho no Notebook:** Abra o notebook e modifique a variável `MODEL_PATH` para apontar para o local correto do arquivo do modelo. Por exemplo:
    ```python
    MODEL_PATH = "../Modelos Treinados/best_ResNet18_FineTuned.pth"
    ```