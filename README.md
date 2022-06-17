
<h1 align="center"> 
  <b> Flyin' 🎧 </b>
</h1>
<h2 align="center">
  <i> web music player </i>
</h3>

![flyin'](https://user-images.githubusercontent.com/101335613/174322420-3e2e81c1-cc69-425c-a154-feb23df76f7f.png)


![Badge](https://img.shields.io/badge/code-WELCOME-F25764?style=for-the-badge&logo=) ![Badge](https://img.shields.io/badge/status-COMPLETE-A52F64?style=for-the-badge&logo=) ![Badge](https://img.shields.io/badge/language-PTBR-FF5F99?style=for-the-badge&logo=)

  <h2 align="center">
 .{tabela de conteúdos 📌
                  </h2>
                
<p align="center">
 <a href="#about">~about</a> •  
 <a href="#question6">~question 6</a> • 
 <a href="#aplication">~aplication</a> • 
 <a href="#developers">~developers</a>
</p> 


<h2 align="center" id="about">
 .{about 🎧
</h2>

  
- O programa "Flyin' Web Music Player" se trata, como descrito, de uma playlist com músicas pré-selecionadas, onde é possível ouvir suas músicas favoritas através de uma interface dinâmica e prática. 
  
- O código foi modificado com o objetivo de aprendizado para o projeto final na disciplina de "Fundamentos da Programação", onde utilizamos os seguintes códigos como base:
  
- https://www.youtube.com/watch?v=1-CvPn4AbT4&t=349s

  <p align="center">
<b> 🥤 As músicas presentes no código foram: </b> 
-   Boys Don't Cry - The Cure
-   Little Dark Age - MGMT
-   Psycho Killer (2005 Remaster) - Talking Heads
-   Rhinestone Eyes - Gorillaz
-   Running Up That Hill (A Deal With God) (2018 Remaster) - Kate Bush
-   The Final Countdown - Europe
-   One Kiss - Calvin Harris, Dua Lipa
-   Hayloft II - Mother Mother
-   505 - Artic Monkeys
-   O Descobridor Dos Sete Mares - Tim Maia
-   Coringa - Jão
-   Lost Boy - Ruth B.
-   Dear Parents - Tate McRae

</p>


<h2 align="center" id="question6">
 .{question 6 ✏️
</h2>
<p align="center">
  <b> <i> 🍃 Resposta para a questão 6 da atividade do Projeto Final de Fundamentos da Programação: </b> </i>

- Explique, com suas próprias palavras, o que faz o seguinte trecho de código:
</p>

<code>
  const createSongList = () => {
  const list = document.createElement("ol");
  for (let i = 0; i < songs.length; i++) {
    const item = document.createElement("li");
    item.appendChild(document.createTextNode(songs[i].slice(0,-4)));
    list.appendChild(item);
  }
  return list;
};
                                   
</code>
 
O código acima cria uma arrow function entitulada "createSongList", que possui uma constante chamada "list", onde armazena 'document.createElement' que é uma API (DOM) usada para manipular elementos, onde através dela, está criando um novo elemento: 'ol'. Um elemento 'ol' simboliza uma lista ordenada.
  
 Se pode traduzir a parte for (let i = 0; i < songs.lenght; i++) como sendo o momento em que o código vai ler cada elemento contido na array 'songs', e conforme isso acontece, ele cria um novo elemento, dentro de uma constante a partir da DOM, sendo 'li'. O elemento 'li' se refere a um elemento contido dentro de uma lista.  
                                                           Com isso, cada vez que um novo elemento é criado na lista constante 'item', o .appendChild auxilia na criação de um novo elemento adicionando um novo item 'filho' (children) ao elemento 'pai' (parent). Ele adiciona um 'nó' de texto (createTextNode) para mostrar o títulos de cada uma das músicas na lista 'songs' que está sendo percorrida pela variável 'i', sendo separadas pelo '.slice'.    
                                                           
Além disso, a constante 'item', que armazena todo o processo do 'createTextNode', é inserida como 'appendChild' (filha) da constante 'list', onde a lista ordenada 'ol' está.                                                                                
Dessa forma, ao realizar o 'return list', está mostrando a lista de músicas (em 'songs') na tela do usuário. 
    
<h2 align="center" id="aplication">
 .{aplication 🍓
</h2>
  

<p align="center">
  <b> <i> 🎼 Demonstração de como o programa é exibido no desktop, apresentando as seguintes funcionalidades: </b> </i>
  </p>
  • loop de músicas.
  
  • lista de músicas para selecionar a desejada.
  
  • pular para momentos específicos de uma músicas.
  
  • pular músicas (próxima ou anterior).
  
  • modo aleatório.
</p>
  
![flyin'](https://user-images.githubusercontent.com/101335613/174390248-30dce86b-c002-462f-8d8d-64cc5355b329.gif)

<h2 align="center" id="developers">
 .{developers 🎶
</h2>

<p align="center">
  <b> <i> 👩‍💻 Desenvolvedoras que ajudaram a personalizar o código. </b> </i>
</p>


| [<img src="https://avatars.githubusercontent.com/u/106769049?v=4" width=115><br><sub>Livia Riegel</sub>](https://github.com/liviariegel) |  [<img src="https://avatars.githubusercontent.com/u/96701270?v=4" width=115><br><sub>Vitória Diniz</sub>](https://github.com/vantusrg) |  [<img src="https://avatars.githubusercontent.com/u/101335613?s=400&u=208cc7f426ab58ecedbd8c8c489afd1788361798&v=4" width=115><br><sub>Letícia Dutra</sub>](https://github.com/leticiadutra22-23) |
| :---: | :---: | :---: |


