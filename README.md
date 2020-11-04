## Descrição
Avisar sabesp e prefeitura que faltou agua. 
O sistema permite que o usuario avise a sabesp, dando local e hora
o Sistema abre ordem de serviço e avisa prefeitura para acompanhamento
O funcionário efetua o serviço e avisa o sistema
Sistema avisa usuário que serviço foi efetuado.
Sistema avisa prefeitura que serviço foi efetuado. 
Prefeitura pergunta se usuario esta satisfeito.

## To Do

Acrtar todas as media  querys

## Links úteis

- <a href="https://laravel.com/docs/7.x">Documentação Laravel (versão 7)</a>
- <a href="https://getcomposer.org/">Composer</a>
- <a href="https://www.apachefriends.org/pt_br/index.html">XAMPP (Apache e MySQL)</a>
- <a href="https://git-scm.com/">GIT e GIT BASH</a>


## ANTES DE USAR
- copiar o arquivo 'env.example' e colar no mesmo local com o nome '.env' e configurar o mesmo com as informações do seu banco de dados.

## EXECUTAR OS COMANDOS ABAIXO:
- composer install
- php artisan key:generate

## COMANDO PARA EXECUTAR AS MIGRATIONS (CRIAR AS TABELAS NO BANCO DE DADOS)
- php artisan migrate

## COMANDO PARA INICIAR O PROJETO EM LOCALHOST:8000
- php artisan serve
