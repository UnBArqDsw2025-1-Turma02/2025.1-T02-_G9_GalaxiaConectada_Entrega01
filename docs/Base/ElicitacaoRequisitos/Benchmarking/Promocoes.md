# Benchmarking em Relação a Sites de Promoções

## Sumário

* [Cuponomia](#Cuponomia)
* [Promobit](#Promobit)
* [Lições para o projeto Galáxia Conectada](#Lições-para-o-projeto-Galáxia-Conectada)
* [Requisitos Elicitados](#Requisitos-Elicitados)
  * [Requisitos Funcionais](#Requisitos-Funcionais)
  * [Requisitos Não-Funcionais](#Requisitos-Não-Funcionais)

## [Cuponomia](https://www.cuponomia.com.br/)

### 📝 Descrição do site
Plataforma brasileira que reúne cupons de desconto, cashback e promoções de diversas lojas online. 

### 🎯 Estrutura e Estilo
- Navegação por categorias (moda, eletrônicos, mercado, viagens etc.).
- Buscador central de cupons por loja ou produto.
- Interface limpa, leve e responsiva.

### 🛍️ Elementos de Engajamento
- Sistema de cashback: usuários acumulam valores por compras feitas com link do site.
- Ranking de melhores ofertas.
- Notificações por e-mail e navegador sobre novos cupons.

### ✅ Pontos Positivos
- Facilidade de uso e navegação intuitiva.
- Grande variedade de lojas e cupons.
- Funcionalidade de cashback integrada e confiável.

### ❌ Pontos Negativos
- Nem todos os cupons funcionam (falta de verificação automática em tempo real).
- Layout mais tradicional.


## [Promobit](https://www.promobit.com.br/)

### 📝 Descrição do site
Plataforma colaborativa de promoções em tempo real, onde os próprios usuários compartilham e avaliam ofertas. Possui foco em promoções verificadas e oferece suporte para compras mais conscientes.

### 🎯 Estrutura e Estilo
- Divisão por categorias (eletrônicos, casa, beleza, games.).
- Destaques em promoções do dia e mais votadas.
- Comunidade ativa comentando, avaliando e compartilhando experiências.

### 🛍️ Elementos de Engajamento
- Sistema de votação de promoções (positivo/negativo).
- Comentários e avaliações colaborativas nas ofertas.
- Área de **listas de desejos** com alertas personalizados.


### ✅ Pontos Positivos
- Comunidade ativa e colaborativa.
- Foco em promoções verificadas reduz chances de erro.

## ✨ Lições para o projeto **Galáxia Conectada**

- A ideia de **comunidade colaborativa** (como no Promobit) pode ser aplicada à área de eventos astronômicos ou promoções de cursos e livros científicos.
- Funcionalidades como **listas de desejos e alertas personalizados** são úteis para acompanhar interesses do usuário.

## Requisitos Elicitados

### Requisitos Funcionais 

| Código | Requisito Funcional                                                                      | Objetivo                                                                                   | Origem             |
|--------|-------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|--------------------|
| RF01   | O sistema deve exibir uma lista de promoções organizadas por categoria.                  | Facilitar a busca de ofertas relevantes.                                                   | Promobit / Cuponomia |
| RF02   | O sistema deve permitir que os usuários filtrem promoções por tipo, data ou valor.       | Oferecer personalização na busca de promoções.                                             | Promobit           |
| RF03   | O sistema deve permitir que usuários avaliem e comentem promoções.                       | Promover a confiança e o engajamento entre os usuários.                                    | Promobit           |
| RF04   | O sistema deve disponibilizar cupons de desconto com instruções de uso.                  | Aumentar a usabilidade dos descontos.                                                      | Cuponomia          |
| RF05   | O sistema deve permitir que o usuário favorite ou salve promoções para ver depois.       | Manter o interesse ativo e facilitar o retorno.                                            | Promobit / Cuponomia |
| RF06   | O sistema deve notificar os usuários sobre promoções relevantes por e-mail ou push.      | Manter os usuários informados e engajados.                                                 | Cuponomia          |
| RF07   | O sistema deve exibir datas de validade e detalhes da promoção de forma clara.           | Evitar frustrações e aumentar a transparência.                                             | Promobit / Cuponomia |
| RF08   | O sistema deve permitir login para acompanhar histórico e preferências de promoções.     | Personalizar a experiência do usuário.                                                     | Cuponomia          |
| RF09   | O sistema deve permitir reportar promoções expiradas ou enganosas.                       | Manter a qualidade das informações.                                                        | Promobit           |
| RF10   | O sistema deve integrar links para sites parceiros ou externos com segurança.            | Direcionar o usuário para compras sem comprometer sua segurança.                          | Cuponomia          |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

### Requisitos Não Funcionais 

| Código | Requisito Não Funcional                                                                   | Objetivo                                                                                     | Origem             |
|--------|--------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|--------------------|
| RNF01  | O sistema deve ser responsivo e acessível em dispositivos móveis.                          | Ampliar o acesso dos usuários.                                                               | Cuponomia / Promobit |
| RNF02  | O tempo de carregamento de páginas não deve exceder 3 segundos.                            | Melhorar a experiência do usuário.                                                           | Cuponomia          |
| RNF03  | O sistema deve seguir padrões de segurança em redirecionamentos e cupons.                  | Garantir a proteção dos usuários.                                                            | Cuponomia / Promobit |
| RNF04  | O sistema deve usar HTTPS em todas as páginas.                                             | Assegurar a privacidade dos dados dos usuários.                                              | Cuponomia          |
| RNF05  | O sistema deve permitir integração com redes sociais e login via Google/Facebook.         | Facilitar o acesso e compartilhamento.                                                       | Promobit           |
| RNF06  | A interface deve ser intuitiva, com destaque para promoções em destaque.                  | Aumentar o engajamento e facilitar a navegação.                                              | Cuponomia / Promobit |
| RNF07  | O sistema deve garantir alta disponibilidade (acima de 99%).                              | Manter o serviço sempre acessível.                                                           | Promobit           |
| RNF08  | O sistema deve suportar atualizações frequentes de conteúdo promocional.                  | Garantir informações atualizadas.                                                            | Cuponomia          |
| RNF09  | O sistema deve usar layout leve e otimizado para diferentes conexões.                      | Melhorar desempenho em diferentes localidades e redes.                                       | Promobit           |
| RNF10  | O sistema deve armazenar apenas os dados essenciais dos usuários com consentimento.        | Cumprir com a LGPD e reforçar a segurança de dados.                                          | Cuponomia          |


<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.
