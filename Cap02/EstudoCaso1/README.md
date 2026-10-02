# Estudo de Caso 1 — DSA AI Coder: Criando Seu Assistente de Programação Python em Python

 Abra o terminal ou prompt de comando, navegue até a pasta com os arquivos e execute o comando abaixo para criar um ambiente virtual.

 ## Criar o ambiente virtual nativo do Python

```
py -3.13 -m venv venv
```

 > **Observação:** o segundo `venv` é o nome do ambiente virtual onde serão instaladas as bibliotecas e versões que você definiu. Nos comandos abaixo, esse será o nome utilizado.
>
>  Caso não queira especificar a versão do Python, também pode utilizar:
>
>
> ```
> python -m venv venv
> ```

 ## Ativar o ambiente virtual

 ### Windows

```
.\venv\Scripts\activate
```

 ### Linux / macOS

```
source venv/bin/activate
```

 ## Instalar as dependências

 Instale as dependências isoladamente utilizando o arquivo `requirements.txt`:

```
pip install -r requirements.txt
```

 ## Executar a aplicação

```
streamlit run dsa_assistente.py
```

 ## Exemplos de uso do assistente

 Você pode fazer perguntas como:

```
Como crio um hello world em Python?

Qual a sintaxe de um loop em Python?

Como eu uso a função map em Python? Me dê um exemplo com lambda.
```

 ## Desativar e remover o ambiente virtual

 Quando terminar de utilizar o ambiente virtual, você pode desativá-lo com:

```
deactivate
```

 Para remover o ambiente virtual no Windows:

```
rmdir /s /q venv
```