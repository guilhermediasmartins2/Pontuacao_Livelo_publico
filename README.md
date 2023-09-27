# Pontuacao_Livelo_publico

O código foi criado para poder manter informado quando surgir uma promoção de pontuações da empresa parceiro que você tem interesse.

Quando isso acontecer, uma mensagem é enviada pelo Telegram informando qual é a empresa e a respectiva pontuação.

# Módulos utilizados

Time

Requests

Selenium

Recaptcha Solver

ChromeDriverManager


# Modo de utilização

O programa abre uma janela no Google Chrome onde será controlado pelo código. Com isso, ele acessa o site da Livelo e insere os dados para login.

Caso apareça um recaptcha para logar, o módulo Recaptcha Solver é ativado para realizar a quebra. Após isso ele procura a lista de todos os parceiros presentes na Livelo e busca todas as empresas de seu interesse presente em uma lista no script.

Caso encontre um empresa que esteja com a pontuação maior do que o número que você deseja, é enviado uma mensagem pelo Telegram com o nome dessa empresa e a pontuação.
 


https://github.com/guilhermediasmartins2/Pontuacao_Livelo_publico/assets/125048539/bb911fd3-ea80-4d63-8ed8-1be65867e4a9

