# Objetivo geral

Introduzir ao versionamento de código com Git e Github.

- Conhecer as ferramentas
- Instalar, Configurar e Autenticar
- Primeiros Passos com Git e Github
- Dicas e Materiais de Apoio

Versionamento de código, git e github.

## O que é versionamento?

Imagine que você está construindo uma casa de blocos de montar. Cada vez que você adiciona ou muda um bloco, você registra isso em um caderno, certo? Assim, se você quiser voltar atrás e ver como a casa estava em um determinado momento, você pode olhar no caderno e ver todas as mudanças que foram feitas.

Bom, versionamento de código é mais ou menos isso, mas para os programas de computador. Quando as pessoas escrevem programas, elas geralmente trabalham em equipes e fazem muitas mudanças nos códigos o tempo todo. Às vezes, essas mudanças podem causar problemas, como quando uma parte do código para de funcionar por causa de uma mudança que alguém fez.

É aí que entram os sistemas de controle de versão! Eles são como o caderno para as casas de blocos de montar, mas para os programas de computador. Eles registram todas as mudanças que são feitas no código, quem fez essas mudanças e quando elas foram feitas. Isso é muito útil porque, se algo der errado, podemos voltar para uma versão anterior do código, como se voltássemos no tempo para antes do problema acontecer.

Os sistemas de controle de versão também ajudam as equipes de desenvolvimento a trabalhar juntas de forma mais organizada. Eles garantem que todos tenham acesso às versões mais recentes do código e ajudam a evitar que pessoas mudem o código ao mesmo tempo e causem confusão.

Então, resumindo, os sistemas de controle de versão são como cadernos que registram todas as mudanças feitas nos programas de computador, ajudando as equipes a trabalharem juntas de forma mais organizada e permitindo que voltemos no tempo se algo der errado.

## Tipos de Sistemas de Controle de Versão

Dentre os Sistemas de COntrole de Versão (VCS), temos:

VCS Centralizado (CVCS) - CVS, Subversion.

Existe apenas um servidor responsavel pelo controle de versão, a grande desvantagem é em caso de servidor ficar fora do ar não é possivel salvar ou recuperar os projetos.

VCS Distribuído (DVCS) - Git, Mercurial.

Para resolver esses problemas o VCS Distribuido permite que cada desenvolvedor crie uma cópia dos arquivos presentes no servidor, permitindo que os projetos não sejam interrompidos caso o serviço fique fora do ar.