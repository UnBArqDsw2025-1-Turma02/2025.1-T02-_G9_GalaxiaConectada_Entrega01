# Benchmarking em Relação a Sites de Jogos

## Sumário

* [Racha-Cuca](#Racha-Cuca)
* [Português-Coruja](#Português-Coruja)
* [Bandle](#Bandle)
* [NeuroNation](#NeuroNation)
* [Supera](#Português-Coruja)
* [Lições para o projeto Galáxia Conectada](#Lições-para-o-projeto-Galáxia-Conectada)
* [Requisitos Elicitados](#Requisitos-Elicitados)
  * [Requisitos Funcionais](#Requisitos-Funcionais)
  * [Requisitos Não-Funcionais](#Requisitos-Não-Funcionais)


## [Racha Cuca](https://rachacuca.com.br/)

### 🎯 Estrutura e Navegação
- Site voltado para jogos de lógica, enigmas, quebra-cabeças, testes e desafios mentais.
- Menus claros por categoria: jogos de lógica, testes, enigmas, palavras cruzadas.
- Design simples, leve e funcional, com foco no conteúdo.

### 🎮 Elementos de Engajamento
- Atualização frequente de jogos e desafios.
- Jogos diários com destaque na página inicial.
- Classificação por dificuldade e tipo.
- Rankings e possibilidade de ver resultados corretos após jogar.

### ✅ Pontos Positivos
- Grande variedade de jogos e exercícios mentais.
- Interface acessível e leve.
- Estimula o raciocínio e o pensamento lógico de forma divertida.

### ❌ Pontos Negativos
- Visual pouco moderno.

## Português Coruja](https://portuguescoruja.com.br/)

### 🎯 Estrutura e Navegação
- Plataforma voltada para o ensino da língua portuguesa, com foco em concursos e reforço escolar.
- Categorias organizadas por tema gramatical (crase, pontuação, regência etc.).
- Interface limpa, com muitos quizzes e desafios interativos.

### 🎮 Elementos de Engajamento
- Jogos em forma de quiz com correção imediata.
- Explicações gramaticais para cada questão.
- Seção de ranking com desafios temporais.

### ✅ Pontos Positivos
- Ótimo para quem está se preparando para concursos.
- Mistura de jogo e aprendizado com explicações didáticas.
- Organização por temas facilita o estudo direcionado.

### ❌ Pontos Negativos
- Experiência menos lúdica, mais focada em testes.

## [Bandle](https://bandle.app/)

### 🎯 Estrutura e Navegação
- Jogo de adivinhação de bandas/músicas no estilo Wordle.
- Interface minimalista e moderna.
- Navegação extremamente simples: foco direto no jogo do dia.

### 🎮 Elementos de Engajamento
- Um desafio novo por dia.
- Compartilhamento de resultados nas redes sociais.
- Histórico de acertos.
- Sistema de dicas progressivas.

### ✅ Pontos Positivos
- Simples, rápido e envolvente.
- Elemento diário mantém usuários retornando.
- Boa integração com cultura pop e música.

## 🧠 [NeuroNation](https://www.neuronation.com/)

### 🎯 Estrutura e Navegação
- Plataforma focada em treino cerebral com base científica.
- Interface moderna, com design gamificado e intuitivo.
- Área de login com perfil, progresso e plano de treino personalizado.

### 🎮 Elementos de Engajamento
- Programas personalizados de treino.
- Jogos variados focando memória, atenção, lógica e velocidade.
- Estatísticas de desempenho, progresso e comparações com outros usuários.

### ✅ Pontos Positivos
- Fortemente baseado em ciência e neuroeducação.
- Experiência personalizada e motivadora.
- Interface envolvente e adaptável ao usuário.

### ❌ Pontos Negativos
- Muitas funcionalidades estão atrás de paywall (plano premium).

## [Supera](https://www.metodosupera.com.br/)

### 🎯 Estrutura e Navegação
- Site institucional de uma franquia de ginástica para o cérebro.
- Apresenta atividades, agenda de eventos, localização de unidades, blog e vídeos.

### 🎮 Elementos de Engajamento
- Conteúdo informativo e vídeos demonstrativos de atividades mentais.
- Blog com curiosidades e dicas de estímulo cerebral.

### ✅ Pontos Positivos
- Conteúdo educativo e institucional bem estruturado.

## 🧠 Lições para o projeto **Galáxia Conectada**
- Ter um **jogo ou desafio diário** (como Bandle ou Racha Cuca) é excelente para fidelizar usuários.
- Plataformas como **NeuroNation** mostram a importância de **personalização, progresso e feedback**.
- O modelo do **Português Coruja** pode inspirar quizzes educativos com correções e explicações imediatas.
- Um **ambiente leve e visualmente atrativo**, mesmo com foco educacional, ajuda no engajamento (aprendizado lúdico).
- Considerar um **ranking comunitário**, **perfil de usuário** e **recompensas simbólicas** (badges, estrelas) pode fortalecer o envolvimento com o conteúdo.

## Requisitos Elicitados

### Requisitos Funcionais 

| Código | Requisito Funcional                                                                     | Objetivo                                                                                       | Origem                     |
|--------|------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|----------------------------|
| RF01   | O sistema deve disponibilizar jogos interativos de lógica, memória e conhecimentos.     | Promover o aprendizado lúdico e estimular o raciocínio.                                       | Racha Cuca / NeuroNation   |
| RF02   | O sistema deve permitir acesso diário a novos desafios ou jogos.                        | Estimular a frequência de uso e senso de progresso contínuo.                                  | Bandle / Racha Cuca        |
| RF03   | O sistema deve oferecer jogos com diferentes níveis de dificuldade.                     | Atender usuários iniciantes e avançados, promovendo progressão.                               | NeuroNation / Supera       |
| RF04   | O sistema deve permitir ao usuário acompanhar seu desempenho (pontuação, progresso etc).| Fornecer feedback e senso de evolução no aprendizado.                                          | NeuroNation / Supera       |
| RF05   | O sistema deve exibir rankings ou conquistas para motivação.                            | Criar competitividade saudável e incentivo ao retorno.                                         | Bandle / Supera            |
| RF06   | O sistema deve oferecer sugestões de jogos com base no histórico do usuário.            | Personalizar a experiência conforme preferências individuais.                                 | NeuroNation                |
| RF07   | O sistema deve permitir que os jogos sejam classificados por categoria ou habilidade.   | Facilitar a busca por jogos relacionados a interesses específicos.                            | Racha Cuca / Português Coruja |
| RF08   | O sistema deve disponibilizar jogos em diferentes formatos (texto, áudio, visual).      | Atender diferentes estilos de aprendizagem e acessibilidade.                                  | Português Coruja / Supera  |
| RF09   | O sistema deve permitir que usuários salvem seus jogos favoritos ou desafios preferidos.| Oferecer acesso rápido a conteúdos que o usuário goste de repetir.                            | Racha Cuca / Bandle        |
| RF10   | O sistema deve oferecer desafios temáticos ou sazonais.                                 | Engajar o público com conteúdo atualizado e relevante ao momento.                             | Racha Cuca / Bandle        |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

### Requisitos Não Funcionais 

| Código | Requisito Não Funcional                                                               | Objetivo                                                                                 | Origem                    |
|--------|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|---------------------------|
| RNF01  | O sistema deve ser responsivo e acessível em dispositivos móveis e tablets.            | Permitir acesso em diferentes plataformas.                                               | Todos os sites            |
| RNF02  | Os jogos devem carregar em até 3 segundos após o clique do usuário.                    | Garantir fluidez e reduzir frustrações com lentidão.                                     | Bandle / NeuroNation      |
| RNF03  | O sistema deve ser compatível com navegadores modernos (Chrome, Firefox, etc.).        | Ampliar o alcance e acessibilidade da plataforma.                                        | Todos os sites            |
| RNF04  | O sistema deve seguir diretrizes de acessibilidade (ex: contraste, navegação por teclado). | Incluir usuários com deficiência.                                                   | Português Coruja / Supera |
| RNF05  | A plataforma deve armazenar os dados de progresso do usuário com segurança.            | Proteger informações pessoais e evitar perda de progresso.                               | NeuroNation / Supera      |
| RNF06  | O sistema deve manter taxa de disponibilidade (uptime) superior a 99%.                 | Evitar indisponibilidades e manter confiança dos usuários.                               | NeuroNation / Racha Cuca  |
| RNF07  | O sistema deve apresentar interface intuitiva e centrada no jogo.                      | Facilitar a navegação e foco nos desafios.                                               | Bandle / Português Coruja |
| RNF08  | O conteúdo deve ser otimizado para SEO(Search Engine Optimization).                                                 | Aumentar visibilidade em buscadores e atrair novos usuários.                             | Racha Cuca / Português Coruja |
| RNF09  | A plataforma deve oferecer suporte multilíngue ou adaptável à linguagem do navegador.  | Ampliar o alcance internacional e inclusão linguística.                                  | NeuroNation               |
| RNF10  | O sistema deve registrar estatísticas de uso para análise e melhoria contínua.         | Permitir melhorias baseadas em dados reais de uso.                                       | Supera / NeuroNation      |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>


## Bibliografia

[1] BANDLE. Bandle. Disponível em: <https://bandle.app/>. Acesso em: 8 abr. 2025.

[2] NEURONATION. NeuroNation. Disponível em: <https://www.neuronation.com/>. Acesso em: 8 abr. 2025.

[3] PORTUGUÊS CORUJA. Português Coruja. Disponível em: <https://portuguescoruja.com.br/>. Acesso em: 8 abr. 2025.

[4] RACHA CUCA. Racha Cuca. Disponível em: <https://rachacuca.com.br/>. Acesso em: 8 abr. 2025.

[5] SUPERA. Supera. Disponível em: <https://www.metodosupera.com.br/>. Acesso em: 8 abr. 2025.
