# Ponto de controle

## Trabalho em Grupo

Com base no artigo: [Designing a Complex Software System](https://betterprogramming.pub/designing-a-complex-software-system-720897671b6a), foi criado a lista a seguir, itens/documentos que poderiam estar contidos no projeto.

- No documento de requisitos, quais os resultados esperados, o que podemos obter de valor com o projeto. Uma melhor descrição desses resultados.

- Restrições do projeto (limites): Frameworks que serão utilizados, plataformas, tempo aceitável de processamento; etc; No diagrama de componente do servidor por exemplo, é pouco especificado quais tecnologias serão utilizadas. Pode-se dizer o mesmo com relação ao diagrama de componente da aplicação mobile;

- Contratos de modo geral; Não há nenhuma especificação com relação aos contratos;
    - Com relação a interação do usuário com o sistema;
    - Pouco com relação a interação do servidor com a aplicação mobile;
    - Também a pouco com relação a interação com os serviços externos;
    - Contratos de dados utilizados entre os vários sistemas e seus mecanismos de armazenamento;

- Mock-up para projetar a interface do usuário para o público-alvo;

- wiki descrevendo as principais funcionalidades;

- Diagrama de fluxo lógico;

---

## Verificação interna do projeto

- O que pode mudar ao longo do tempo foi identificado? Esta possibilidade de mudança está isolada? Houve algum esforço para viabilizar ou facilitar a mudança?
    - R: Sim, foi identificado. Sim, está isolada. Sim, houve esforços para viabilizar a mudança: a partir da componentização, isolando conxões de serviços externos e outros serviços (mesmo internos) que podem sofrer com adições ou mudanças no requisito, como por exemplo a **validação de identificação acadêmica**.
- O tamanho de cada um dos "elementos" ou "partes" do design está adequado? Nem "grande" nem "pequeno" demais?
    - R: Em sua maioria sim. Há alguns elementos que poderiam ter um melhor detalhamento.
- Testes foram contemplados? Houve a necessidade de se organizar os "elementos" ou "partes" de tal forma a facilitar a execução de testes?
    - R: Não. Não foi pensando nos testes.
- Foi verificado se todos os "elementos" ou "partes" contribuem com a definição dos requisitos ou há algo que pode ser simplesmente removido?
    - R: Há elementos que podem ser removidos, que não fazem parte dos requisitos, como o validator em duas etapas.
