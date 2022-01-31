# Hã?

A>***Rusty**: Você precisaria de ao menos uma dúzia de homens fazendo uma combinação de habilidades.*
A>
A>***Dany**: Como o quê? O que você tem em mente?
A>
A>***Rusty**: À primeira vista, eu diria que você está procurando por um Boeski, um Jim Brown, uma Miss Daisy, dois Jethros e um Leon Spinks, sem mencionar a melhor Ella Fitzgerald do mundo.*
A>
A>*Onze Homens e um Segredo* (Ocean's Eleven,2001)

É possível aprender jornalismo de dados em uma hora?

Esse foi o desafio que encarei no final de 2011,quando fui convidado a ir a Bristol para ministrar um curso intensivo.

Afinal, para cada manchete relacionada ao [Wikileaks ](http://www.theguardian.com/world/iraq-war-logs) e aos [Gastos feitos por membros do parlamento](http://www.telegraph.co.uk/news/newstopics/mps-expenses/). Ou que noticiam desde o surto de gripe em determinada área até a classificação do melhor jogador da Premier League, existe o uso do jornalismo de dados que passa, muitas vezes, despercebido. E, graças a esse desconhecimento, foi criado o mito de que o jornalismo de dados é complicado, espetacular ou exige muitos recursos. 
Mas nem sempre é assim.

Pensando nisso, resolvi destrinchar o tema para reduzi-lo a algumas técnicas básicas. O resultado é este livro que aborda os fundamentos do jornalismo de dados. Começando pelas habilidades básicas para produzir notícias — partindo da localização— passando por formas rápidas de obter informações complementares aos dados, até maneiras de apresentá-los ao público de forma eficiente.

Nisso, volto à pergunta inicial: é possível aprender jornalismo de dados em uma hora?

Definitivamente não. Mas você pode aprender o suficiente para dar os primeiros passos na produção das suas matérias. E o mais importante: adquirir, dentro do possível, uma base para se desenvolver ainda mais na área (assunto que abordarei no final do livro).

Este é o *Data Journalism Heist*: nada ilegal, apenas um conceito que busca abranger a complexidade, urgência e limpeza dessa abordagem. Bem como a importância do último elemento: '*Ninguém sai ferido*'.

Portanto, sem mais delongas vamos tratar de jornalismo de dados! Pois, como visto anteriormente, esse é um tema que também está relacionado à velocidade e nós já estamos perdendo no quesito tempo.

# Onde estão os dados?

Todo bom golpe inicia com a missão de identificar e explorar o melhor local para a nossa operação. E o jornalismo de dados conta com vários sites que tornam isso possível.

*Logo, se o seu país estado ou cidade tem um banco de dados, é importante destacar que ele deve receber atualizações constantes. Dessa forma, você pode encontrar [uma lista em](http://ckan.org/instances/) com alguns deles. Os nomes vão desde [data.gov.uk](http://data.gov.uk) no Reino Unido, até localidades menores como [Waterloo](http://www.regionofwaterloo.ca/en/regionalgovernment/OpenDataHome.asp) no Canadá,[Emilia-Romagna](http://datablog.ahref.eu/en/ahref-log/opendata/open-data-la-regione-emilia-romagna-presenta-il-suo-portale) na Itália ou [Chicago](https://data.cityofchicago.org/) nos Estados Unidos;
*Portanto, descobrir se o seu país tem um provedor de estatísticas nacionais é o primeiro passo. [Uma lista desses fornecedores pode ser encontrada no portal Wikipédia](http://en.wikipedia.org/wiki/List_of_national_and_international_statistical_services);
*Além disso, outra forma de chegar aos dados é por meio das solicitações amparadas pela Lei de Acesso à Informação (Freedom of Information Act). Verifique se existe em seu país algum site que permita ao público o envio e monitoramento deste pedido (como o [Whatdotheyknow.com](http://whatdotheyknow.com) no Reino Unido e [AskTheEU](http://www.asktheeu.org) para a União Europeia).
*Você ainda pode optar pela busca de registros  dessas solicitações recebidas  por essas agências.

Tire um tempo para considerar essas opções. Outro caminho é providenciar o recebimento desses dados regularmente. Seja através do e-mail ou ainda pelo feed RSS, se esse for o método que você utiliza para acompanhar as atualizações de vários sites.

T>Caso a página da internet não permita atualizações por estas formas, tente usar o [ChangeDetection.com](http://ChangeDetection.com). Essa ferramenta envia um e-mail a cada alteração nos sites que você selecionar.

Ainda, se você está cobrindo — ou tem interesse particular em — um tema específico como criminalidade, saúde, educação, bem-estar social ou meio ambiente; você pode buscar por *órgãos* locais e (inter)nacionais que publiquem dados na área.

Partindo do Reino Unido como exemplo, segue abaixo uma breve lista de fontes gerais cujos dados são atualizados constantemente:

*Educação: Higher Education Statistics Agency (HESA), Higher Education Funding Council (HEFCE) e Universities and Colleges Admission Service (UCAS)- todos eles disponibilizam informações sobre as universidades e os estudantes. Já o Office for Standards in Education, Children's Services and Skills (Ofsted), responsável pela inspeção e definição dos padrões educacionais na Inglaterra, reúne dados sobre estudantes menores de 16 anos.
*Saúde: NHS Information Centre (NHSIC) e Health Episode Statistics (HES) fornecem números relacionados às internações hospitalares e profissionais do ramo na região.
*Trabalho: NOMIS oferece dados quanto aos  índices de empregabilidade e desemprego.
*Segurança: o Data.police.uk possui informações acerca da criminalidade e policiamento.

## Explorando sites de governos locais

A missão a seguir trata de um tipo específico de dado que você encontrará frequentemente nas suas buscas: os gastos administrativos em uma determinada região.

A partir de agora, vamos fazer um exercício de análise dessas informações. Lembre-se que o conteúdo não é o mais importante nesse momento. E sim, o procedimento que você pode repetir com a maioria dos dados públicos — sejam voltados para o meio ambiente, índices no mercado de trabalho, climáticos, entre outros.

Dessa vez, vamos usar a Inglaterra como estudo de caso: todos os seus governos regionais são obrigados a publicar as despesas que ultrapassam o valor de £500. Para encontrar essas informações, basta pesquisar por `gastos 500` seguido pelo nome de uma localidade. Aqui, procuraremos por Birmingham — a maior na Europa. Os dados sobre os custos administrativos dessa cidade podem ser encontrados em [Birmingham.gov.uk/payment-data](http://www.birmingham.gov.uk/payment-data). Aqui, você achará os gastos mensais dos últimos doze meses de gerenciamento, podendo solicitar informações mais antigas através de e-mail.

Vale ressaltar que o material é fornecido pelo site em dois formatos: planilhas e PDF. E eu recomendo a você que, sempre que puder, evite a última opção.

A>Caso escolha trabalhar com dados internacionais, você pode optar por baixar [dados sobre empréstimos do Banco Europeu de Investimento](http://www.eib.org/projects/loans/list/index.htm) — basta mudar a pesquisa para os critérios mais amplos possíveis.

Em seguida, clique na opção em *Export* (procure atenciosamente por ela, pois é difícil de encontrar) no fim da página para obter uma planilha em Excel. Apesar de ela aparecer nesse modelo, são, na verdade, arquivos em formato **CSV**, que podem ser abertos em qualquer software de planilhas. Incluindo opções gratuitas como o Google Sheets e [Open Office](http://www.openoffice.org/) (que também abre arquivos em Excel).

I>CSV é a sigla para Valores Separados por Vírgulas — como o próprio nome explica — neles o valor de cada coluna é separado por vírgulas, como: `Nome, Data de Nascimento, Endereço`. Consequentemente, quando ele é aberto em um software de planilhas, cada vírgula é substituída por uma coluna.

De volta ao exercício, o nosso próximo passo consiste em  clicar na versão mais recente de *planilha* sobre os dados de gastos (não no PDF) e fazer o download em seu computador. Por isso, lembre de salvar o arquivo num lugar fácil para encontrar depois, como na Área de Trabalho. A partir daí, você pode abri-lo no software de sua preferência — clicando duas vezes nele ou [fazendo o envio para uma ferramenta baseada na web como o Google Drive](https://support.google.com/drive/answer/2424368?hl=pt-br).

Agora sim! Conseguimos entrar.

T> Mas, antes de prosseguir, se a sua única opção ainda for os dados em PDF,tente usar um conversor desse formato para Excel como [PDFtoExcelOnline.com](PDFtoExcelOnline.com), [PDF2XL](http://www.cogniview.com/pdf-to-excel/pdf2xl-basic) ou [Wondershare PDF Converter](http://www.wondershare.com/pdf-converter/). Você, também, pode tentar entrar em contato com o site que forneceu as informações. Ou ainda, solicitá-las no formato de planilha por meio da Lei de Acesso à Informação.

I>###Maneiras alternativas de obter dados:
I>
I>Crie uma rede de contatos: conseguir informações através de intermediários não é menos importante no jornalismo de dados do que em outras áreas da profissão. Essas pessoas podem te alertar sobre novidades, ou ainda fornecê-las diretamente.
I>
I>Solicite os dados com base nas leis de direito à informação como a Freedom of Information Act (FOI). Para se aprofundar nesse tema, recomendo o livro da jornalista Heather Brooke, *Tu derecho a saber* (versão em espanhol).
I>Outra opção é realizar uma raspagem de dados por um software ou programação. Para mais informações sobre essa técnica, consulte meu livro *[Extracción de datos para periodistas (versão em espanhol)](http://leanpub.com/scrapingforjournalists)*.














