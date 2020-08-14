

# Aula 1- Versionamento 

## Meu Exercício
---
###### **Artigo de [Eduardo Fagundes](https://efagundes.com/artigos/como-funciona-a-internet/#:~:text=Para%20a%20troca%20de%20mensagens,um%20determinado%20endere%C3%A7o%20na%20Internet.)** 


# <span style="color: Black"> Como funciona a Internet? </span> :computer:
![](https://img.ibxk.com.br/materias/9847/40791.jpg) 

 
  A história da Internet começa com a paranóia da guerra fria na década de 60. com o medo da aniquilação numa guerra nuclear. O Departamento de Defesa Americano e a Agência de Desenvolvimentos de Projetos Avançados (ARPA) desenvolveram uma rede de computadores para a transmissão de informações imune a sabotagens. A idéia foi criar uma rede com vários computadores que pudessem trocar informações através de várias conexões independentes, de tal forma que se uma conexão ou um computador fossem paralisados os outros poderiam continuar a trocar informações 

Para tornar a rede de computadores imune a ataques foi usada a tecnologia de transmissão de dados por comutação de pacotes – <span style="color:green">*packet switching*.</span> Para entender essa tecnologia imagine a existência de três computadores instalados em três prédios diferentes conectados entre si através de linhas telefônicas. O computador A está ligado no computador B, o computador B está ligado ao computador C e o computador C está ligado ao computador A. Se o computador A deseja enviar uma nota para o computador C utiliza-se a rota AC. Caso exista um bloqueio na rota AC através dessa tecnologia é possível enviar a nota pela rota ABC. Como existem milhares de rotas na Internet a chance de paralisação total da rede é muito pequena.

Para que a rede possa funcionar é necessário procedimento detalhado para a troca de dados. As regras são implementadas através de <span style="color:red">“protocolos de comunicação”</span>. As regras de comunicação entre computadores são similares as de uma linguagem humana. Por exemplo, quando se estabelece uma conversa entre duas pessoas a etiqueta diz que enquanto uma fala a outra escuta; para que uma idéia seja transmitida é necessário colocar as palavras dentro de uma sintaxe da língua conveniente; caso o interlocutor não entenda a mensagem ele solicita que seja repetida. Para a troca de mensagens na Internet foi desenvolvido o protocolo de comunicação TCP/IP – <span style="color:green"> *Transmission Control Protocol/Internet Protocol*</span>. O protocolo IP é responsável por dividir uma mensagem em vários pacotes compatíveis com a rede e encaminhá-los ao computador com um determinado endereço na Internet. O protocolo TCP é responsável por manipular uma quantidade grande de dados e garantir que as informações transmitidas entre dois computadores da rede não contenham erros.

