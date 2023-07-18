# Exercícios resolvidos UML
Exercícios resolvidos dos dois primeiros capítulos do livro ["Exercitando Modelagem em UML"](https://books.google.com.br/books?id=rDPQ8iP4kQwC&printsec=frontcover&hl=pt-BR&source=gbs_atb#v=onepage&q&f=false), de Ana Cristina Melo - 2006 - Rio de Janeiro. Esse repositório inclui os arquivos na extensão do software Astah, onde são realizadas as modelagens e seus respectivos prints em .png/.jpeg

## Introdução

### Método de organização dos arquivos:
Todos os arquivos estão nomeados com o assunto do exercício, seguido de sua versão, caso haja. Ainda há o número do exercício logo a seguir. 

### Como abrir os arquivos:
Para abrir os arquivos é necessário ter instalado na sua máquina o software Astah e alguma versão do jdk. 
Na instalação do astah é marcado como opcional o jdk, portanto, desmarque somente caso já esteja instalado em sua máquina, caso contrário o Astah não rodará.

- [Link de Instalação Oficial](https://astah.net/downloads/)

<hr/>

# Capítulo 1 

### 1. Conta de Luz
_Cenário:_<br>
As informações a seguir se referem à planilha Excel de Gabriel, que controla os gastos mensais com sua conta de luz. Parada cada conta de luz cadastra-se: data em que a leitura do relógio de luz foi realizada, número da leitura, quantidade de Kw gasto no mês, valor a pagar pela conta, data do pagamento e média do consumo. <br>
Mensalmente, são realizadas as seguintes pesquisas:
- verificação do mês de maior consumo;
- verificação do mês de menor consumo.


### 2. Classe texto saída
_Cenário:_<br>
Para fixação do conceito de classes em sala de aula, prof Cristina criou com seus alunos a classe TextoSaida. <br>
O objetivo do exercício é criar uma classe que permita configurar um texto por meio de atributos (tamanho da letra, cor da fonte e cor do fundo), escolhendo em que tipo de componente ele deve ser exibido (entre as opções: label, edit e memo). <br>
Para não haver vínculo com linguagens de programação, essa classe não foi criada como herança de uma classe visual. <br>
As cores podem ser escolhidas entre os tons: preto, branco, azul, amarelo ou cinza.

### 3. Boneco em movimento
_Cenário:_<br>
Professora Cristina decidiu criar uma classe que permita mover um boneco na tela. Esse boneco deve ter nome, posição da coordenada X, posição da coordenada Y e direção atual (cima, baixo, direita, esquerda).

## 4. Horário de remédios
_Cenário:_<br>
As informações a seguir se referem a uma aplicação de controle pessoal de horário de remédios, existente no palm de Maurício. Para cada remédio cadastra-se: o nome de quem vai tomar o remédio, a data de início, a quantidade de dias que foi prescrita pelo médico, a quantidade de vezes ao dia, a dosagem e o nome do remédio. <br>
Ao cadastrar o remédio, a aplicação sugere todos os horários possíveis para tomar remédio. O usuário escolhe o melhor horário e a aplicação avisa até quando o remédio deve ser tomado e prepara uma planilha de horários. <br>
O usuário, no início do dia, seleciona a opção de planilha de horários de remédios do dia. <br>
No caso de Mauricio atrasar o horário de um remédio num determinado dia, a planilha reorganiza os horários daquele dia.

### 5. Gastos diários
_Cenário:_<br>
As informações a seguir se referem à planilha excel de Vera, que faz o controle de seus gastos diários. <br>
Para cada gasto, Vera cadastra: o tipo do gasto (reédio, roupa, refeição, etc.), adata do gasto, o valor do gasto e a forma de pagamento (dinheiro, cheque, cartão ou cheque pré) <br>
No final do mês, Vera lista o total dos gastos mensais, agrupados por tipo de gasto e exibindo o quanto foi gasto em cada tipo de forma de pagamento.

### 6. Comanda eletrônica
_Cenário:_<br>
As informações a seguir se referem a uma aplicação de controle de comanda eletrônica da padaria Doce Sabor do Seu Joquim. <br>
O cliente usa uma comanda eletrônica durante suas compras na padaria. A cada produto consumido, o atendente registra em sua comanda (que possui numeração) o produto e quantidade. <br>
Ao passar no caixa na saída da padaria, a caixa lê os gastos da comanda, finalizando a compra. Na leitura da comanda, verifica-se o valor unitário de cada produto a fim de calcular o valor total da compra.

### 7. Lista de compras
_Cenário:_<br>
Carolina controla em excel uma planilha com sua lista de compras mensais. Ela cadastra o nome do produto, a quantidade de compra, quantidade prevista para um mês, a quantidade que efetivamente será comprada e o preço estimado (atualizado todo mês).

| Produto | Unidade de Compra | Quantidade/Mês | Quantidade Compra | Preço Estimado |
|---------|------------------|----------------|-------------------|----------------|
| Arroz   | Kg               | 5              | 20                | R$ 4,50         |
| Feijão  | Kg               | 3              | 12                | R$ 7,20         |
| Leite   | Litro            | 10             | 20                | R$ 3,80         |
| Carne   | Kg               | 2              | 6                 | R$ 25,00        |
| Ovo     | Unidade          | 30             | 90                | R$ 0,50         |

| Total Estimado | R$ 150,00 |
|----------------|-----------|
|                |           |

### 8. Lista de compras (Variação A)
_Cenário:_<br>
Carolina não tem mais tempo de fazer as compras pessoalmente. Precisou detalhar o produto, de forma a lhe permitir delegar essa tarefa a outra pessoa. Além disso, não quer que paguem um valor absurdo por algum produto. Sendo assim, inclui em sua planilha as colunas "preço máximo já comprado" e "preço máximo a pagar" no mês corrente, onde esta última coluna é calculada a partir da coluna anterior acrescida de 5%. O "preço máximo já comprado" é inserido na planilha, apartir das compras efetivamente realizadas.

### 9. Lista de compras (Variação B)
_Cenário:_<br>
Carolina está assutada com a variação de preços de um supermercado para outro. Tem feito compras (ou pedido para fazer) em até três supermercados diferentes. Sendo assim, resolveu melhorar sua planilha. Criou uma segunda planilha que contém o preço mais baixo que ela já pagou em um determinado mês, indicando a que supermercado pertence. Veja a seguir:


| Produto | Unidade de Compra| Mês            | Valor Compra      | Supermercado    |
|---------|------------------|----------------|-------------------|-----------------|
| Arroz   | Kg               | Julho          | 1,80              | XXXXXXXXX       |
| Feijão  | Kg               | Agosto         | 1,75              | XXXXXXXXX       |
| Leite   | Litro            | Setembro       | 2,05              | XXXXXXXXX       |
| Carne   | Kg               | Julho          | 2,10              | XXXXXXXXX       |
| Ovo     | Unidade          | Agosto         | 2,25              | XXXXXXXXX       |

### 10. Lista de compras (Variação C)
_Cenário:_<br>
Carolina deseja saber qual o supermercado que apresentou os produtos mais baratos, em um determinado mês.

### 11. Lista de compras (Variação D)
_Cenário:_<br>
Carolina deseja desconsiderar o preço de um determinado mês para cálculos de maior ou menosr valor, ou ainda o supermercado mais vantajoso.
- Exemplo 1: Saber qual o supermercado que apresentou mais produtos baratos, num determinado mês. Supondo que ela comprou um produto numa promoção relâmpago que ofereceu 50% de desconto, esse valor não pode ser parâmetro para suas compras futuras.
- Exemplo 2: Para calcular _precoMaximoAnterior_, a aplicação pega o maior vaor. Vamos upor que um determinado produto teve queda de preço. Isso significa que os meses de preço alto não podem ser considerados para as próximas compras.

### 12. Coleção de CDS 
_Cenário:_<br>
Adriano tem uma coleção grande de CDS e gostria de cadastrar no seu palm a lista desses cds, pois as vezes nem sabe o que tem.
<br>
Ele pensou em cadastrar o nome do cantor ou conjunto, o título do Cd e o ano de lançamento.

### 13. Coleção de CDS (Variação A)
_Cenário:_<br>
Adriano notou que algun CDS são coletâneas. Sendo assi, não tem apenas um cantor (ou conjunto) e sim vários. Ele quer cadastrar essa lista de músicos, sem relacioná-los às músicas. Deseja controlar também se o CD é coletânea ou duplo. <br>
Adriano gostaria de ter cadastrada a lista das músicas de cada CD, com o tempo de duração de cada faixa. <br>
São relatórios desejados: os CDS de um determinado músico e em quais Cds está uma determinada música.

### 14. Sala de reunião
_Cenário:_<br>
Patrícia é secretária e dentre suas tarefas habituais existe a de controlar o uso das três salas de reunião, que são utilizadas por todos os setores da empresa. <br>
Ela possui pastas de trabalho em Excel para cada mês do ano e, dentro de cada pasta, existem de vinte e oito a trinta e uma planilhas, uma para cada dia do mês. <br>
Na planilha, ela criou a coluna de horários e três colunas, uma para cada sala de reunião. Num controle à parte, ela relaciona o nome do funcionário, seu cargo e ramal. Além da alocação, surge frequentemente a necessidade de realocação de uma reunião, mudando a sala e/ou data e/ou horário. <br>
Outra consulta constante que é feita à Patrícia, pelos Diretores, é sobre as salas que estão livres numa determinada data, numa faixa de horário. Para cada sala é necessário saber o número de lugares. Veja o exemplo a seguir:


| 1° de agosto |
|--------------|
|              |

| Horário | Sala 1      | Sala 105     | Sala 201 |
|---------|-------------|--------------|----------|
| 08:30   | Dr Galuco - |              |
| 09:00   | Assunto:    | Dra Maria-   |
| 09:30   | Processo em-| Assunto:     |
| 10:00   |presa mar e  | Palestra so- |
| 10:30   |lua.         |bre a nova lei|
| 11:00   |             |das falencias |
| 11:30   |             |              |


### 15. Sala de reunião (Variação A)
_Cenário:_<br>
Os materiais de apoio são divididos entre as salas de reunião. Sendo assim, é preciso controlar os materiais que estão alocados e para quais reuniões. Por exemplo: retroprojetor - sala 101 na reunião das 9h às 10:30; flip - sala 102 na reunião de 10h às 12h.

### 16. Herança
Observe as duas classes adiante: 

| Classe      | Atributos                                    | Métodos                                             |
|-------------|----------------------------------------------|-----------------------------------------------------|
| Funcionário | - matrícula: integer<br>- nome : string<br>- dataNascimento: date<br>- endereco: Endereco<br>- telefoneContato : Coleção de telefone<br>- cargo : Cargo<br>- salario: real<br>- dataAdmissao : date | - cadastrar()<br>- obterIdade()<br>- reajustarSalario(percentual:real)<br>- promover(novoCargo:Cargo) |
| Cliente     | - codigo : string<br>- nome : string<br>- dataNascimento: date<br>- endereco: Endereco<br>- telefoneContato : Coleção de telefone | - cadastrar()<br>- obterIdade()                  |

Crie uma superclasse que contenha os atributos comuns, reformulando as classes.

# Capítulo 2





