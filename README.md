# Gerador de Recibos - RD PRAG DETETIZAÇÃO

## Descrição
Este é um programa desenvolvido para facilitar a geração de recibos automatizados para a empresa **RD PRAG DETETIZAÇÃO**. Ele permite que o usuário insira informações do cliente, selecione a data e gere um recibo em formato **PDF** ou **DOCX**, pronto para ser impresso e entregue ao cliente. Além disso, o programa salva um histórico dos clientes em um arquivo **JSON**.

## Funcionalidades
- Interface gráfica intuitiva desenvolvida com **Tkinter**.
- Seleção de data utilizando **tkcalendar**.
- Geração automática de recibos em **PDF** e **DOCX**.
- Conversão do valor para extenso (exemplo: "150" vira "Cento e cinquenta reais").
- Armazena os dados dos clientes em um arquivo **JSON**.

## Tecnologias Utilizadas
- **Python 3**
- **Tkinter** (Interface gráfica)
- **tkcalendar** (Seleção de datas)
- **ReportLab** (Geração de PDFs)
- **python-docx** (Geração de arquivos Word)
- **num2words** (Conversão de números para palavras)
- **JSON** (Armazenamento de dados de clientes)

## Como Usar
### 1. Instalação das Dependências
Antes de executar o programa, certifique-se de instalar as bibliotecas necessárias. Utilize o seguinte comando:
```sh
pip install tkinter tkcalendar reportlab python-docx num2words
```

### 2. Executar o Programa
Para rodar o programa, basta executar o arquivo Python:
```sh
python nome_do_arquivo.py
```

### 3. Preenchimento dos Campos
1. Insira as informações do cliente:
   - Nome
   - CPF
   - Contato
   - Data do serviço (com opção de seleção no calendário)
   - Horário
   - Valor do serviço
2. Clique em **"Gerar Recibo"**.
3. Escolha o local para salvar o arquivo em **PDF** ou **DOCX**.
4. O recibo será salvo e estará pronto para impressão.

## Exemplo de Recibo Gerado
O recibo gerado possui:
- Logo da empresa (previamente definida no código)
- Nome e CPF do cliente
- Contato
- Data e horário do serviço
- Valor do serviço, tanto em números quanto por extenso
- Espaço para assinatura
- Mensagem de agradecimento ao cliente

## Exemplo com imagem:
![image](https://github.com/user-attachments/assets/b563b765-d1a3-4cf7-9781-e0fc2192e841)


## Personalização
Se desejar personalizar:
- **Logo da empresa**: Substitua a imagem no caminho `C:/Users/gabri/Downloads/oip.jpeg`.
- **CNPJ da empresa**: Edite a linha correspondente no código.
- **Layout do recibo**: Modifique os métodos `salvar_pdf` e `salvar_docx`.

## Desenvolvedor
Criado por **Gabriel Santana**
- [LinkedIn](https://www.linkedin.com/in/gabrielsbelarmino/)
- [GitHub](https://github.com/GabrielFSantana/)

