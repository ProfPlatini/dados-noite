# 📊 dados-noite

Repositório pessoal criado para acompanhar o curso **Fundamentos de IA e Análise de Dados**, com estudos práticos em Python, análise de dados e visão computacional.

> Fork de [ProfPlatini/dados-noite](https://github.com/ProfPlatini/dados-noite), com exercícios e experimentos próprios.

## 🎯 Sobre o repositório

Aqui estão reunidos os notebooks, scripts e bases de dados usados ao longo das aulas — desde a introdução às bibliotecas de análise de dados até um primeiro contato com visão computacional usando YOLO.

> **Observação:** os dados usados alternam entre fictícios e reais, extraídos principalmente do [Kaggle](https://www.kaggle.com/), e sua reprodução é totalmente livre.

## 🗂️ Estrutura do projeto

| Arquivo / Pasta | Descrição |
|---|---|
| `data/` | Bases de dados utilizadas nos notebooks |
| `bibliotecas.ipynb` | Introdução às bibliotecas de análise de dados (Pandas, NumPy, Seaborn) |
| `aula02.ipynb` | Notebook da aula 02 |
| `aula03.ipynb` | Notebook da aula 03 |
| `aula04.ipynb` | Notebook da aula 04 |
| `aula06.ipynb` | Notebook da aula 06 |
| `exercicios.ipynb` | Exercícios gerais do curso |
| `exercicios_aula02.ipynb` | Exercícios específicos da aula 02 |
| `ml.ipynb` | Experimentos com Machine Learning |
| `visao.py` | Script de visão computacional com YOLOv8 (detecção via webcam) |
| `yolov8n.pt` | Pesos pré-treinados do modelo YOLOv8 nano |
| `app.py` | Script principal da aplicação |

## 🛠️ Tecnologias utilizadas

- **Python 3**
- **Pandas** e **NumPy** — manipulação e análise de dados
- **Seaborn** — visualização gráfica
- **Jupyter Notebook** — desenvolvimento interativo
- **Ultralytics YOLOv8** — detecção de objetos em tempo real

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/breno209/dados-noite.git
   cd dados-noite
   ```

2. Instale as bibliotecas necessárias:
   ```bash
   pip install pandas seaborn numpy
   ```

3. Para o script de visão computacional (`visao.py`), instale também:
   ```bash
   pip install ultralytics
   ```

4. Abra os notebooks com Jupyter:
   ```bash
   jupyter notebook
   ```

5. Para rodar a detecção de objetos em tempo real via webcam:
   ```bash
   python visao.py
   ```

## ✅ Boas práticas

Os códigos seguem a proposta de **clean code** e estão adequados ao padrão **PEP 8**.
