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
  
| Código | Requisito Funcional                                                                 | Rastreabilidade                             |
|--------|--------------------------------------------------------------------------------------|---------------------------------------------|
| RF01   | Disponibilizar vídeos educativos organizados por tema, faixa etária e complexidade. | Animações                                   |
| RF02   | Integrar vídeos e recursos multimídia (áudio, imagem, podcasts) às trilhas de aprendizado. | Animações, Divulgação Científica, Plataformas educacionais |
| RF03   | Utilizar linguagem acessível e lúdica nos conteúdos audiovisuais.                   | Animações                                   |
| RF04   | Permitir visualização direta de vídeos e conteúdos na plataforma.                   | Animações, Divulgação Científica            |
| RF05   | Exibir descrições, links úteis e informações complementares aos conteúdos.          | Animações, Divulgação Científica            |
| RF06   | Recomendação automática de conteúdos relacionados com base no histórico do usuário. | Animações, Jogos, Plataformas educacionais  |
| RF07   | Oferecer trilhas de aprendizado organizadas por tema e nível de conhecimento.       | Divulgação Científica, Plataformas educacionais |
| RF08   | Permitir acesso a artigos e materiais com diferentes níveis de profundidade.        | Divulgação Científica                       |
| RF09   | Classificar conteúdos por categoria, complexidade e não apenas por data.            | Divulgação Científica                       |
| RF10   | Permitir busca eficiente por conteúdos diversos da plataforma.                      | Divulgação Científica, Fóruns, Plataformas educacionais |
| RF11   | Notificar sobre eventos astronômicos ou promoções relevantes.                       | Divulgação Científica, Promoções            |
| RF12   | Exibir uma agenda de eventos científicos/astronômicos atualizada.                   | Divulgação Científica                       |
| RF13   | Disponibilizar seção de notícias e atualizações científicas.                        | Divulgação Científica                       |
| RF14   | Permitir publicação de perguntas, respostas e postagens livres em fóruns.           | Fóruns                                      |
| RF15   | Permitir comentários, curtidas/descurtidas e marcação de resposta como “aceita”.    | Fóruns                                      |
| RF16   | Organizar fóruns com tags, categorias e filtros temáticos.                          | Fóruns                                      |
| RF17   | Oferecer perfis de usuários com reputação e histórico.                              | Fóruns                                      |
| RF18   | Disponibilizar área de destaque com conteúdos populares no fórum.                   | Fóruns                                      |
| RF19   | Disponibilizar jogos interativos de lógica, memória e conhecimentos.                | Jogos                                       |
| RF20   | Disponibilizar novos desafios ou jogos com frequência.                              | Jogos                                       |
| RF21   | Oferecer jogos com níveis de dificuldade variados e progressão.                     | Jogos                                       |
| RF22   | Permitir acompanhar desempenho e progresso nos jogos.                               | Jogos                                       |
| RF23   | Exibir rankings, conquistas e recompensas.                                          | Jogos                                       |
| RF24   | Disponibilizar jogos em diferentes formatos (texto, áudio, visual).                 | Jogos                                       |
| RF25   | Permitir classificação de jogos por habilidade ou categoria.                        | Jogos                                       |
| RF26   | Permitir comentários e interação entre usuários em conteúdos selecionados.          | Plataformas educacionais                   |
| RF27   | Permitir avaliações com feedback imediato.                                          | Plataformas educacionais                   |
| RF28   | Sugerir próximos passos com base no desempenho do usuário.                          | Plataformas educacionais                   |
| RF29   | Permitir emissão de certificados de conclusão.                                      | Plataformas educacionais                   |
| RF30   | Exibir lista de promoções organizadas por categoria, data e valor.                  | Promoções                                   |
| RF31   | Permitir favoritar ou salvar promoções.                                             | Promoções                                   |
| RF32   | Permitir ao usuário reportar promoções expiradas ou enganosas.                      | Promoções                                   |
| RF33   | Integrar links de sites parceiros de forma segura.                                  | Promoções                                   |



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
