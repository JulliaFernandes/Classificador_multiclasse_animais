# Classificação de Animais com Data Augmentation e Random Forest 🐾🌲

Este repositório contém o código e os experimentos realizados para o seminário da disciplina de **Visão Computacional**, com o tema:  
**“Uso de Data Augmentation e Random Forest na Classificação de Animais”**.

## 📚 Objetivo do Projeto

O principal objetivo foi aplicar técnicas de **aumento de dados (data augmentation)** em um conjunto de imagens de animais e utilizar o algoritmo de **Random Forest** para realizar a **classificação automática** dessas imagens.

## 🧠 Tecnologias e Bibliotecas Utilizadas

- Python 3.x  
- OpenCV (`cv2`)
- NumPy
- scikit-learn (`sklearn`)
- Matplotlib (para visualização)
- OS, Glob (para manipulação de arquivos e diretórios)

## 🔬 Metodologia

1. **Coleta de Dados**  
   Imagens de diferentes classes de animais (cães, baleias, aguias).

2. **Pré-processamento e Aumento de Dados**  
   Aplicação de técnicas como:
   - Rotação
   - Espelhamento (flip horizontal/vertical)
   - Redimensionamento
   - Ruído e ajustes de brilho

3. **Treinamento do Modelo**  
   Uso do algoritmo de **Random Forest** da biblioteca `sklearn` para treinar o classificador.

4. **Avaliação**  
   Testes com dados não vistos e avaliação da acurácia do modelo.

## 📁 Estrutura do Repositório

```
Classificacao_De_Animais/
├── animais/                 # Imagens divididas por classes
│   ├── aguia/               # Imagens originais
│   └── baleia/              # Imagens originais
│   └── cachorro/            # Imagens originais
│   └── treino/              # Imagens originais de treino
│   └── validacao/           # Imagens originais de validação
├── aumentadas/              # Imagens de treino pos aplicação do Data Aumentation
│   ├── treino/              # Imagens de treino aumentadas
├── imgsAmigos/              # Imagem reais de animais para testar o modelo.
├── environment.yml          # Bibliotecas necessárias
├── main.ipynb               # Scripts Python (pré-processamento, treino, avaliação)
└── melhor_modelo.h5         # Melhor modelo obtido
```

## 📊 Resultados

- O uso de **Data Augmentation** contribuiu para o aumento da base de dados e melhor generalização do modelo.
- A **Random Forest** apresentou bom desempenho na classificação, com precisão satisfatória mesmo com um número limitado de dados originais.

## 🎓 Informações Acadêmicas

- **Disciplina**: Visão Computacional  
- **Instituição**: CEFET-MG  
- **Alunos**:
  - Anna Laura Moura Santana
  - Jullia Fernandes Felizardo

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/JulliaFernandes/Classificacao_De_Animais.git
   cd Classificacao_De_Animais
   ```

2. Crie o ambiente Conda a partir do arquivo `environment.yml`:
   ```bash
   conda env create -f environment.yml
   ```

3. Ative o ambiente:
   ```bash
   conda activate classificacao_animais
   ```

4. Execute os scripts ou abra os notebooks na pasta `/notebooks`.

## 📝 Licença

Este projeto foi desenvolvido exclusivamente para fins acadêmicos e educacionais.
