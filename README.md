# EBA- Aula 05: Para Casa Desafio do IFOOD (continuação)


Chegou a hora de treinarmos os conceitos ensinados em aula!

Na pasta `data` você vai encontrar os dados em arquivo `csv`e `xlsx`. Na pasta `notebooks` você vai ter o gabarito proposto para a solução do exercício. Recomendamos que você tente fazer sozinho antes de olhar o gabarito. Isto vai fazer com que suas habilidades analíticas sejam desenvolvidas muito mais rapidamente.

## INSTRUÇÕES PARA RESOLUÇÃO DO CASE:


O conjunto de dados é composto por clientes da empresa Ifood com dados sobre:

Perfis de clientes
Preferências do produto
Sucessos/fracassos da campanha
Desempenho do canal

Algumas colunas do dataset:

![Dicionário de Colunas](https://github.com/EbaPed/EBA-aula05-ParaCasa/tree/main/image)



Suponha que estamos tentando atrair mais clientes. Na nossa análise de dados anterior, vimos que pessoas sem filhos gastam mais do que pessoas com mais filhos. 

Nossa equipe de marketing pensou em fazer campanhas direcionadas ao grupo de pessoas com filho (independente da quantidade), porém precisamos comprovar se de fato as médias de gastos dos grupos é diferente. 

Portanto:
- Agrupe todas as pessoas que tem filhos em um grupo chamado "com filhos" e faça uma comparação da média de gastos de pessoas sem filhos e pessoas com filhos.
- Posteriormente, compare os grupos de pessoas com filhos. O time de marketing nos pediu para verificar se há diferenças de gastos (expenses) em quem tem 1, 2, 3 ou mais filhos para que eles possam afunilar mais ainda a campanha. 
- A média desses grupos é diferente? Qual(is) tem menor média?


---


## INSTRUÇÕES PARA O USO DESTE REPOSITÓRIO:

### **Como utilizar este repositório?**

Este repositório contém os arquivos e códigos necessários para a aula de Estatística Descritiva. Abaixo estão as instruções simplificadas para configurar o ambiente com Pyenv e Poetry.

- **Passo a Passo para Configuração do Ambiente:**

1. **Clonar o Repositório:**

No terminal, clone este repositório:

```bash
git clone https://github.com/EbaPed/EBA-aula05-ParaCasa.git
cd EBA_aula01_EstatisticaDescritiva
```

2. **Configurar a versão do Python com Pyenv**

Defina a versão do Python para o projeto. Para esta aula, vamos usar o Python 3.10.11 (ou outra versão compatível):

```bash
pyenv local 3.10.11
```

3. **Ativar o Ambiente Virtual Poetry**

Agora, ative o ambiente virtual:

```bash
poetry shell
```

4. **Instale as dependências do projeto usando Poetry:**

```bash
poetry install
```

Isso criará automaticamente um ambiente virtual isolado.


5. **Configurar o Kernel do Jupyter Notebook**

Se você for usar Jupyter Notebook, instale o ipykernel:

```bash
poetry add ipykernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)
```

No Jupyter Notebook, escolha o kernel "Python (venv)" ao iniciar ou criar um novo notebook.


6. **Desativar o Ambiente Virtual**

Para sair do ambiente virtual, basta usar:

```bash
exit
```

7. **Executar o Código**

Agora que o ambiente está configurado, você pode executar os códigos Python fornecidos no repositório.

### **Comandos úteis**

- Ativar o ambiente virtual Poetry:

```bash
poetry shell
```

- Rodar um script com Poetry:

```bash
poetry run python script.py
```

- Adicionar bibliotecas:

 ```bash
poetry add nome_da_biblioteca
```

- Remover Bibliotecas:

 ```bash
poetry remove nome_da_biblioteca
```

