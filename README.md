Tentando aprender programação, e eu realmente não faço ideia do que estou fazendo 😅.

## **💻 Tecnologias e Ferramentas:**  

<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" /></code> VS Code

<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" /></code> C#

<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/opengl/opengl-original.svg" /></code> OpenGL

<code><img height="30" src="https://avatars.githubusercontent.com/u/5914736?s=280&v=4" /></code> OpenTK

<code><img height="30" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nuget/nuget-original.svg" /></code> StbImageSharp

## 🚀 Objetivo:

Estou tentando recriar a primeira versão do Minecraft, a rd-132211, na linguagem C# usando a biblioteca OpenTK (e falhando mizeravelmente).

#### Um pouco da minha história:

Meu primeiro contato com programação, que eu me recordo, foi tentando criar mods para Minecraft em meados de 2017, e como eu não fazia ideia do que estava fazendo, e não faço até hoje, foi usando um programa chamado PyloMCreator. Eu tinha encontrado o codigo de como o bloco de grama do minecraft se espalhava, e fiz a grama crescendo por estagios:
![Imagem2](https://github.com/user-attachments/assets/345cecdf-d165-4379-8f5b-7cf783307f4d)


No final de 2019, quando sai de uma internação psiquiatrica pra tentar tratar minha depressão, tinha uma propaganda de um certo curso, que prefiro não mensionar para evitar possiveis problemas juridicos futuros, que prometia ensinar a recriar o Minecraft. Apesar de frustrada com o curso, acho que acabei ficando um pouco obsecada com isso, conheci alguns outros cursos na Udemy e alguns videos no YouTube, você pode ver meu melhor resultado nestes videos curtos (segue os links):
- https://youtu.be/N4mYw29mtlo?si=AdKo6G4cRmIHez4b
- https://youtu.be/m-1NtXqeSX8?si=j411nu_TTJDbtLv-
- https://youtu.be/edpp7paOwfw?si=Tc-N14KnecdYmhmi
- https://youtu.be/vxxl5rHKTDs?si=pHeMn4gn24IGMXZ0
- https://youtu.be/2SBipgQl19Q?si=m5lo5s8cxQbAyhiD

Em algum momente, acho que em 2023, a Unity tava com umas polemicas de cobrança, tentei migrar para a Godot, mas não conseguia descobrir como renderizar voxels na engine de jeito nenhum, conheci o site LearnOpenGL, onde ensina a fazer alguma coisa em C++, mas ja fracassei tentando instalar a biblioteca GLFW, tentei em Java usando a biblioteca LWJGL, como o Minecraft, mas também não fui muito longe, e acabei de C#, que era uma linguagem que ja estava familiarizada por causa da Unity, com a biblioteca OpenTK.

Aqui esta uma imagem do meu progresso ja usando o Perlin Noise da versão rd-160052:
![Image](https://github.com/user-attachments/assets/98b0d398-5293-4cb3-b65f-a12a5d807f08)

Atualmente estou tentando aplicar fisica, um sistema de colisão AABB (quando eu falo sistema de colisão muita gente me pergunta que diabos é isso, basicamente para eu andar sobre o mapa sem atravessa-lo), tenho algo mais ou menos funcional. Implementei um sistema de gravidade e pulo parecido com o que eu usava na Unity, até funciona, mas o jogador inicia em y -300. Também tenho algo parecido com um Raycast, consigo quebrar blocos, mas a parte de colocar funciona quando quer.

#### To-Do:

- ✅ Gerar uma Janela
- ✅ Gerar um Triangulo
- ✅ Gerando um Shader
- ✅ Gerando um Retangulo com dois triangulos
- ✅ Gerando uma Textura usando um Texture Atlas
- ✅ Recortando um Tile do Texture Atlas
- ✅ Gerando um Icone de Janela
- ✅ Gerando uma Camera
- ✅ Movimentando a camera com as teclada W, A, S, D, Space e LeftShif
- ✅ Rotacioando a camera com o mouse
- ✅ Gerando um Bloco
- ✅ Gerando um Chunk
- ✅ Apagando faces não visiveis entre os blocos do chunk
- ✅ Definindo a posição inicial do jogador e respawn com a tecla R
- ✅ Aplicando cor para gerar uma iluminação/sombra primitiva
- ✅ Gerando camadas de pedra, grama e ar
- ✅ Gerando um Mundo de 256 x 64 x 256 blocos
- ⚠ Gerando um colisor AABB
- ⚠ Gravidade e pulo
- ⚠ Raycast
- ⚠ Highlight
- ⚠ Quebrar blocos
- ❌ Highlight apenas na lateral do bloco que a camera esta apontando
- ❌ Colocar blocos
- ✅ Salvar o jogo

#### Créditos:

Creditos pelo README.md, me baseei no README.md de um seguido, não sei como faço para mensionalo, o nome é Lucas e o nickname é SorPuti.

#### P.S.:

Queria aprender a deixar os icones um em cima do outro com o nome na frente. (P.P.S. Descobri)
Atualmente estou tentando aprender como usar o GitHub pq sempre reclamam e eu não estou entendo o pq.
Talvez esse README.md esteja ficando muito grande, mas depois eu arrumo... to aprendendo, tenham paciencia comigo.
Me recomendaram usar a biblioteca BulletSharp para implementar a fisica, mas eu não faço a mais p*** ideia de como usar, e não encontrei nenhum video ou tutorial.
Também gostaria de um biblioteca para implementar objetos 3D, para quando eu inciar a proxima versão a rd-132328 que tem aqueles Steve(s) doidos correndo e pulando pra tudo quanté lado.

Extras:
![image](https://github.com/user-attachments/assets/c3640a1a-2449-4d19-8949-21471224c90e)
![image](https://github.com/user-attachments/assets/daff38ec-e03c-46e5-aceb-3f9718f89e93)
![image](https://github.com/user-attachments/assets/218cf6e4-698d-4b1e-ba70-db7a0f7c0bf2)
![image](https://github.com/user-attachments/assets/f28639e5-fa37-4ccf-a46e-183bce90e1ed)
![image](https://github.com/user-attachments/assets/f19cb636-50e2-464c-9b3b-9e5d72981eb6)
![image](https://github.com/user-attachments/assets/d55eb6f3-ff28-4ec6-b17c-31f4a43df2bd)
![image](https://github.com/user-attachments/assets/c43780e0-e040-4b1a-ab74-bd61bd5a8229)
![image](https://github.com/user-attachments/assets/a84641f7-d440-4601-9604-2e47ffe97e9c)
![image](https://github.com/user-attachments/assets/80cb6cae-bc59-4051-9dd4-ec83f6a21f2f)
![image](https://github.com/user-attachments/assets/8eefc663-7da1-4ffd-9f68-38cfc9b717b0)

