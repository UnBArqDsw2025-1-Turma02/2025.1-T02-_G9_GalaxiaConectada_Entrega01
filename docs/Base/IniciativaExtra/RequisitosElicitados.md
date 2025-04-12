# Requisitos Elicitados

## Sumário

* [Introdução](#Introdução)
* [Requisitos Funcionais](#Requisitos-Funcionais)
* [Requisitos Não Funcionais](#Requisitos-Não-Funcionais)
* [Conclusão](#Conclusão)
* [Histórico de versão](#Histórico-de-versão)

## Introdução

O levantamento e a organização dos requisitos são etapas fundamentais no desenvolvimento do projeto Galáxia Conectada. Com isso, este documento apresenta de forma estruturada os requisitos funcionais e não funcionais que norteiam a construção da plataforma, reunidos a partir de brainstorming, análises de benchmarking com sites e plataformas semelhantes, e das necessidades específicas do público-alvo.

## Requisitos Funcionais



###  Tabela 1: Geral de Requisitos Funcionais

| Código | Requisito Funcional                                                                                 | Rastreabilidade                                                                                      |
|--------|------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| RF01   | Oferecer trilhas de aprendizado organizadas por tema, nível e categoria.                            | Brainstorming, Plataformas Educacionais, Benchmarking Divulgação Científica                          |
| RF02   | Exibir aulas, artigos, vídeos e testes integrados às trilhas.                                       | Brainstorming, Animações, Plataformas Educacionais                                                   |
| RF03   | Apresentar trilhas como missões espaciais lúdicas.                                                  | Brainstorming                                                                                         |
| RF04   | Armazenar o progresso dos usuários e exibir certificados de conclusão.                              | Brainstorming, Plataformas Educacionais                                                               |
| RF05   | Atribuir recompensas (XP, moedas, conquistas) por participação e progresso.                         | Brainstorming, Jogos                                                                                  |
| RF06   | Fornecer feedback imediato em quizzes, exercícios e jogos.                                          | Brainstorming, Jogos, Plataformas Educacionais                                                        |
| RF07   | Exibir rankings e destaques entre usuários, com sistema de reputação.                               | Brainstorming, Fóruns, Jogos                                                                          |
| RF08   | Oferecer jogos educativos e interativos com diferentes níveis, temas e formatos.                    | Brainstorming, Jogos                                                                                  |
| RF09   | Permitir criação de tópicos e postagens no fórum, com comentários, tags e votos.                    | Brainstorming, Fóruns                                                                                 |
| RF10   | Disponibilizar busca eficiente por conteúdos (trilhas, fóruns, artigos, jogos etc).                 | Divulgação Científica, Fóruns, Plataformas Educacionais                                              |
| RF11   | Exibir calendário de eventos astronômicos com filtros e notificações.                               | Brainstorming, Divulgação Científica                                                                  |
| RF12   | Enviar notificações personalizadas sobre eventos e promoções.                                       | Brainstorming, Promoções                                                                             |
| RF13   | Disponibilizar blog com artigos, glossário e filtros por categorias e níveis.                       | Brainstorming, Divulgação Científica                                                                  |
| RF14   | Atualizar regularmente publicações e notícias científicas.                                          | Brainstorming, Divulgação Científica                                                                  |
| RF15   | Permitir que usuários enviem conteúdos (fotos, textos, sugestões).                                  | Divulgação Científica                                                                                 |
| RF16   | Recomendar conteúdos com base no histórico e perfil do usuário.                                     | Jogos, Plataformas Educacionais, Promoções                                                            |
| RF17   | Integrar vídeos educativos de criadores parceiros à plataforma.                                     | Animações                                                                                             |
| RF18   | Incluir roteiros de experimentos práticos para casa e indicações de apps de astronomia.             | Brainstorming                                                                                         |
| RF19   | Exibir promoções organizadas por categoria com filtros e favoritos.                                 | Promoções                                                                                             |
| RF20   | Notificar promoções e novidades por bot ou push.                                                    | Brainstorming, Promoções                                                                             |
| RF21   | Disponibilizar jogos e quizzes com tempo limitado.                                                  | Brainstorming                                                                                         |
| RF22   | Permitir acesso diário a novos desafios e atividades gamificadas.                                   | Jogos                                                                                                 |
| RF23   | Exibir perfil de usuário com histórico de participação, reputação e conquistas.                     | Fóruns, Jogos                                                                                         |
| RF24   | Permitir comentários e interações nos conteúdos da plataforma (aulas, artigos, vídeos etc.).        | Plataformas Educacionais                                                                             |
| RF25   | Apresentar seção com conteúdos populares ou mais votados.                                           | Fóruns                                                                                                |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.


##  Requisitos Não Funcionais

###  Tabela 2: Geral de Requisitos Não Funcionais

| Código | Requisito Não Funcional                                                                 | Objetivo                                                                                     | Rastreabilidade / Origem                                             |
|--------|------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|----------------------------------------------------------------------|
| RNF01  | A plataforma deve ser responsiva e compatível com dispositivos móveis, tablets e desktops.| Garantir acessibilidade e boa usabilidade em diferentes telas.                             | Brainstorming, Animações, Divulgação Científica                     |
| RNF02  | O tempo de resposta das páginas e conteúdos deve ser inferior a 3 segundos.              | Proporcionar fluidez e boa experiência de navegação.                                         | Brainstorming, Animações, Educacionais                             |
| RNF03  | O sistema deve seguir diretrizes de acessibilidade (WCAG 2.1, contraste, leitores de tela, teclado). | Incluir pessoas com deficiência e neurodivergência.                                | Brainstorming, Jogos, Fóruns, Divulgação Científica                |
| RNF04  | Os dados dos usuários devem ser armazenados com segurança, incluindo criptografia e backup. | Proteger informações pessoais e de progresso.                                             | Brainstorming, Jogos, Educacionais                                 |
| RNF05  | O sistema deve ter disponibilidade mínima de 99,5% e suportar escalabilidade.            | Evitar interrupções e manter estabilidade com aumento de usuários.                          | Brainstorming                                                      |
| RNF06  | A interface deve ser clara, intuitiva e com linguagem acessível.                         | Facilitar o uso por iniciantes e melhorar a navegação geral.                                | Brainstorming, Divulgação Científica                               |
| RNF07  | A plataforma deve suportar múltiplos idiomas e adaptar-se ao idioma do usuário.          | Ampliar o alcance internacional e a inclusão.                                                | Fóruns, Animações                                                  |
| RNF08  | Os conteúdos devem ser organizados por níveis e com fácil navegação entre seções.        | Apoiar o aprendizado progressivo e a orientação do usuário.                                  | Divulgação Científica, Animações                                   |
| RNF09  | O sistema deve ser compatível com navegadores modernos (Chrome, Firefox, Edge, Safari). | Garantir o acesso por diferentes perfis de usuários.                                         | Brainstorming                                                      |
| RNF10  | A plataforma deve ser otimizada para mecanismos de busca (SEO).                          | Aumentar a visibilidade e atrair novos usuários.                                             | Divulgação Científica, Fóruns                                     |
| RNF11  | Recursos multimídia (como vídeos) devem carregar com rapidez e ter suporte a legendas.  | Melhorar a experiência de consumo e a acessibilidade.                                        | Animações, Educacionais                                            |
| RNF12  | O sistema deve permitir atualizações frequentes sem comprometer o funcionamento.         | Garantir evolução contínua sem prejudicar a experiência do usuário.                          | Brainstorming, Promoções                                           |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

## Conclusão

A consolidação dos requisitos funcionais e não funcionais permite estabelecer uma base um pouco mais sólida para o desenvolvimento da Galáxia Conectada.

| Versão | Alteração | Responsável | Data |
| - | - | - | - |
| 1.0 | Elaboração do documento| Larissa Stéfane | 11/04/2024 |

