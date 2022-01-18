# vtex-minimal-store

Este projeto servirá para produzir práticas do Vtex seguindo sua documentação. 
Documentação dísponivel no link: https://developers.vtex.com/

Como Rodar?
 Antes de tudo você deve instalar a extensão do VtexIO na sua máquina. A própia documentação do Vtex ensina a instalação no link a seguir:
 https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-vtex-io-cli-install 
 
 faça a instalação seguindo o passo a passo conforme o seu Sistema operacional.
 
 Após a instalaão do Vtex, abra seu terminal de comando de preferência e rode os seguintes comandos:
 - vtex login ${your-account}
 // Para realizar o login da sua conta Vtex, Após estar loggado, utilize um workspace para realizar seus teste com o seguinte comando: 
- vtex use ${your-workspace}
 //Caso o nome que você selecionou não exista, o vtex irá criar o workspace solicitado. Para verificar os workspaces disponíveis, pod rdar o comando: vtex workspace list.
 
 Após estar devidamente logado e já usando o workspace desejável, basta clonar o layout de uma Minimal-Store que a própia vtex disponibiliza no seguinte link:
 https://github.com/vtex-apps/minimum-boilerplate-theme
 
 Basta seguir o passo a passo no Readme do link acima. Após clonar o layout minimo, você consegue abrí-lo para acompanhar suas edições em tempo real.
No terminal, rode o comando:
- vtex link
Será realizado Build do código, após isso, abra um novo terminal, vá até a pasta local que clonou os documentos do vtex e rode o comando:
- vtex browse
OU
Abra um browser de preferência e escreva o seguinte link:
https://workspacename-aaccountname.myvtex.com/
Substitua workspacename pelo nome do seu workspace usado e accountname pelo nome da sua conta.
