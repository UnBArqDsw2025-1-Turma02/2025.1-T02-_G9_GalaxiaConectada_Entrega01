# Benchmarking

## Sumário

* [Introdução](#Introdução)
* [Objetivos](#Objetivos)
* [Metodologia](#Metodologia)
* [Requisitos Elicitados](#Requisitos-Elicitados)
  * [Requisitos Funcionais](#Requisitos-Funcionais)
  * [Requisitos Não Funcionais](#Requisitos-Não-Funcionais)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)

## Introdução

O **benchmarking**, segundo o artigo [Benchmarking: muito além de uma simples comparação
](https://pontogp.wordpress.com/2008/12/24/benchmarking-muito-alem-de-uma-simples-comparacao/#:~:text=No%20final%20da%20d%C3%A9cada%20de%2070%2C%20quando,preciso%20dar%20um%20nome%20a%20esse%20processo.) [1](#ref1), 
 é uma metodologia que consiste na análise sistemática de produtos, de serviços ou práticas de outras organizações com o objetivo de identificar padrões de excelência e adaptá-los a um novo projeto. Com isso, segundo Camp (1989), considerado o "pai do benchmarking", trata-se de um processo contínuo de medição de serviços e práticas contra os concorrentes mais fortes. Portanto, em ambientes digitais, essa prática permite **observar tendências, inovações e estratégias que se destacam no mercado, servindo como fonte de inspiração e aprimoramento**

Neste contexto, foi realizado uma análise de plataformas e recursos online relevantes para o desenvolvimento do site **Galáxia Conectada.**
## Objetivos
O principal objetivo deste benchmarking é analisar criticamente plataformas educacionais, fóruns científicos, sistemas de jogos cognitivos e mecanismos de promoção online, a fim de identificar elementos, funcionalidades e abordagens que possam ser incorporados de forma estratégica ao desenvolvimento do site Galáxia Conectada.
Dessa forma, busca-se compreender como diferentes soluções digitais lidam com a apresentação de conteúdo científico, engajamento do usuário, personalização da experiência e usabilidade da interface.

## Metodologia
A metodologia adotada para este benchmarking consistiu na análise exploratória de diferentes tipos de plataformas, agrupadas por categorias, com o objetivo de identificar práticas e funcionalidades relevantes para o desenvolvimento do site **Galáxia Conectada**. 

Cada grupo de sites foi selecionado com base na sua afinidade com os aspectos essenciais do projeto como:

 - A apresentação de conteúdo científico;
 - A gamificação do aprendizado;
 - A discussão em comunidades online; 
 - A produção de vídeos educativos;
 - Uso de ferramentas tecnológicas de engajamento.

A seguir, os sites analisados foram divididos conforme seus respectivos focos:

<details>
  <summary size="20"><b>  Sites de Divulgação Científica</b></summary> 

- [Astronomia no Zênite](http://www.zenite.nu)
- [Céu Profundo](http://www.ceuprofundo.com)
- [NASA Science](https://science.nasa.gov)
- [EarthSky](https://earthsky.org)

</details>

<details>
  <summary size="20"><b>  Sites de Fóruns e Grupos de Discussão </b></summary> 
  
- [Reddit - r/astronomy](https://www.reddit.com/r/astronomy/)
- [Quora](https://www.quora.com/)
- [Stack Overflow (comunidades científicas e técnicas)](https://stackoverflow.com/)

</details>

<details>
  <summary size="20"><b>  Sites de Jogos Diários e Interativos</b></summary> 

- [Racha Cuca](https://rachacuca.com.br/)
- [Português Coruja](https://portuguescoruja.com.br/)
- [Bandle](https://bandle.app/)
- [NeuroNation](https://www.neuronation.com/)
- [Supera](https://www.metodosupera.com.br/)

</details>

<details>
  <summary size="20"><b>  Canais de Animações Educativas e Lúdicas </b></summary> 
  
- [Um Minuto no Museu](https://www.youtube.com/@umminutonomuseu)
- [De Onde Vem](https://www.youtube.com/@deondevem)
- [Minuto na Terra](https://www.youtube.com/@MinutoNaTerra)
- [Ciência Todo Dia](https://www.youtube.com/@CienciaTodoDia)
- [Manual do Mundo](https://www.youtube.com/@manualdomundo)
</details>

<details>
  <summary size="20"><b>  Plataformas Educacionais</b></summary> 

- [Khan Academy](https://pt.khanacademy.org/)
- [Duolingo](https://www.duolingo.com/)
- [Português Coruja](https://portuguescoruja.com.br/)
- [Udemy](https://www.udemy.com/)
- [Canal do Professor Boaro (YouTube)](https://www.youtube.com/@professorboaro)
- [Física e Vestibular](https://www.fisicaevestibular.com.br/)
</details>

<details>
  <summary size="20"><b>  Plataformas de Monitoramento de Promoções</b></summary> 

- [Cuponomia](https://www.cuponomia.com.br/)
- [Promobit](https://www.promobit.com.br/)
</details>


## Requisitos Elicitados
### Requisitos Funcionais

<details>
  <summary size="20"><b> Requisitos funcionais elicitados com o benchmarking </b></summary> 
  
| Código | Requisito Funcional | Objetivo |
|--------|---------------------|----------|
| RF01 | Permitir cadastro de usuários com e-mail e senha | Gerenciar contas e personalizar experiências |
| RF02 | Permitir login com autenticação segura | Garantir acesso autorizado ao conteúdo |
| RF03 | Exibir trilhas de aprendizagem por tema | Guiar o aprendizado do usuário |
| RF04 | Incluir jogos educativos interativos | Estimular o aprendizado lúdico |
| RF05 | Oferecer fórum para dúvidas e discussões | Promover troca de conhecimento entre usuários |
| RF06 | Permitir publicação de artigos e textos educativos | Compartilhar conteúdo com a comunidade |
| RF07 | Exibir agenda com eventos e datas astronômicas | Manter o público atualizado |
| RF08 | Incluir recursos para upload e visualização de fotos da comunidade | Estimular engajamento visual |
| RF09 | Permitir a avaliação de conteúdo por meio de curtidas/comentários | Promover interações |
| RF10 | Incluir sistema de perguntas e respostas por categorias | Facilitar localização de dúvidas/respostas |
| RF11 | Oferecer busca por palavras-chave em todo o site | Melhorar a navegação |
| RF12 | Categorizar conteúdos por nível (iniciante, intermediário, avançado) | Personalizar a experiência de aprendizado |
| RF13 | Permitir que administradores moderem o conteúdo publicado | Manter qualidade e segurança |
| RF14 | Incluir sistema de denúncias para moderação comunitária | Promover ambiente seguro |
| RF15 | Disponibilizar vídeos explicativos e tutoriais | Facilitar o entendimento de conteúdos complexos |
| RF16 | Exibir sugestões de leitura e links relacionados ao final dos artigos | Incentivar exploração de temas |
| RF17 | Integrar newsletter com atualizações regulares | Manter usuários engajados |
| RF18 | Permitir salvar conteúdos favoritos | Ajudar na organização pessoal de estudo |
| RF19 | Apresentar rankings ou conquistas baseadas em interações ou jogos | Estimular engajamento gamificado |
| RF20 | Exibir notícias científicas atualizadas | Informar sobre descobertas recentes |
| RF21 | Oferecer acesso a e-books e materiais complementares | Expandir as formas de aprendizado |
| RF22 | Integrar com redes sociais para compartilhamento de conteúdo | Aumentar o alcance da plataforma |
| RF23 | Permitir feedback dos usuários sobre recursos da plataforma | Coletar opiniões para melhorias |
| RF24 | Incluir recursos acessíveis (ex: alto contraste, leitor de tela) | Promover inclusão |
| RF25 | Disponibilizar simuladores e experiências interativas | Tornar o aprendizado mais prático |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

</details>

### Requisitos Não Funcionais

<details>
  <summary size="20"><b> Requisitos não funcionais elicitados com o benchmarking </b></summary>

| Código | Requisito Não Funcional | Objetivo |
|--------|-------------------------|----------|
| RNF01 | O site deve carregar em até 3 segundos em conexões padrão | Garantir desempenho e usabilidade |
| RNF02 | A disponibilidade da plataforma deve ser de 99% ao mês | Garantir confiabilidade |
| RNF03 | O sistema deve suportar pelo menos 10.000 usuários simultâneos | Escalabilidade |
| RNF04 | O login deve ser realizado em até 2 segundos | Eficiência |
| RNF05 | Os dados dos usuários devem ser criptografados | Garantir segurança |
| RNF06 | O fórum deve ser moderado com tempo de resposta de até 24h | Manter qualidade da comunidade |
| RNF07 | O sistema deve ser compatível com dispositivos móveis | Acessibilidade multiplataforma |
| RNF08 | A interface deve seguir diretrizes de usabilidade (ex: heurísticas de Nielsen) | Melhorar experiência do usuário |
| RNF09 | A navegação deve ser possível com teclado (acessibilidade) | Inclusão de usuários com deficiência |
| RNF10 | O sistema deve ser compatível com os principais navegadores | Ampliar acessibilidade |
| RNF11 | O tempo médio de resposta dos servidores deve ser inferior a 500ms | Desempenho |
| RNF12 | Os conteúdos devem estar disponíveis em pelo menos dois idiomas | Internacionalização |
| RNF13 | As páginas devem seguir normas de SEO | Facilitar localização em mecanismos de busca |
| RNF14 | Os conteúdos devem ser atualizados semanalmente | Garantir atualidade |
| RNF15 | Os dados devem ser armazenados em servidores com backup diário | Confiabilidade de dados |
| RNF16 | A estrutura de código deve seguir boas práticas (ex: Clean Code) | Manutenção |
| RNF17 | A plataforma deve ter tempo médio de recuperação de falhas inferior a 1h | Tolerância a falhas |
| RNF18 | Deve haver logs de erro para rastreabilidade de problemas | Suporte técnico |
| RNF19 | O sistema deve permitir integração com ferramentas analíticas (ex: Google Analytics) | Medição de uso |
| RNF20 | A taxa de erros em formulários deve ser inferior a 1% | Confiabilidade |
| RNF21 | A plataforma deve ser testada em resoluções de 1024x768 a 1920x1080 | Compatibilidade |
| RNF22 | Deve seguir as normas LGPD para coleta e uso de dados | Conformidade legal |
| RNF23 | O sistema deve permitir atualizações sem afetar o serviço | Manutenção contínua |
| RNF24 | O tempo de exibição de feedback visual após ações deve ser inferior a 1s | Usabilidade |
| RNF25 | O conteúdo multimídia deve estar otimizado para carregamento em conexões 4G | Acessibilidade de mídia |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

</details>

## Bibliografia

<a name="ref1"></a>  
[1] IATA, Cristiane. Benchmarking: muito além de uma simples comparação. Revista Benchmarking, edição 1, dez. 2008. Disponível em: https://pontogp.wordpress.com/2008/12/24/benchmarking-muito-alem-de-uma-simples-comparacao. Acesso em 6 de abril de 2025.
