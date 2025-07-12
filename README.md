# 🐋🦋🐶 Comparação de Técnicas de Visão Computacional na Classificação de Animais

Este repositório ao trabalho desenvolvido como projeto final da disciplina de *Visão Computacional* do curso de Engenharia da Computação (CEFET-MG). O estudo teve como propósito aplicar técnicas de redes neurais convolucionais e algoritmos de aprendizado supervisionado para classificar imagens de animais, comparando o desempenho entre a arquitetura *MobileNetV2* e o modelo *Random Forest*.

## ⚙️ Funcionalidades do sistema

- Utilização da base de dados com imagens de três espécies animais: *baleia, **borboleta* e *cachorro*.
- Aplicação de técnicas de *pré-processamento* e *aumento de dados* (data augmentation) para aumentar a capacidade generalização dos modelos.
- Treinamento de um modelo baseado em *Random Forest* com extração de características.
- Treinamento de uma *CNN MobileNetV2* com pesos pré-treinados via Transfer Learning.
- Avaliação dos modelos com uso das métricas: *acurácia, **precisão, **revocação (recall), **F1-score, **matriz de confusão* e *curva ROC*.
- Comparação dos resultados obtidos para análise de desempenho entre as abordagens.


## 📁 Estrutura do Repositório

bash
animal-classification/
├── animais/                        # Conjuntos de imagens originais por espécie
│   ├── ButterflyDataset/
│   ├── DogDataset/
│   └── WhalesDataset/
├── dataset_aumentado/             # Imagens com data augmentation
│   ├── teste/
│   ├── treino/
│   └── validacao/
├── dataset_organizado/            # Dataset organizado sem aumento de dados
│   ├── teste/
│   ├── treino/
│   └── validacao/
├── environment.yml                # Arquivo para criação de ambiente Conda
├── main.ipynb                     # Notebook principal com execução geral do projeto
├── random_forest_melhor_modelo.joblib  # Modelo Random Forest salvo (melhor versão)
└── README.md                      


## 🛠️ Tecnologias e Ferramentas

### 🧰 Tecnologias utilizadas

- *Python 3.10+* — Linguagem principal do projeto.
- *Jupyter Notebook* — Ambiente interativo utilizado para desenvolvimento e apresentação dos experimentos.
- **[TensorFlow](https://www.tensorflow.org/)** e **[Keras](https://keras.io/)** — Frameworks usados para construção e treinamento da CNN MobileNetV2.
- **[OpenCV](https://opencv.org/)** — Utilizado para manipulação e processamento das imagens.
- **[scikit-learn](https://scikit-learn.org/)** — Ferramenta para treinamento do modelo Random Forest, extração de métricas e validação cruzada.
- *NumPy / Matplotlib* — Bibliotecas para manipulação de dados numéricos e visualização gráfica.

### 🚀 Como usar

1. *Clone este repositório*:
   ```bash
   git clone https://github.com/seu-usuario/animal-classification.git
   cd animal-classification

## 🎓 Informações Acadêmicas

- **Disciplina**: Visão Computacional  
- **Instituição**: CEFET-MG  
- **Alunos**:
  - Anna Laura Moura Santana
  - Jullia Fernandes Felizardo

## 👩‍💻 Autoras

> *Anna Laura Moura*  
> [nalauramoura@gmail.com](mailto:nalauramoura@gmail.com)

> *Jullia Fernandes Felizardo*  
> [julliacefet@gmail.com](mailto:julliacefet@gmail.com)


## 📝 Licença

Este projeto foi desenvolvido exclusivamente para fins acadêmicos e educacionais.

