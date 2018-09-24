# help

## git
Fazer pull todos os projetos git dentro de um diretório windows
`for /D %G in (<diretorio>\*") do (echo %G) && (cd %G) && (git pull origin) && (cd ..)`
