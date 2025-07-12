# 🐋🦋🐶 Classificador Multiclasse de Animais com MobileNetV2 e Random Forest

Este repositório contém o projeto desenvolvido como trabalho final da disciplina de *Visão Computacional* do curso de Engenharia da Computação (CEFET-MG).

O objetivo principal foi aplicar e comparar duas abordagens de aprendizado supervisionado para classificação de imagens de três espécies animais: **baleia**, **borboleta** e **cachorro**.

## ⚙️ Funcionalidades

- Organização de dataset multiclasse com imagens das três espécies.
- Aplicação de técnicas de **pré-processamento** e **data augmentation**.
- Treinamento de modelo **Random Forest** com extração de características visuais.
- Treinamento de **MobileNetV2** via *Transfer Learning* (Keras).
- Avaliação e comparação dos modelos utilizando:
  - Acurácia
  - Precisão
  - Revocação (Recall)
  - F1-Score
  - Matriz de confusão
  - Curva ROC

---

## 📁 Estrutura do Projeto
```

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

```

---

## 🧪 Tecnologias Utilizadas

- **Python 3.10+**
- **Jupyter Notebook**
- **TensorFlow / Keras** – MobileNetV2
- **scikit-learn** – Random Forest, métricas, validação
- **OpenCV** – Processamento de imagens
- **Matplotlib / Seaborn / NumPy** – Visualização e manipulação de dados

---

## 🚀 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/JulliaFernandes/Classificador_multiclasse_animais.git
cd Classificador_multiclasse_animais
```

2. Crie o ambiente Conda:

```bash
conda env create -f environment.yml
conda activate classificador-animais
```

3. Execute os notebooks:

- `RandomForest_model.ipynb`
- `MobileNetV2_model.ipynb`

---

## 📊 Resultados

O projeto compara as abordagens em termos de desempenho de classificação, utilizando métricas padrão. A MobileNetV2, por ser baseada em redes neurais profundas com Transfer Learning, apresentou melhor desempenho na maioria dos testes.

---

## 👩‍💻 Autoras

- **Anna Laura Moura Santana** — [nalauramoura@gmail.com](mailto:nalauramoura@gmail.com)  
- **Jullia Fernandes Felizardo** — [julliacefet@gmail.com](mailto:julliacefet@gmail.com)

---

## 🎓 Informações Acadêmicas

- **Disciplina**: Visão Computacional  
- **Instituição**: CEFET-MG  
- **Professor**: Thabatta Araújo 
- **Ano/Semestre**: 2024/1

---

## 📄 Licença

Projeto desenvolvido exclusivamente para fins acadêmicos e educacionais.
