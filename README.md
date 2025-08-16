# 📑 Automação de Emissão de Notas com Selenium e Excel
Este projeto é um robô de automação em Python que lê dados de clientes e produtos de uma planilha Excel e os insere automaticamente em um formulário web utilizando Selenium.

🚀 Tecnologias utilizadas
Python 3

Pandas (leitura e manipulação de Excel)

Openpyxl (engine para Excel)

Selenium (automação de navegador)

Webdriver Manager (gerenciamento automático do ChromeDriver)

🎮 Funcionalidades
✔ Leitura de dados estruturados em planilhas Excel (NotasEmitir.xlsx).
✔ Automação de login em página HTML simulada (login.html).
✔ Preenchimento automático de formulário com:

Nome do cliente

CPF/CNPJ

Endereço, bairro, município, CEP e UF

Descrição do produto

Quantidade, valor unitário e valor total
✔ Submissão do formulário e limpeza dos campos para o próximo registro.

🏗 Estrutura do código
Leitura dos dados: a planilha Excel é carregada com Pandas.

Login automático: o Selenium acessa a página login.html, insere usuário e senha e faz login.

Loop de preenchimento: para cada linha da planilha, o robô insere os dados nos campos HTML.

Envio do formulário: clica no botão para registrar a nota e limpa os campos.

📊 Exemplo de uso
O usuário mantém um Excel com dados de clientes e notas fiscais.

O script lê esses dados automaticamente.

O Selenium abre o navegador, preenche o formulário e envia as informações sem interação manual.

💡 Aprendizados
Como integrar Python + Excel + Web em um fluxo automatizado.

Uso prático do Selenium para automação de formulários.

Manipulação de grandes volumes de dados com Pandas.

Criação de robôs que reduzem erros humanos em tarefas repetitivas.
