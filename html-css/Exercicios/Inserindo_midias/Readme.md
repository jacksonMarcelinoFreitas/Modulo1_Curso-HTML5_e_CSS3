##Inserindo Mídias (aúdio e imagem no HTML5)🔈🖼️

Nesta aula o professor Guanabara mostrou como insere imagens e como fazê-las ser adaptativas ao tamanho da tela. Também indicou o caminho para colocar aúdios.

🖼️Tag para a inserção de IMAGEM dinâmica:
- &lt; picture &gt;
- &lt; img &gt; - para uma imagem padrão  
- &lt; source media="(max-width:)" srcset="imgem.png" type="image/png"&gt; 

🔈Tag para a inserção de AUDIO:
- &lt; audio &gt; - coloca-se os tipos de audios e uma mensagem padrão para que seja efetuado o dawload (caso nenhum deles carreguem).
- &lt; audio preload="metadata" autoplay controls loop &gt; 
🔹 metadata (carrega requisitos básicos) 
🔹 autoplay controls loop (mostra o controle de audio e faz o loop ao final do audio)
- &lt; src= "audio.wav" type= "audio/wav" &gt; 