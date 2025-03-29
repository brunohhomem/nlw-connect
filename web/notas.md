# Notas

1 - Separar um trecho de código em um componente React faz sentido quando ele contém lógica reutilizável, melhora a organização do código ou otimiza a renderização.

2 - "use client" é necessário para componentes que exigem interatividade, como manipulação de eventos, estados (useState), efeitos colaterais (useEffect) e qualquer lógica que dependa do ambiente do navegador.

3 - Evitar o envio de JavaScript desnecessário ao cliente melhora a performance da aplicação. Componentes que não precisam de interatividade (apenas renderizam HTML e CSS) podem ser componentes server-side, evitando o carregamento desnecessário de JS no navegador.

4 - Nem todo componente que usa JS precisa ser client-side. Se o código executa apenas no servidor (como chamadas ao banco de dados ou carregamento de dados via getServerSideProps no Next.js), ele deve permanecer um Server Component.
