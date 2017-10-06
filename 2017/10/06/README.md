# Atividades de 6 de outubro de 2017

* [Criação de usuários](#usuarios)
* [Configuração do acesso gráfico remoto](#remoto)

## Criação de usuários
```
jurandy@amazonas:~$ sudo adduser nome-sobrenome
Adicionando o usuário `nome-sobrenome' ...
Adicionando novo grupo 'nome-sobrenome' (1003) ...
Adicionando novo usuário `nome-sobrenome' (1003) ao grupo `nome-sobrenome' ...
Criando diretório pessoal `/home/nome-sobrenome' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para nome-sobrenome
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: Nome Completo
	Número da Sala []: 
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
A informação está correta? [S/n] 
jurandy@amazonas:~$ 
jurandy@amazonas:~$ sudo adduser jurandy-soares
Adicionando o usuário `jurandy-soares' ...
Adicionando novo grupo 'jurandy-soares' (1004) ...
Adicionando novo usuário `jurandy-soares' (1004) ao grupo `jurandy-soares' ...
Criando diretório pessoal `/home/jurandy-soares' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para jurandy-soares
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: Jurandy Martins Soares Júnior
	Número da Sala []: 
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
chfn: nome com caracteres não-ASCII: 'Jurandy Martins Soares Júnior'
A informação está correta? [S/n] 
jurandy@amazonas:~$ id jurandy-soares
uid=1004(jurandy-soares) gid=1004(jurandy-soares) grupos=1004(jurandy-soares)
jurandy@amazonas:~$ 
jurandy@amazonas:~$ sudo adduser jose-carlos
Adicionando o usuário `jose-carlos' ...
Adicionando novo grupo 'jose-carlos' (1005) ...
Adicionando novo usuário `jose-carlos' (1005) ao grupo `jose-carlos' ...
Criando diretório pessoal `/home/jose-carlos' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
Sorry, passwords do not match
passwd : Erro de manipulação de token de autenticação
passwd: senha inalterada
Tentar novamente? [s/N] s
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para jose-carlos
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: José Carlos de Brito Albino do Nascimento
	Número da Sala []: 6b
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
chfn: nome com caracteres não-ASCII: 'José Carlos de Brito Albino do Nascimento'
A informação está correta? [S/n] 
jurandy@amazonas:~$ id jose-carlos 
uid=1005(jose-carlos) gid=1005(jose-carlos) grupos=1005(jose-carlos)
jurandy@amazonas:~$ 
jurandy@amazonas:~$ sudo adduser
adduser: Somente um ou dois nomes permitidos.
jurandy@amazonas:~$ sudo adduser fernanda-aureliano
Adicionando o usuário `fernanda-aureliano' ...
Adicionando novo grupo 'fernanda-aureliano' (1006) ...
Adicionando novo usuário `fernanda-aureliano' (1006) ao grupo `fernanda-aureliano' ...
Criando diretório pessoal `/home/fernanda-aureliano' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para fernanda-aureliano
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: Fernanda dos Santos Aureliano
	Número da Sala []: 8a
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
A informação está correta? [S/n] 
jurandy@amazonas:~$ id fernanda-aureliano
uid=1006(fernanda-aureliano) gid=1006(fernanda-aureliano) grupos=1006(fernanda-aureliano)
jurandy@amazonas:~$ 
jurandy@amazonas:~$ sudo adduser judson-silva
Adicionando o usuário `judson-silva' ...
Adicionando novo grupo 'judson-silva' (1007) ...
Adicionando novo usuário `judson-silva' (1007) ao grupo `judson-silva' ...
Criando diretório pessoal `/home/judson-silva' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para judson-silva
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: Judson Pereira da Silva
	Número da Sala []: 9u 
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
A informação está correta? [S/n] 
jurandy@amazonas:~$ id judson-silva
uid=1007(judson-silva) gid=1007(judson-silva) grupos=1007(judson-silva)
jurandy@amazonas:~$ 
jurandy@amazonas:~$ sudo adduser marcos-vinicios
Adicionando o usuário `marcos-vinicios' ...
Adicionando novo grupo 'marcos-vinicios' (1008) ...
Adicionando novo usuário `marcos-vinicios' (1008) ao grupo `marcos-vinicios' ...
Criando diretório pessoal `/home/marcos-vinicios' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
Sorry, passwords do not match
passwd : Erro de manipulação de token de autenticação
passwd: senha inalterada
Tentar novamente? [s/N] s
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
Sorry, passwords do not match
passwd : Erro de manipulação de token de autenticação
passwd: senha inalterada
Tentar novamente? [s/N] s
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para marcos-vinicios
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: Marcos Vinicios
	Número da Sala []: 7u
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
A informação está correta? [S/n] 
jurandy@amazonas:~$ id marcos-vinicios
uid=1008(marcos-vinicios) gid=1008(marcos-vinicios) grupos=1008(marcos-vinicios)
jurandy@amazonas:~$ 
jurandy@amazonas:~$ sudo adduser maxswell-silva
Adicionando o usuário `maxswell-silva' ...
Adicionando novo grupo 'maxswell-silva' (1009) ...
Adicionando novo usuário `maxswell-silva' (1009) ao grupo `maxswell-silva' ...
Criando diretório pessoal `/home/maxswell-silva' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
Sorry, passwords do not match
passwd : Erro de manipulação de token de autenticação
passwd: senha inalterada
Tentar novamente? [s/N] s
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para maxswell-silva
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: Maxswell Silva
	Número da Sala []: 
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
A informação está correta? [S/n] 
jurandy@amazonas:~$ id maxswell-silva
uid=1009(maxswell-silva) gid=1009(maxswell-silva) grupos=1009(maxswell-silva)
jurandy@amazonas:~$ 
jurandy@amazonas:~$ sudo adduser joel-brito
Adicionando o usuário `joel-brito' ...
Adicionando novo grupo 'joel-brito' (1010) ...
Adicionando novo usuário `joel-brito' (1010) ao grupo `joel-brito' ...
Criando diretório pessoal `/home/joel-brito' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para joel-brito
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: Joel de Brito Flozino
	Número da Sala []: 9u    
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
A informação está correta? [S/n]
jurandy@amazonas:~$ sudo adduser nome-sobrenome
Adicionando o usuário `nome-sobrenome' ...
Adicionando novo grupo 'nome-sobrenome' (1003) ...
Adicionando novo usuário `nome-sobrenome' (1003) ao grupo `nome-sobrenome' ...
Criando diretório pessoal `/home/nome-sobrenome' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para nome-sobrenome
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: Nome Completo
	Número da Sala []: 
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
A informação está correta? [S/n] 
jurandy@amazonas:~$ 
jurandy@amazonas:~$ sudo adduser jurandy-soares
Adicionando o usuário `jurandy-soares' ...
Adicionando novo grupo 'jurandy-soares' (1004) ...
Adicionando novo usuário `jurandy-soares' (1004) ao grupo `jurandy-soares' ...
Criando diretório pessoal `/home/jurandy-soares' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para jurandy-soares
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: Jurandy Martins Soares Júnior
	Número da Sala []: 
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
chfn: nome com caracteres não-ASCII: 'Jurandy Martins Soares Júnior'
A informação está correta? [S/n] 
jurandy@amazonas:~$ id jurandy-soares
uid=1004(jurandy-soares) gid=1004(jurandy-soares) grupos=1004(jurandy-soares)
jurandy@amazonas:~$ 
jurandy@amazonas:~$ sudo adduser jose-carlos
Adicionando o usuário `jose-carlos' ...
Adicionando novo grupo 'jose-carlos' (1005) ...
Adicionando novo usuário `jose-carlos' (1005) ao grupo `jose-carlos' ...
Criando diretório pessoal `/home/jose-carlos' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
Sorry, passwords do not match
passwd : Erro de manipulação de token de autenticação
passwd: senha inalterada
Tentar novamente? [s/N] s
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para jose-carlos
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: José Carlos de Brito Albino do Nascimento
	Número da Sala []: 6b
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
chfn: nome com caracteres não-ASCII: 'José Carlos de Brito Albino do Nascimento'
A informação está correta? [S/n] 
jurandy@amazonas:~$ id jose-carlos 
uid=1005(jose-carlos) gid=1005(jose-carlos) grupos=1005(jose-carlos)
jurandy@amazonas:~$ 
jurandy@amazonas:~$ sudo adduser
adduser: Somente um ou dois nomes permitidos.
jurandy@amazonas:~$ sudo adduser fernanda-aureliano
Adicionando o usuário `fernanda-aureliano' ...
Adicionando novo grupo 'fernanda-aureliano' (1006) ...
Adicionando novo usuário `fernanda-aureliano' (1006) ao grupo `fernanda-aureliano' ...
Criando diretório pessoal `/home/fernanda-aureliano' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para fernanda-aureliano
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: Fernanda dos Santos Aureliano
	Número da Sala []: 8a
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
A informação está correta? [S/n] 
jurandy@amazonas:~$ id fernanda-aureliano
uid=1006(fernanda-aureliano) gid=1006(fernanda-aureliano) grupos=1006(fernanda-aureliano)
jurandy@amazonas:~$ 
jurandy@amazonas:~$ sudo adduser judson-silva
Adicionando o usuário `judson-silva' ...
Adicionando novo grupo 'judson-silva' (1007) ...
Adicionando novo usuário `judson-silva' (1007) ao grupo `judson-silva' ...
Criando diretório pessoal `/home/judson-silva' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para judson-silva
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: Judson Pereira da Silva
	Número da Sala []: 9u 
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
A informação está correta? [S/n] 
jurandy@amazonas:~$ id judson-silva
uid=1007(judson-silva) gid=1007(judson-silva) grupos=1007(judson-silva)
jurandy@amazonas:~$ 
jurandy@amazonas:~$ sudo adduser marcos-vinicios
Adicionando o usuário `marcos-vinicios' ...
Adicionando novo grupo 'marcos-vinicios' (1008) ...
Adicionando novo usuário `marcos-vinicios' (1008) ao grupo `marcos-vinicios' ...
Criando diretório pessoal `/home/marcos-vinicios' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
Sorry, passwords do not match
passwd : Erro de manipulação de token de autenticação
passwd: senha inalterada
Tentar novamente? [s/N] s
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
Sorry, passwords do not match
passwd : Erro de manipulação de token de autenticação
passwd: senha inalterada
Tentar novamente? [s/N] s
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para marcos-vinicios
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: Marcos Vinicios
	Número da Sala []: 7u
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
A informação está correta? [S/n] 
jurandy@amazonas:~$ id marcos-vinicios
uid=1008(marcos-vinicios) gid=1008(marcos-vinicios) grupos=1008(marcos-vinicios)
jurandy@amazonas:~$ 
jurandy@amazonas:~$ sudo adduser maxswell-silva
Adicionando o usuário `maxswell-silva' ...
Adicionando novo grupo 'maxswell-silva' (1009) ...
Adicionando novo usuário `maxswell-silva' (1009) ao grupo `maxswell-silva' ...
Criando diretório pessoal `/home/maxswell-silva' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
Sorry, passwords do not match
passwd : Erro de manipulação de token de autenticação
passwd: senha inalterada
Tentar novamente? [s/N] s
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para maxswell-silva
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: Maxswell Silva
	Número da Sala []: 
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
A informação está correta? [S/n] 
jurandy@amazonas:~$ id maxswell-silva
uid=1009(maxswell-silva) gid=1009(maxswell-silva) grupos=1009(maxswell-silva)
jurandy@amazonas:~$ 
jurandy@amazonas:~$ sudo adduser joel-brito
Adicionando o usuário `joel-brito' ...
Adicionando novo grupo 'joel-brito' (1010) ...
Adicionando novo usuário `joel-brito' (1010) ao grupo `joel-brito' ...
Criando diretório pessoal `/home/joel-brito' ...
Copiando arquivos de '/etc/skel' ...
Digite a nova senha UNIX: 
Redigite a nova senha UNIX: 
passwd: senha atualizada com sucesso
Modificando as informações de usuário para joel-brito
Informe o novo valor ou pressione ENTER para aceitar o padrão
	Nome Completo []: Joel de Brito Flozino
	Número da Sala []: 9u    
	Fone de Trabalho []: 
	Fone Residencial []: 
	Outro []: 
A informação está correta? [S/n]
```

<a name="remoto">

## Configuração do aceso gráfico
```
sudo apt install tasksel xrdp
sudo apt tasksel install ubuntu-mate-core
```
