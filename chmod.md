Comando `chmod` - alterar as permissões de acesso a arquivos e diretórios  

## MODO DE PERMISSÕES OCTAL  

__SINTAXE__:  
`chmod` `<permissões>` `<arquivo ou diretório>`  

Apenas Execução = 1  
Apenas Escrita  = 2  
Escrita e Execução = 3  
Apenas Leitura  = 4  
Leitura e Execução = 5  
Leitura e Escrita = 6  
Leitura, Escrita e Execução = 7

`rwx`  
`111` = 7

`--x`  
`001` = 1  

`-w-`  
`010` = 2  

`r--`  
`100` = 4  

`rw-`  
`110` = 6  

## EXEMPLOS

`rwx`   `rw-`   `rw-`  
`111`   `110`   `110`  
`766`  

`$ chmod 766 <arquivo ou diretório>`  

`rw-`   `r--`   `---`  
`110`   `100`   `000`  
`640`  

`$ chmod 640 <arquivo ou diretório>`  

