# memoria

# Ram:
Sigla de Random access memory (memória de acesso aleatório), é a tecnologia que permite o 
o acesso dos arquivos armazenados no computador. Ela não armazena os conteudos permanentemente mas é responsavel pela leitura dos conteudos requeridos.

Ao carregar um programa, ele é lido no HD (ou outra mídia de armazenamento) e é transferido para a memória RAM, para ser executado pelo processador. A memória RAM oferece tempos de acesso mais baixos que o HD e trabalha com taxas de transferência mais altas, mas possui a desvantagem de perder os dados armazenados quando o micro é desligado, por isso a necessidade de salvar os arquivos periodicamente.

Quando é acessado uma grande quantidade de memória  no HD de uma só vez, é necessário uma grande quantidade de memória RAM,que é medida pelo fluxo de bits suportados nas operações.
Há dois tipos de tecnologia de memória RAM que são muitos utilizados: estático e dinâmico, isto é, SRAM e DRAM, e tambem o tipo mais recente chamado de MRAM.
A capacidade de processamento da memória RAM tambem é influenciada pela largura e a velocidade do barramento, que é um conjunto de “fios” responsáveis pela conexão da memória com os outros componentes.

 # ROM 
 
 Sigla de Read-Only Memory (Memória Somente de Leitura) é onde se tem os dados são gravados nelas apenas uma vez. Depois disso, essas informações não podem ser apagadas ou alteradas, apenas lidas pelo computador, exceto por meio de procedimentos especiais.Diferentemente da memória RAM, os dados contidos em uma memória ROM não são destruídos nem perdidos em caso de interrupção da energia elétrica, por isso, é chamada de “memória não volátil”.
 Na memória ROM é empregada para armazenar informação da configuração do sistema, dos programas de arranque ou início, suporte físico e outros programas que não precisam de atualização constante.
  
  principais tipos de memória ROM:
 - EEPROM (Electrically-Erasable Programmable Read-Only Memory): este tipo de memória ROM também permite a regravação de dados, no entanto, ao contrário do que acontece com as memórias EPROM, os processos para apagar e gravar dados são feitos eletricamente, fazendo com que não seja necessário mover o dispositivo de seu lugar para um aparelho especial para que a regravação ocorra;

- EAROM (Electrically-Alterable Programmable Read-Only Memory): as memórias EAROM podem ser vistas como um tipo de EEPROM. Sua principal característica é o fato de que os dados gravados podem ser alterados aos poucos, razão pela qual esse tipo é geralmente utilizado em aplicações que exigem apenas reescrita parcial de informações;

- Flash: as memórias Flash também podem ser vistas como um tipo de EEPROM, no entanto, o processo de gravação (e regravação) é muito mais rápido. Além disso, memórias Flash são mais duráveis e podem guardar um volume elevado de dado

# Swap

 Memoria virtual é espaço variavel no disco rígido reservado para ajudar a armazenar os dados da memória RAM quando ela está cheia. É uma forma de estender a quantidade de memória para os dados temporários utilizados pelos aplicativos em execução sem que precise fazer um upgrade de hardware. Quando o Sistema Operacional notar que a Memória RAM não tem mais espaço de execução, o sistema vai passar a executar os seus programas na Memória Virtual.
Quando a Memória Virtual é utilizada, o sistema fica extremamente lento.Ela pode ser chamada também de: Page-file, paginação, memória paginada, swap ou memória de troca.

# Paginação de memoria

A paginação permite que o programa possa ser espalhado por áreas não contíguas de memória. Com isso, o espaço de endereçamento lógico de um processo é dividido em páginas lógicas de tamanho fixo e a memória física é dividida em páginas com tamanho fixo, com tamanho igual ao da página lógica. Nisso, o programa é carregado página a página, cada página lógica ocupa uma página física e as páginas físicas não são necessariamente contíguas. O endereço lógico é inicialmente dividido em duas partes : um número de página lógica (usado como índice no acesso a tabela de páginas, de forma a obter o número da página física correspondente) e um deslocamento dentro da página. Não existe fragmentação externa, porém existe fragmentação interna.A transferência das páginas de processo podem ser transferidas para a memória por demanda, levando apenas o que é necessário para a execução do programa ou por paginação antecipada, onde o sistema tenta prever as páginas que serão necessárias à execução do programa






>referencias bibliograficas:
http://www.cursosdeinformaticabasica.com.br/o-que-e-memoria-virtual/
http://www.techtudo.com.br/artigos/noticia/2012/02/o-que-e-memoria-ram-e-qual-sua-funcao.html
http://queconceito.com.br/memoria-rom
http://www.diolinux.com.br/2014/09/o-que-e-memoria-swap.html
https://gustavoschroeder.wordpress.com/2015/06/25/paginacao-x-segmentacao/



