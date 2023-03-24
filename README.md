# assets_repository

## PT

Esse projeto tem como ideia a interação entre dois repositórios diferentes, de modo que sempre que ocorram mudanças dentro da pasta **images**, o outro repositório seja acionado para trazer as alterações para ele.

Essa interação é feita através de Repository_dispatch que dispara uma notificação para o outro repositório.

A mesma Action também é responsável por fazer o Upload do Artefato que contém as imagens, embora existam outras formas de fazer isso, poderíamos fazer um checkout para esse repositório a partir do outro e copiar os arquivos para lá, um script Shell seria capaz de fazer isso também.

Você pode olhar o código do outro repositório através desse [link](https://github.com/guilhermeqmaia/consume_assets_repository)


## EN

This project has the idea of ​​interaction between two different repositories, so that whenever changes occur within the **images** folder, the other repository is triggered to bring the changes to it.

This interaction is done through Repository_dispatch which triggers a notification to the other repository.

The same Action is also responsible for uploading the Artifact that contains the images, although there are other ways to do this, we could checkout this repository from the other and copy the files there, a shell script would be able to do that this too.

You can look at the code of the other repository through this [link](https://github.com/guilhermeqmaia/consume_assets_repository)
