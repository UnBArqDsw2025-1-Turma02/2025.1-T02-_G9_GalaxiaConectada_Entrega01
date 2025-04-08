# Benchmarking em Relação a Sites de Fóruns e Grupos de Discussão

## Sumário

* [Introdução](#Introdução)
* [Reddit – r/astronomy](#Reddit-–-r/astronomy)
* [Quora](#Quora)
* [Stack Overflow (modelo para fóruns técnicos)](#Stack-Overflow-(modelo-para-fóruns-técnicos))
* [Lições para o projeto Galáxia Conectada](#Lições-para-o-projeto-Galáxia-Conectada)
* [Requisitos Elicitados](#Requisitos-Elicitados)
  * [Requisitos Funcionais](#Requisitos-Funcionais)
  * [Requisitos Não-Funcionais](#Requisitos-Não-Funcionais)

## [Reddit – r/astronomy](https://www.reddit.com/r/astronomy/)

### 🧩 Estrutura e Navegação
- Plataforma baseada em comunidades (subreddits) temáticas.
- Interface com postagens em estilo de feed contínuo e votação por relevância.
- Possui marcadores de postagens (como "Discussion", "Astrophotography", etc.) para ajudar na organização do conteúdo.
- Sistema de comentários em árvore, favorecendo debates e respostas diretas.

### 🤝 Dinâmicas de Interação
- Muito centrado na comunidade: usuários compartilham imagens, dúvidas, experiências e artigos.
- Curtidas (upvotes) e votos negativos ajudam a destacar o que é mais relevante.
- Postagens populares ganham destaque no topo, o que motiva usuários a contribuírem com qualidade.

### 🛡️ Mecanismos de Moderação
- Moderadores voluntários controlam o conteúdo com base em regras claras listadas na comunidade.
- Regras comuns incluem: proibição de spam, civilidade obrigatória, incentivo a conteúdo original e explicações junto aos links.
- Sistema de denúncias por parte da comunidade.

### ✅ Pontos Positivos
- Forte senso de comunidade e participação.
- Conteúdo visual bem valorizado.
- Sistema de votação ajuda a destacar tópicos úteis e populares.

### ❌ Pontos Negativos
- Estrutura pode parecer caótica para novos usuários.
- Discussões podem se perder em meio a muitos comentários ou tópicos irrelevantes.

## [Quora](https://www.quora.com/)

### 🧩 Estrutura e Navegação
- Plataforma baseada em perguntas e respostas organizadas por temas.
- Interface limpa, com buscas fáceis e sugestões automáticas.
- Cada pergunta pode ter múltiplas respostas, votadas pela comunidade.

### 🤝 Dinâmicas de Interação
- Foco na explicação e no compartilhamento de conhecimento.
- As respostas são geralmente mais longas, elaboradas e opinativas.
- Possui seguidores de temas e autores, o que cria microcomunidades.

### 🛡️ Mecanismos de Moderação
- Moderação híbrida (equipe oficial + denúncias da comunidade).
- Políticas contra spam, desinformação e violação de direitos autorais.
- Algumas respostas são verificadas por especialistas ou usuários verificados.

### ✅ Pontos Positivos
- Respostas profundas e bem argumentadas.
- Facilidade para busca e navegação por temas.
- Ótimo para aprendizado e exploração de ideias.

### ❌ Pontos Negativos
- Algumas respostas podem ser muito opinativas e pouco fundamentadas.
- Nem sempre há consenso sobre as respostas corretas.
- Requer moderação ativa para evitar duplicações e discussões dispersas.

## [Stack Overflow](https://stackoverflow.com/) (modelo para fóruns técnicos)

### 🧩 Estrutura e Navegação
- Estrutura de perguntas e respostas técnicas, com foco em precisão e clareza.
- Sistema de tags para categorizar temas.
- Respostas são votadas e a “melhor resposta” pode ser destacada pelo autor da pergunta.

### 🤝 Dinâmicas de Interação
- Dinâmica altamente voltada à resolução de problemas.
- Interações rápidas e objetivas.

### 🛡️ Mecanismos de Moderação
- Sistema de reputação para usuários: quanto mais útil, maior o nível de acesso.
- Moderadores da comunidade + sistema de denúncia.
- Regras rigorosas para manter foco e evitar perguntas duplicadas ou mal formuladas.

### ✅ Pontos Positivos
- Foco técnico com alta qualidade nas respostas.
- Estrutura clara e objetiva.
- Sistema de reputação que estimula boas contribuições.

### ❌ Pontos Negativos
- Ambiente pouco acolhedor para iniciantes (respostas ríspidas não são incomuns).
- Exige perguntas muito bem formuladas — senão, são rapidamente negativadas.
- Pouco espaço para discussão aberta ou informalidades.

## 🧠 Lições para o projeto **Galáxia Conectada**

-  **comunidade e compartilhamento**: adotar um modelo semelhante ao **Reddit**, com áreas visuais, categorias abertas e incentivo à participação.
- **Educação, perguntas e respostas**: o modelo **Quora** oferece maior profundidade e curadoria de conhecimento.
- Para uma área de **resolução técnica ou científica** (como perguntas sobre observação, instrumentos de astronomia como telescópios, métodos): o estilo **Stack Overflow**.
- O**sistema de moderação** e **regras claras de participação** são fundamentais para manter um ambiente produtivo e saudável.

## Requisitos Elicitados

### Requisitos Funcionais 

| Código | Requisito Funcional                                                                 | Objetivo                                                                                   | Origem                 |
|--------|--------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|-------------------------|
| RF01   | O sistema deve permitir que os usuários publiquem perguntas e respostas.            | Fomentar o aprendizado colaborativo e resolução de dúvidas.                               | Quora / Stack Overflow  |
| RF02   | O sistema deve permitir a publicação de postagens abertas (sem pergunta).           | Estimular o compartilhamento livre de experiências e curiosidades.                        | Reddit                  |
| RF03   | O sistema deve permitir comentários em postagens e respostas.                       | Viabilizar conversas e aprofundamento das discussões.                                     | Todos os sites          |
| RF04   | O sistema deve oferecer uma área de destaques e conteúdos populares.                | Dar visibilidade ao conteúdo mais relevante para a comunidade.                            | Reddit / Stack Overflow |
| RF05   | O sistema deve permitir o uso de votos positivos e negativos em postagens.          | Destacar conteúdo útil e ocultar contribuições de baixa qualidade.                        | Reddit / Stack Overflow |
| RF06   | O sistema deve permitir categorização e tags nos tópicos e discussões.              | Facilitar a organização do conteúdo e a busca temática.                                   | Stack Overflow / Quora  |
| RF07   | O sistema deve ter perfis de usuário com reputação ou histórico de participação.    | Estimular contribuições qualificadas e engajamento contínuo.                              | Stack Overflow / Quora  |
| RF08   | O sistema deve disponibilizar um mecanismo de busca interno eficiente.              | Ajudar os usuários a encontrar tópicos específicos de forma rápida.                       | Todos os sites          |
| RF09   | O sistema deve permitir a inserção de mídia (imagens, links etc.) nas postagens.    | Enriquecer o conteúdo com recursos visuais e informativos.                                | Reddit / Quora          |
| RF10   | O sistema deve permitir a marcação de respostas como “resposta aceita” ou “solução”.| Indicar a resolução de problemas ou dúvidas.                                              | Stack Overflow          |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

### Requisitos Não Funcionais 

| Código | Requisito Não Funcional                                                             | Objetivo                                                                           | Origem                 |
|--------|--------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|------------------------|
| RNF01  | O sistema deve ser responsivo e adaptável a diferentes tamanhos de tela.            | Permitir o uso confortável em desktop e mobile.                                   | Todos os sites         |
| RNF02  | O tempo de resposta do servidor deve ser inferior a 2 segundos por requisição.      | Garantir uma navegação fluida e rápida.                                           | Stack Overflow         |
| RNF03  | O sistema deve ter mecanismos de moderação, como denúncias e aprovação de conteúdo. | Manter um ambiente seguro, focado e com conteúdo relevante.                       | Reddit / Stack Overflow|
| RNF04  | O sistema deve exibir conteúdo hierarquicamente organizado (por tópicos e tags).    | Facilitar a navegação e localização de discussões.                                | Stack Overflow         |
| RNF05  | O sistema deve ser acessível, seguindo padrões como WCAG 2.1.                       | Incluir usuários com deficiência.                                                 | Quora / Stack Overflow |
| RNF06  | O sistema deve suportar múltiplos idiomas ou adaptar-se a idioma padrão do usuário. | Ampliar o alcance da plataforma internacionalmente.                               | Quora                  |
| RNF07  | O layout deve seguir um design limpo e centrado no conteúdo.                        | Priorizar a leitura e interação com o conteúdo postado.                           | Reddit / Quora         |
| RNF08  | A plataforma deve garantir estabilidade com uptime superior a 99%.                  | Evitar quedas ou interrupções frequentes no serviço.                              | Stack Overflow         |
| RNF09  | O sistema deve notificar os usuários sobre interações em seus posts.                | Incentivar o retorno à plataforma e engajamento contínuo.                         | Quora / Reddit         |
| RNF10  | O conteúdo deve ser indexado para aparecer em mecanismos de busca externos (SEO).   | Aumentar a visibilidade e atrair novos usuários por meio do Google e similares.   | Quora / Stack Overflow |



