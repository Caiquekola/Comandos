## Windows CMD / Unix 

### - cd:   
* Significa change directory. Serve para navegar entre as pastas.

### - dir  
* Diretórios, serve para listar os diretórios em uma pasta.
### - ls (Unix)
* Significa directories, serve para listar os diretórios em uma pasta.

### - mkdir  
* Criar pasta

### - del/ rmdir (Windows)
* del, deleta somento o que tem dentro da pasta.   
* "rmdir /S /Q" deletará tudo e a pasta.
### - rm (Unix)
* Deletar pasta e conteúdo. "rm -rf"
### - Echo
* Exibe uma mensagem. Com o símbolo de > (maior que), ele cria um arquivo. Exemplo Echo > Hello.txt  

## Novo Repositório

Passos para criar um repositório no GitBash


echo "# Comandos" >> README.md  
git init  
git add README.md  
git commit -m "first commit"  
git branch -M main  
git remote add origin https://github.com/Caiquekola/NomeDoArquivo.git  
git push -u origin main


Clonar

git Clone https://...