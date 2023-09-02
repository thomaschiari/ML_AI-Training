# Capacitação em Machine Learning e Inteligência Artificial
Treinamento para novos membros da Capacitação do Insper Dynamics

## Diretores:
- Guilherme Fontana
- Thomas Chiari Ciocchetti de Souza

## Colaboradores:
- João Alfredo Cardoso Lamy

## Tópicos abordados:

### Parte I: Básicos
- Intensivo de Python
- Intensivo de Pandas
- Intensivo de Git e Github

### Parte II: Machine Learning
- Introdução
  - Análise Exploratória
  - Pré-processamento
  - Modelos Lineares
  - Modelos de Árvore e Random Forests
  - Trabalhando com outros modelos
- Aprendizado Avançado
  - Redes Neurais Artificiais e Convolucionais
- Aprofundando
  - Feature Engineering
  - Melhorando os Modelos
  - Competições de Machine Learning

### Parte III: Inteligência Artificial
- Introdução
  - Agentes Autônomos
  - Algoritmos de Busca
- Avançando
  - Algoritmos Competitivos
  - Min-Max e Funções de Utilidade
- Aprendizado por Reforço
  - Q-Learning
  - Upper Confidence Bound
  - Thompson Sampling
  - Deep Reinforcement Learning

---

## Como utilizar o repositório:

1. Tenha o `git` instalado em sua máquina. Para verificar se você já o possui, digite no terminal:
```
git --version
```
Caso não possua, siga as instruções de instalação no site oficial: [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

2. Clone o repositório em sua máquina utilizando o comando:
```
git clone https://github.com/thomaschiari/ML_AI-Training.git
```

3. Para atualizar o repositório local com as modificações feitas no repositório remoto, utilize o comando:
```
git pull
```

4. Para iniciar o o projeto, será necessário utilizar um ambiente para gerenciar as dependências. Aqui, podemos utilizar tanto `venv` quanto `conda`.

### Utilizando `venv`:

1. Caso não tenha o `virtualenv` instalado, siga as instruções de instalação no site oficial: [Virtualenv](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/).

2. Rode o comando:
```
python3 -m venv env
```

3. Ative o ambiente virtual:
    - Windows:
    ```
    .\env\Scripts\activate.bat
    ```
    - Linux/MacOS:
    ```
    source env/bin/activate
    ```

4. Instale as dependências:
```
pip install -r requirements.txt
```

5. Para desativar o ambiente virtual, utilize o comando:
```
deactivate
```

### Utilizando `conda`:

1. Caso não tenha o `conda` instalado, siga as instruções de instalação no site oficial: [Conda](https://docs.conda.io/projects/miniconda/en/latest/).

2. Rode o comando:
```
conda env create -f environment.yml
```

3. Ative o ambiente virtual:
```
conda activate ml_ai-training
```

4. Para desativar o ambiente virtual, utilize o comando:
```
conda deactivate
```