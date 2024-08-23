# Comandos Básicos do Linux

Os comandos estão entre áspas duplas(" "):

* "pwd" -> Mostra o diretório atual;

* "clear" -> Limpar a tela;

* "touch" -> Este comando "toca" no arquivo, apenas alterando a data de atualização;

* "cd" -> Mudar de diretório cd significa change directory. Exemplo: \
cd Desktop - vai para o diretório Desktop;\
cd - Vai para o diretório base/raiz;\
cd .. - Retorna um diretório;

* "ls" -> Lista os arquivos e diretórios;\
ls -la - Lista todos os arquivos inclusive os invisíveis, a letra a é de all;
ls * - Lista todos os arquivos de todos os diretórios;

* "-v" -> Vem de verbose, utilizado como complemento do comando para informar o que está sendo realizado;

* "-q" -> Vem de quiet, utilizado para deixar o comando "quieto", sem escrever tudo o que está sendo feito;

* "echo" -> repete uma mensagem no terminal. Exemplo: echo "Bem vindo!", retorna Bem vindo!;

* ">" -> Redirecionar a saída para algum lugar. Exemplo: echo "Bem vindo!" > bemVindo.txt, este comando vai criar um arquivo .txt no seu diretório com um texto escrito "Bem vindo!";

* ">>" ->  O objetivo é o mesmo do comando acima, porem caso o arquivo já tenha algum conteúdo, ele não sobrescreve a informação e sim adiciona o conteúdo ao arquivo;

* "cat" -> O cat é um comando onde busca arquivos. Exxemplo: Se for colocado a informação cat bemVindo.txt, ele vai imprimir no terminal Bem vindo!;

* "ls -l" -> Lista todos os arquivos que tem no seu diretório, a informação vem da seguinte maneira: \
\-rw-r--r-- 1 lucas_oliveira lucas_oliveira 11 Jun  9 17:58 bemVindo.txt \
Esta linha contem informações do grupo, usuário, data de modificação e tamanho do arquivo;

* "man" -> É o comando de ajuda man é de manual. Exemplo: man pwd, ele vai trazer um visualizador com a documentação do comandos com pwd , e aperte Q para sair;

* "mkdir" -> É o comando de criar diretório, mkdir significar make diretory. Exemplo: mkdir workspace, vai criar este diretório;

* "rm" -> É utilizado para apagar arquivo;

* "rmdir" -> É utilizado para apagar diretório vazio;

* "*" -> Podemos utilizar para ler todos os arquivos. Exemplo: \
 cat *.txt - Vai ler todos os arquivos que são .txt;

* "cp" -> Copia arquivo;

* "cp -r" -> Copia diretórios;

* "mv" -> Move arquivo. Exemplo: mover um arquivo para o diretorio Desktop -> mv bemVindo.txt cd/Desktop/bemVindo.txt;

* "zip -r" -> Cria arquivos zip exemplo: \
zip -r documentos.zip documentos/;\
unzip -l documentos.zip - Mostra o que contem no arquivo zip;\
unzip documentos.zip - Descompacta o zip;\

* "head" -> Tras as primeiras linhas de um documento. Exemplo:\
head texto.txt - Para trazer as 10 primeiras linhas do cabeçalho;\
head -n 3 texto.txt - Parar trazer 3 linhas ou quantas linhas quiser apenas alterar o argumento numérico;

* "tail" - Tras as ultimas linhas de um documento. Exemplo:\
tail texto.txt - Puxa as 10 ultimas linhas do documento;\
tail -n 3 texto.txt - Parar trazer 3 ultimas linhas ou quantas linhas quiser apenas alterar o argumento numérico;

* "top" -> Monitorar os processos em execução;

# Guias para linux em português

* https://www.guiafoca.org/#download 