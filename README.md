# App de lembretes e tarefas com Kotlin.
Feito no curso da [Digital Innovation One](https://digitalinnovation.one/).

Aplicativo resiliente que não perde as tarefas salvas quando é encerrado, usando a estratégia de salvar os dados localmente. 

Podemos fazer isto de duas maneiras usar nossas [Shared Preferences](https://developer.android.com/training/data-storage/shared-preferences?hl=pt-br) ou nosso [SQLite](https://developer.android.com/training/data-storage/sqlite) para utilizar esses conceitos de uma maneira facilitada devemos usar as seguintes bibliotecas:

 - [Room](https://developer.android.com/training/data-storage/room): é um banco de dados que oferece uma camada de abstração sobre o SQLite, e nos ajuda a lidar melhor com a complexidade do mesmo.

 - [DataStore](https://developer.android.com/topic/libraries/architecture/datastore?hl=pt-br): é uma solução de armazenamento de dados que permite armazenar pares de chave-valor ou objetos tipados.