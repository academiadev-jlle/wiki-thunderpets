
# Branches

A documentação abaixo contém a explicação do uso das branches para a publicação das funcionalidades.
As branches são divididas em 3 partes: **master**, **release**, **feature**. A ordem de que são utilizadas é como segue:

## Feature
*Utilizadas para commitar as funcionalidades desenvolvidas*. De acordo com as *issues* criadas, a branch terá o desenvolvimento desta *issue* com o nome (**feature/***[nro. da issue]*).

## Release
*Branch que terá a integração das features*. Após todas serem desenvolvidas para uma determinada **release,** a mesma é enviada para a **master**. As branches das **release** seguem o mesmo padrão da **feature**, ou seja, para cada conjunto de features desenvolvidas, envia-se para a  (**release/***[nro. da release]*)

## Master
*Usada para realizar merges com releases finalizadas*.Bloqueadas para commits e merges com features. Contém o projeto funcional. Merges são feitos apenas pelo Líder da equipe.