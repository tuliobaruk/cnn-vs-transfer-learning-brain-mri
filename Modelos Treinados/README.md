# Modelos Treinados

Neste diretório estão armazenados os pesos dos modelos que alcançaram o melhor desempenho durante a fase de validação. Os arquivos estão no formato `.pth` do PyTorch.

-   **`best_CNN_de_tumores_cerebrais.pth`**: Pesos do melhor modelo da CNN Personalizada.
-   **`best_ResNet18_FineTuned.pth`**: Pesos do melhor modelo ResNet18 após a fase de ajuste fino (*fine-tuning*).

Esses arquivos podem ser carregados em suas respectivas arquiteturas de modelo para realizar inferência ou continuar o treinamento.