Classificador de Dígitos Manuscritos com PyTorch
================================================

Este é um projeto de classificação de dígitos manuscritos utilizando o conjunto de dados MNIST e implementado com o framework PyTorch.

Descrição
---------

O objetivo deste projeto é desenvolver um modelo de aprendizado de máquina capaz de reconhecer dígitos manuscritos com alta precisão. O conjunto de dados MNIST é um conjunto popular para esse tipo de tarefa, contendo imagens de dígitos manuscritos de 0 a 9.

O projeto consiste em:

1.  **Preparação dos Dados**: Os dados são baixados e preparados utilizando o PyTorch DataLoader para treinamento e validação.
    
2.  **Definição do Modelo**: Uma rede neural é definida utilizando a biblioteca PyTorch. O modelo consiste em camadas lineares e ativações ReLU.
    
3.  **Treinamento do Modelo**: O modelo é treinado utilizando o algoritmo de gradiente descendente estocástico (SGD) com a função de perda NLLLoss.
    
4.  **Validação do Modelo**: Após o treinamento, o modelo é avaliado em um conjunto de dados de validação separado para medir sua precisão.
    

Requisitos
----------

*   Python 3
*   PyTorch
*   torchvision
*   matplotlib

Como Usar
---------

1.  Clone este repositório:

bashCopy code

`git clone https://github.com/seu-usuario/classificador-digitos-manuscritos.git`

2.  Navegue até o diretório do projeto:

bashCopy code

`cd classificador-digitos-manuscritos`

3.  Execute o notebook Jupyter:

bashCopy code

`jupyter notebook classificador_digitos.ipynb`

4.  Siga as instruções no notebook para treinar e testar o modelo.

Contribuições
-------------

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

Licença
-------

Este projeto é licenciado sob a MIT License.
