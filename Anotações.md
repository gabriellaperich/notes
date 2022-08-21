# Anotações sobre Git e GitHub :heart:

O **Git** é um sistema de controle de versão de arquivos. Sempre quando alguém disponibiliza sua parte do projeto no Git, ele gerencia as alterações feitas e guarda um histórico. Isso é importante pois se houver algum problema você pode desfazer as alterações e voltar para a versão que estava estável. Desta forma, é possível ter maior controle dos seus projetos. Já o **GitHub** é uma plataforma onde você pode armazenar seus projetos, também chamados de _repositórios_. Outras pessoas podem acessar esses repositórios, alterá-los e comentá-los. O GitHub só suporta o Git, então para você subir seus projetos deve utilizá-lo, mas a integração entre eles é bem fácil. Costuma ser usado como portfólio.

## Criando um repositório:

O arquivo está no servidor local, ou seja, no computador do dev. Os documentos em Git começam no estágio _Untracked_, então, após inicializar o git o arquivo é movido à área de _staged_, onde o código fica escondido mas ainda não lançado em sua versão mais atual. Se, durante esse tempo em stage, o arquivo em questão é modificado ele é passado para a área de _modified_ e então é necessário, outra vez, passar esse arquivo modificado para staged. Quando enfim esse documento estiver 100% concluído é necessário "commitá-lo" para que seja salvo em sua última versão e ele se torna _unmodified_. Então, só então, o repositório está pronto para ser levado ao servidor remoto, **GitHub**.

### Termos:

Remote Repository: GitHub; Local Repository; Working Directory; Staging Area; Git; Main/Master; Repositório; Markdown; README.file; etc.