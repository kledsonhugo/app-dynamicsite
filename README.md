# app-dynamicsite

## Descrição
Este projeto é uma aplicação PHP simples que exibe informações detalhadas sobre o ambiente do servidor, como hostname, IP, sistema operacional, versão do PHP, software do servidor web, tempo de resposta, User-Agent, cabeçalhos da requisição e variáveis de ambiente.

## Funcionalidades
- Exibe dados do servidor (hostname, IP, OS, versão do PHP, software do servidor web, tempo de resposta)
- Mostra o User-Agent do cliente
- Lista todos os cabeçalhos da requisição
- Exibe todas as variáveis de ambiente disponíveis

## Como executar
1. Certifique-se de ter o PHP instalado em sua máquina ou servidor.
2. Faça o deploy dos arquivos em um servidor web compatível (Apache, Nginx, etc).
3. Acesse o arquivo `phpinfo.php` pelo navegador para visualizar as informações.

## Estrutura
- `phpinfo.php`: Página principal que exibe as informações do ambiente.
- `LICENSE`: Licença do projeto.
- `README.md`: Este arquivo de documentação.

## Exemplo de uso
Acesse `http://localhost/phpinfo.php` (ou o endereço configurado no seu servidor) para visualizar as informações detalhadas do ambiente.

## Requisitos
- PHP 7.0 ou superior
- Servidor web (Apache, Nginx, etc)

## Licença
Consulte o arquivo LICENSE para mais detalhes.