# Projeto da escola Maria Helena Faria Lima e Cunha
Automação em python desenvolvida como projeto final para a
escola Maria Helena Faria Lima e Cunha onde cursei programação
para internet, 2° e 3.º Ano tec(habilitação profissional Novotec). 

# Tutorial de execução do código 

- Primeiro passo
  - Acessar o site replit.com
  - Fazer o login na plataforma;
  - Criar um template python
 
- Segundo passo
  - Instalar os módulos pandas e openpyxl usando shell do ambiente;
  - <code>pip install pandas</code>
  - <code>pip install openpyxl</code>

- Terceiro passo
  - Copiar código do arquivo [main.py](main.py) que está neste repositório para main.py do ambiente Repl.it.

- Quarto passo
  - Editar valor variável email_user da linha 23 com seu e-mail do gmail;
  - Editar valor da variável email_pass da linha 24 com a senha que será gerada na verificação de duas etapas do gmail;
  - Para obter a senha da verificação de duas etapas: acesse as configurações da sua conta Google>segurança>como você acessa o seu e-mail>Verificação em duas etapas>Ativar verificação>Senhas de App>Outros>Nomear>gerar;
  - Copiar senha gerada para linha 24;
  - Editar, na linha 75, o valor da variável receiver_email. Atualizar com o e-mail do destinatário.
 
- Quinto passo
  - No Repl.it vá em Filés>Upload file e faça o upload de tabela [Vendas.xlsx](Vendas.xlsx) que se encontra nesse repositório.
 
- Sexto passo
  - No shell do ambiente Repl.it executar o comando <code>python main.py</code>

# Considerações finais 
O objetivo deste código e a manipulação dos dados da tabela Vendas.xlsx, Impressão desses dados manipulados no shell e envio deles por e-mail para algum destinatário. A automação envia um e-mail formatado por meio de tags html com as informações manipuladas. 
