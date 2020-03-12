# Setup

É importante ter as ferramentas certas para iniciarmos a nossa caminhada no
aprendizado da programação. Programar computadores não apenas técnica e
conhecimento, mas também a utilização de ferramentas certas para fazer as coisas
certas.

Este capítulo é basicamente voltado para prepararmos o ambiente para começarmos
a programar, inclusive preparando seu computador com algumas ferramentas que
serão necessárias ao longo do texto. Não é minha intenção criar nenhum tutorial
longo ou entrar em detalhes demais sobre cada ferramenta. Se fosse assim o livro
seria sobre ferramentas e não sobre aprender a programar.

Ao longo do texto usaremos somente o básico de cada ferramenta no intuito de
usá-las como um meio, não como um fim. Sempre que possível haverá uma dica ou
uma leitura extra para que você possa aprofundar-se em cada uma das
ferramentas. É importante que você, enquanto programador, domine as ferramentas
que decidir usar para auxiliá-lo no seu dia-a-dia.

Para começar, aqui vai a lista de ferramentas que precisaremos daqui em diante:

- Um bom editor de textos
- O intérprete Python
- Um bom controlador de versões

## Editor de textos

Os programas são escritos em arquivos de texto simples, sem formatação. O editor
de textos para editar um programa é bem diferente dos editores comuns, como o
Microsoft Word. Normalmente, estes editores fazem muito mais do que apenas
editar textos. A principal característica é o destaque de sintaxe, do inglês
_syntax highlighting_, que permite uma visualização melhor do código mostrando
palavras reservadas, cadeias de caracteres e outros elementos do programa com
cores diferentes.

Não apenas isto, mas estes editores oferecem um conjunto de ferramentas incrível
para ajudá-lo no dia-a-dia, como integração com controladores de versão,
automação de tarefas, bibliotecas de modelos de código e por aí vai. Mas, qual
editor usar?

Partindo da suposição de que você nunca programou na sua vida, o melhor editor é
aquele que você gostar. Mas para gostar de um editor de textos é preciso que
você avalie um a um, experimente, use. Cada editor tem um conceito diferente
para fazer as mesmas coisas. Para facilitar a sua vida, aqui vai uma pequena
lista de editores de textos para programadores que pode te ajudar a dar o
primeiro passo:

- _Atom_: é o editor de textos do Github. Contém, basicamente, tudo o que um
  programador precisa para escrever código de boa qualidade. É possível
  adicionar funcionalidades através de um excelente repositório de componentes
  prontos para o editor. Você encontra este editor em https://atom.io.
  
- _VSCode_: é o editor da Microsoft, baseado no Atom. Funciona bem em diversos
  sistemas operacionais, incluindo-se macOS e Linux, além do Windows. Assim como
  o Atom, tem grande variedade de componentes prontos e é muito popular nos dias
  de hoje. Você o encontra em https://code.visualstudio.com.
  
- _Sublime_: é um editor de textos pago que segue a linha do Atom e do
  VSCode. Durante muito tempo foi popular, caindo em popularidade depois do
  lançamento do Atom e do VSCode. Você o encontra em
  https://www.sublimetext.com.
  
- _Ultraedit_: um editor pago muito antigo para Windows. Cheio de opções e muito
  completo. Está no mercado há 25 anos e teve sua popularidade no início dos
  anos 2000. Você o encontra em https://ultraedit.com.
  
- _Crimson Editor_: outro editor para Windows, porém gratuito. Muito bom, cheio
  de características interessantes. Você o encontra em
  http://www.crimsoneditor.com/.
  
- _Notepad++_: Outro editor para Windows, também gratuito como o Crimson
  Editor. Tem uma certa popularidade no meio acadêmico. Você o encontra em
  https://notepad-plus-plus.org.
  
- _VIM_: VI Improved, um editor minimalista e que já vem instalado no seu
  linux. Disponível para Windows e macOS. Completo, porém um pouco difícil de
  aprender por usar comandos apenas através do teclado. Você o encontra em
  https://www.vim.org.
  
- _Emacs_: editor que não tem nada de minimalista. Um pouco difícil de aprender,
  como o VIM, por ser fortemente orientado ao uso do teclado. Porém
  absolutamente completo. É o meu editor predileto desde 2004. Disponível para
  quase todos os sistemas operacionais modernos. É o editor oficial do Projeto
  GNU. Você o encontra em https://www.gnu.org/software/emacs/.
  
- _Joe_: editor simplificado e muito simples de usar. Muito antigo, mas ainda
  disponível para download. Orientado a ações pelo teclado, é bastante limitado,
  mas uma opção a considerar. Vem em vários sabores de linux. Você o encontra em
  https://joe-editor.sourceforge.io/.
  
- _nano_: editor de textos absolutamente minimalista. Também orientado ao
  teclado e disponível em vários sabores de linux. Em algumas distros é o editor
  padrão pela sua simplicidade se comparado ao VIM. Você o encontra em
  https://www.nano-editor.org/.
  
Depois de instalado, procure ler a documentação do editor de textos que você
escolheu. É importante, neste ponto, dominar o mínimo para poder seguir
adiante. Pelo menos como salvar, abrir e editar um arquivo. Podem parecer
operações óbvias, mas se você escolheu o Emacs ou o VIM, certamente terá
dificuldades com o óbvio devido à forma como estes editores operam.

### Uma palavrinha sobre as IDEs

É importante, aqui, falarmos um pouco sobre a IDE (_Integrated Development
Environment_, ou Ambiente de Desenvolvimento Integrado em tradução livre). A IDE
é um ambiente de desenvolvimento que é muito mais do que um simples editor de
textos. Trata-se de um programa especializado que integra diversas ferramentas
sob uma única "cara" ou "interface". A ideia deste tipo de software é manter no
mesmo lugar todas as ferramentas que você poderá necessitar.

Além disso, normalmente as IDEs modernas dão suporte a uma quantidade bem grande
de linguagens de programação. O Eclipse e o Visual Studio são duas IDEs muito
populares. O Eclipse foi originalmente criado pela IBM em Novembro de 2001 e
suportado por um consórcio de desenvolvedores de software. É uma IDE sólida,
incrivelmente cheia de ferramentas.

O Visual Studio, por outro lado, nasceu bem antes. Criado em 1997 como o
ambiente de desenvolvimento da Microsoft, suportava somente as linguagens que
esta produzia na época: Visual Basic, Visual C++, Visual J++ e Visual Fox
Pro. Com o andar dos anos, a IDE tornou-se mais flexível e hoje dá suporte a uma
infinidade de linguagens. 

Existem outras IDEs no mercado, tanto pagas quanto gratuitas, como o Bloodshed
C++. Já que falamos até aqui sobre editores de textos para programadores, valia
a pena falar um pouco sobre as IDEs. No entanto, fica o alerta: as IDEs tendem a
ser complexas para quem está iniciando e demandam bastante tempo para serem
dominadas.

Sugiro que você utilize um editor de textos neste momento. Afinal, você está
aprendendo a programar e uma IDE foi criada para quem já tem alguma experiência
na escrita de código. Portanto, evite começar direto em uma IDE. Utilize um
editor mais simples. Deixe para aprender uma IDE depois de já ter alguma
experiência programando. Garanto que o aprendizado será muito mais suave.

## O intérprete Python

Python é uma linguagem _interpretada_. Falaremos sobre isso com detalhes quando
começarmos, de fato, a estudar a linguagem. Neste momento o que você precisa
saber é que a linguagem exige que você instale no seu computador um programa
especial, o _intérprete_. O código que você escrever em Python precisa do
intérprete para ser executado, ou seja, você só verá seu programa fazendo algo
se tiver o intérprete instalado.

Este programa especial, o intérprete, é quem vai ler, entender, criticar e
executar o seu código. A boa notícia é que você consegue este programa
gratuitamente em https://python.org, o site oficial do Python. Sugiro que você
escolha a última versão da série 3 e existe um bom motivo para isso. As versões
da Série 2 estão com os dias contados e existem, atualmente, apenas por questão
de compatibilidade. Em breve as versões da série 2 deixarão de existir.

O que diferencia a Série 3 da Série 2 é o suporte a Unicode, que inexiste
nativamente na Série 2. Sim, vamos estudar um pouco sobre os _encodings_
existentes e sobre internacionalização de software. O fato é que a Série 2 está
com os dias contados e a versão de preferência é a última da Série 3.

Para quem usa Windows, a instalação é rápida e direta, feita através de um
assistente de instalação já velho conhecido. No Linux você tem a opção de usar o
seu gerenciador de pacotes predileto (_snap_, _apt_, etc), ou usar o _pyenv_,
uma aplicação especial que permite que você instale qualquer versão do Python
sem que uma entre em conflito com a outra. No entanto, sugiro que você utilize a
versão 3 do python que vem com a sua distribuição pois o _pyenv_ exige algumas
competências que ainda não desenvolvemos. Assim, vamos manter o mais simples. 
