# Capacitação em Machine Learning e Inteligência Artificial

Bem-vindo(a) à Capacitação em Machine Learning e Inteligência Artificial da Insper Dynamics. Este é o repositório de documentação do curso. Aqui você encontra os materiais disponíveis, as instruções de instalação, exercícios e recomendações de bibliografia.

## Reuniões

- Quartas-feiras, às 18:15. Duração estimada de 30 minutos a 1 hora, via Discord.

## Assuntos

| Data       | Assunto               | Link                       |
|------------|-----------------------|----------------------------|
| 2023-09-13 | Reunião Inicial, Python e Pandas     | [Link](https://thomaschiari.github.io/ML_AI-Training/modulo0/)       |
| 2023-09-20 | Pré-Processamento e Análise Exploratória | [Link](https://thomaschiari.github.io/ML_AI-Training/modulo1/)    |

## Utilização

1. Tenha o `git` instalado em sua máquina. Para verificar se você já o possui, digite no terminal:
```bash
git --version
```
Caso não possua, siga as instruções de instalação no site oficial: [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

2. Clone o repositório em sua máquina utilizando o comando:
```bash
git clone https://github.com/thomaschiari/ML_AI-Training.git
```

3. Para atualizar o repositório local com as modificações feitas no repositório remoto, utilize o comando:
```bash
git pull
```

4. Para iniciar o o projeto, será necessário utilizar um ambiente para gerenciar as dependências. Aqui, podemos utilizar tanto `venv` quanto `conda`.

### Utilizando `venv`:

1. Caso não tenha o `virtualenv` instalado, siga as instruções de instalação no site oficial: [Virtualenv](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/).

2. Rode o comando:
```bash
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
```bash
pip install -r requirements.txt
```

5. Para desativar o ambiente virtual, utilize o comando:
```bash
deactivate
```

### Utilizando `conda`:

1. Caso não tenha o `conda` instalado, siga as instruções de instalação no site oficial: [Conda](https://docs.conda.io/projects/miniconda/en/latest/).

2. Rode o comando:
```bash
conda env create -f environment.yml
```

3. Ative o ambiente virtual:
```bash
conda activate ml_ai-training
```

4. Para desativar o ambiente virtual, utilize o comando:
```bash
conda deactivate
```

Com todos os passos cumpridos, você pode utilizar a IDE do Jupyter Notebook rodando localmente em seu browser rodando o comando:
```bash
jupyter notebook
```
Ou pode simplesmente utilizar a IDE de sua preferência para abrir os Notebooks.
