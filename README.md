# VUE.JS
- VUEJS FOCA MUITO EM REATIVIDADE,
BASICAMENTE EM UM ARRAY DE TODOS, ELE FARÁ TODA DE FORMA MAIS SIMPLES TODA MÁGICA DO REACTJS (QUE ROLA DE BAIXO DOS PANOS):
```
const novoTodos = []
this.Todos = novosTodos
```
- AMBOS POSSUEM LAZY LOADING
- AMBOS USAM VIRTUAL DOM
- USA TEMPLATE COM DECLARAÇÃO DE RENDERIZAÇÃO (REATIVIDADE), MAS TAMBÉM PODE USAR JSX.
- CURVA DE APRENDIZAGEM BEM MENOR.
- DOCUMENTAÇÃO COM COMPARAÇÃO AO REACTJS - ESCRITO POR EVAN YOU (CRIADOR VUEJS) COM COOPERAÇÃO COM DAN AMBROMOV (EQUIPE DO REACTJS)
- BOA DOCUMENTAÇÃO EM PT-BR
- JÁ POSSUI ROTEAMENTO NATIVO. (VUE ROUTER, SERVER-SIDE ROUTING)
- DOCUMENTAÇÃO MUITO BOA DO VUEX
- Style Guide NA DOCUMENTAÇÃO, +1 VEZ DE COMO UTILIZAR BOAS PRÁTICAS NO VUE3!
- CLASS AND STYLES BIDINGS
- UTILIZA VUEX, REACTIVE, PARA TRABALHAR COM ESTADO GLOBAIS. OBS: *NÃO PRECISA UTILIAZAR MAIS UMA LIB PARA FAZER CHAMADAS ASYNC, O PRÓPRIO VUEX JÁ FAZ ISSO.*


# REACT.JS
- REACT FOCA MUITO EM IMUTABILIDADE
```
const [counter, setCounter] = useState([])
setState(prevCounter => prevCounter + 1)
```
- REACTJS TEM MAIS PROGRAMAÇÃO FUNCIONAL QUE O VUEJS.
- COMUNIDADE MUITO MAIOR.
- SINTAXE JSX (BOM OU RUIM)
- AMBOS POSSUEM LAZY LOADING
- AMBOS USAM VIRTUAL DOM
- USA JSX
- MUITOS PACKAGES
- NÃO POSSUI GERENCIAMENTO DE ESTADO GLOBAL.
- UPGRADES DE VERSÕES GERALMENTE NÃO QUEBRA NADA.
- UTILIZA REDUX, CONTEXT-API P/ TRABALHAR COM ESTADOS GLOBAIS. OBS: *UTILIZA REDUX SAGA P/ PODER FAZER CHAMADAS ASYNC (UMA LIB A MAIS)*

# GERAL
- https://www.npmtrends.com/react-vs-vue
- AMBOS TEM MESMO NÍVEL DE PERFORMANCE.

# SEGUNDO O REPORTS DO HACKER RANK (VUEJS):
- O VUEJS ESTÃO EM CONSTANTE CRESCIMENTO, SUBINDO UMA POSIÇÃO POR ANO DESDE 2018, INCLUSIVE EM 2020 PASSOU RUBY ON RAILS INCLUSIVE (https://research.hackerrank.com/developer-skills/2020
- 23% DOS DESENVOLVEDORES QUEREM APRENDER [VUEJS], ESTÃO APENAS ATRÁS DE [DJANGO], [ANGULARJS] E [REACTJS].

# SEGUNDO O STACKOVERFLOW:
- (ENTRE OS MAIS UTILIZADOS) VUEJS EM 7º, REACTJS EM 2º;

- (ENTRE OS MAIS AMADOS) VUEJS EM 3º, REACTJS EM 2º

- (ENTRE OS MAIS TEMIDO) VUEJS EM 14º, REACTJS EM 15º

- (ENTRE OS MAIS PROCURADOS) REACTJS 1º, VUEJS EM 2º

# SEGUNDO A MONTERAIL SOBRE VUEJS:
- INCERTERZA SOBRE O FUTURO, DE 2017 A 2019 DIMINUIU DE 45% PARA 36%
- DÚVIDAS SOBRE A ESCABILIDADE DE 2017 A 2019 AUMENTOU DE 15% PARA 19%.
- FÁCIL DE INTEGRAR DE 2017 A 2019 DIMINUIU DE 81% ÁRA 76%
- BOA DOCUMENTAÇÃO ENTRE 2017-2019 AUMENTOU DE 45% PARA 76%
- PERFORMANCE ENTRE 2017-2019 DIMINUIU DE 56% PARA 51%
- PROGRESSIVIDADE ENTRE 2017-2019 AUMENTOU DE 49% PARA 59%
- AUMENTO DO INVOLVIMENTO DA COMUNIDADE ENTRE 2017-2019 AUMENTOU DE 29% PARA 36%
- AOS ENTREVISTADOS, QUEM JÁ USOU VUEJS, 92,3% DISSERAM QUE É MUITO E MUITO ALTA A PROBABILIDADE DE USAR O VUEJS NOVAMENTE EM OUTRO PROJETO.
- AOS ENTREVISTADOS 87% UTILIZAM VUEX COMO GLOBAL STATE MANAGEMENT.


# SEGUNDO A MONTERAIL SOBRE REACTJS:
- Como o React foi criado para projetos da Web de grande escala, escolher para aplicativos pequenos e simples pode ser um exagero. Embora exija muito código clichê apenas para configurar um projeto de trabalho, a arquitetura do React acaba valendo a pena no longo prazo.


# PROJETOS FEITOS EM VUE.JS
- Euronews
- Behance
- Alibaba *****
- Trustpilot
- Vice

# PROJETOS FEITOS EM REACTJS
- Airbnb
- Disqus
- PayPal
- The New York Times
- Netflix

# SEGUNDO UM ENGENHEIRO DE SOFTWARES QUE TRABALHOU COM REACTJS POR 5 ANOS:

### Filosofias diferentes

- VueJS utiliza (Single File Components, html, js, css [acoplados] em um único arquivo).
- ReactJS realiza o "html", js dentro, porém o css fora.
- Qualquer app grandes e complexos exigem um controle de estado e uso de rotas, o vuejs oferece suporte oficial para ambos (vue router, vuex), enquanto o ReactJS deixa o suporte a comunidade.


### Interesse ao longo do tempo segundo (google trends)
- https://trends.google.com/trends/explore?cat=31&date=today%2012-m,today%2012-m,today%2012-m&geo=,,&q=Vue%20jobs,React%20jobs,Angular%20jobs



# [Angular]	[React]	[Vue] - Github status
- Watchers	3.2k | 6.7k	| 6.2k
- Stars	62k	| 151k | 166k
- Forks	16.9k | 29.4k | 25.2k
- Contributors 1,129 | 1,390 | 293


# COMPARAÇÃO SEGUNDO O SITE DO VUEJS
- ReactJS supera VueJS por exemplo na riqueza de seu ecossitema e na abundância d renderizadores personalizados.
- Tanto React quanto Vue são excepcionalmente e similarmente rápidos, então desempenho não deve ser um fator decisivo para uma escolha entre eles. Para métricas específicas, pode dar uma olhada neste comparativo independente [https://stefankrause.net/js-frameworks-benchmark8/table.html]

- No React, quando o estado de um componente muda, ele aciona também a renderização de toda a árvore de componentes filhos. Para evitar renderizações desnecessárias de componentes filhos, você precisa utilizar um PureComponent ou implementar shouldComponentUpdate sempre que puder. Você também pode precisar utilizar estruturas de dados imutáveis para tornar suas mudanças de estado mais amigáveis a otimizações. Entretanto, em certos casos pode não ser possível se apoiar nestas otimizações, pois PureComponent e shouldComponentUpdate assumem que o resultado da renderização de toda a árvore interna sempre é determinado pelas propriedades do componente corrente. Se este não for seu caso, tais otimizações podem levar a estado inconsistente no DOM.
- No Vue, as dependências de um componente são automaticamente observadas durante sua renderização, desta forma o sistema sabe precisamente quais componentes precisam ser renderizados quando o estado muda. Pode-se considerar que cada componente já tem shouldComponentUpdate automaticamente implementado para você, e sem os problemas com componentes filhos.
- De forma geral, isto remove a necessidade de conhecimento de toda uma gama de otimizações de desempenho das responsabilidades do desenvolvedor, permitindo-o focar mais em construir a aplicação em si enquanto ela cresce.