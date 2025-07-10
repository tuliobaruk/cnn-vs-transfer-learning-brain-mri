# Classificação de Tumores Cerebrais com CNN e Transfer Learning

![Análise Grad-CAM](/Notebook%20GRADCAM/grade_resultados_gradcam.png)

## Sobre

Este repositório contém o código-fonte e os materiais do meu Trabalho de Conclusão de Curso (TCC) em Análise e Desenvolvimento de Sistemas. O projeto investiga e compara duas abordagens de Deep Learning para a classificação de tumores cerebrais em imagens de ressonância magnética (MRI):

1.  **CNN Personalizada:** Uma Rede Neural Convolucional construída do zero.
2.  **Transfer Learning:** A adaptação do renomado modelo **ResNet18**, pré-treinado na base de dados ImageNet.

O objetivo foi determinar qual estratégia apresenta o melhor desempenho para classificar quatro categorias: **Glioma, Meningioma, Pituitária e Ausência de Tumor**. O modelo de Transfer Learning com ResNet18 demonstrou superioridade, alcançando **99% de acurácia** em validação.

## Estrutura

-   **/Notebooks de Treinamento:** Contém as pipelines completas em formato de Jupyter Notebook para o treinamento de ambos os modelos.
-   **/Notebook GRADCAM:** Contém o notebook para gerar visualizações com Grad-CAM, permitindo analisar a interpretabilidade do modelo ResNet18.
-   **/Modelos Treinados:** Armazena os pesos (`.pth`) dos modelos com melhor desempenho salvos durante o treinamento.
-   **/imagens:** Contém imagens de exemplo e os gráficos gerados pelo projeto.

## Requisitos

-   **Linguagem:** Python 3
-   **Bibliotecas Principais (Para ver todas consultar requirements que utilizei em meu venv):** PyTorch, Torchvision, Scikit-learn, Pandas e  Matplotlib
-   **Dataset:** [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

## Artigo
Para uma análise detalhada da metodologia, resultados e conclusões, consulte o artigo completo do TCC.

---
*Desenvolvido por Túlio Baruk Melo Silva como requisito para a conclusão do curso de Tecnólogo em Análise e Desenvolvimento de Sistemas no IFPE, campus Jaboatão dos Guararapes.*