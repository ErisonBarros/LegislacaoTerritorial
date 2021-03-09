# Os Bens
**Prof. Erison**

# Os Bens

Os bens são tratados no **Livro II, do Código Civil**, **artigos 79 a 103.**   O solo e tudo que a ele for incorporado, natural ou artificialmente, são considerados bens imóveis. As edificações separadas do solo,  
mas que conservem sua unidade, removidas para outro local, não perdem seu caráter de imóveis, bem como os materiais provisoriamente separados de um prédio, para nele se reempregarem. Por outro lado, os materiais novos destinados a uma construção e aqueles oriundos de demolição constituem bens móveis.*

## Tipos de Bens

 - **Os bens fungíveis** são aqueles bens móveis que podem ser substituídos    por outros da mesma espécie, qualidade e quantidade. O exemplo    clássico desse tipo de bem é o dinheiro. São, portanto, bens  substituíveis.
 - **Os bens infungíveis** são os que não podem ser substituídos por  
outros da mesma espécie. Cada um deles possui um elemento que o diferencia dos demais.
 - **Os bens divisíveis** são os que se podem fracionar sem alteração  de   sua substância, diminuição ponderável de valor, ou prejuízo do uso a    que se destinam.
 - **Os bens singulares** são os que, embora reunidos, são considerados individualmente, independentes dos demais. Se possuem destinaçãounitária, e pertinentes à mesma pessoa, a pluralidade de bens singulares constitui universalidade de fato.
 - 

 

## Mudar para outro arquivo

Todos os seus arquivos e pastas são alternativos como uma árvore no explorador de arquivos. Você pode alternar de um para outro clicando em um arquivo na árvore.

## Renomear um arquivo

Você pode renomear o arquivo atual clicando no nome do arquivo na barra de navegação ou clicando no botão ** Renomear ** no explorador de arquivos.

## Excluir um arquivo

You can delete the current file by clicking the **Remove** button in the file explorer. The file will be moved into the **Trash** folder and automatically deleted after 7 days of inactivity.

## Export a file

You can export the current file by clicking **Export to disk** in the menu. You can choose to export the file as plain Markdown, as HTML using a Handlebars template or as a PDF.


# Synchronization

Synchronization is one of the biggest features of StackEdit. It enables you to synchronize any file in your workspace with other files stored in your **Google Drive**, your **Dropbox** and your **GitHub** accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow... The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.

There are two types of synchronization and they can complement each other:

- The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.
	> To start syncing your workspace, just sign in with Google in the menu.

- The file synchronization will keep one file of the workspace synced with one or multiple files in **Google Drive**, **Dropbox** or **GitHub**.
	> Before starting to sync files, you must link an account in the **Synchronize** sub-menu.

## Open a file

You can open a file from **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Open from**. Once opened in the workspace, any modification in the file will be automatically synced.

## Save a file

You can save any file of the workspace to **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.

## Synchronize a file

Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.

If you just have modified your file and you want to force syncing, click the **Synchronize now** button in the navigation bar.

> **Note:** The **Synchronize now** button is disabled if you have no file to synchronize.

## Manage file synchronization

Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking **File synchronization** in the **Synchronize** sub-menu. This allows you to list and remove synchronized locations that are linked to your file.


# Publication

Publishing in StackEdit makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **WordPress** and **Zendesk**. With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.

> Before starting to publish, you must link an account in the **Publish** sub-menu.

## Publish a File

You can publish your file by opening the **Publish** sub-menu and by clicking **Publish to**. For some locations, you can choose between the following formats:

- Markdown: publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).

## Update a publication

After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the **Publish now** button in the navigation bar.

> **Note:** The **Publish now** button is disabled if your file has not been published yet.

## Manage file publication

Since one file can be published to multiple locations, you can list and manage publish locations by clicking **File publication** in the **Publish** sub-menu. This allows you to list and remove publication locations that are linked to your file.


# Markdown extensions

StackEdit extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

`` `
 seqüência de sereiaDiagrama 
Alice - >> Bob: Olá Bob, como vai você? 
Bob - >> John: E você John? 
Bob - x Alice: Estou bem, obrigado! 
Bob-x John: Estou bem, obrigado! 
Nota à direita de John: Bob pensa muito <br/> muito tempo, tanto <br/> que o texto <br/> não cabe em uma linha. Bob -> Alice: Checando com John ... Alice-> John: Sim ... John, como você está? `` `





E isso produzirá um fluxograma:

`` `
 Gráfico sereia LR 
A [Retângulo] - Texto do link -> B ((Círculo)) 
A -> C (Retângulo redondo) 
B -> D {Rhombus} 
C -> D` ``

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE2MjMxNjM0NThdfQ==
-->