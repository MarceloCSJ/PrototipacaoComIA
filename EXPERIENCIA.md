# Prototipação Rápida com IA

1. Utilizei o Copilot para gerar as personas, achei que pelo que tenho observado (pelo em Lages-SC) parece ser muito coerente
2. Peguei uma persona (Camila Rodrigues, Revendedora de Produtos de Beleza) por ser de uma área onde atualmente estou trabalhando (Grupo Cize/O Boticário de Lages-SC) e, apesar de não estar inserido exatamente no meio da revenda, consigo ter uma visão sobre isso e também por minha mãe ser uma revendedora (que também se encaixaria em uma persona, assim como a Camila criada pelo Copilot).
3. Personifiquei a Camila através do ChatGPT, porque acredito que ele seja mais "didático" e específico com algumas coisas, principalmente por (minha opiniao) deixar algumas coisas mais explícitas que o Copilot, por exemplo.
4. Fiz algumas perguntas para essa personificação da Camila seguindo os slides e as respostas "dela".
5. Após as perguntas que achei de certa forma validas com o que eu estava buscando no momento, fiz o prompt para a geração de uma tabela com os requisitos funcionais e não funcionais baseado nessa entrevista, pois seria criado alguns critérios e acredito que o próximo passo seria analizar esta tabela com atenção e verificar o que poderia ser melhorado e o que seria real, principalmente com pessoas reais (vide minha mãe), porém acredito que no momento não seria o caso nesta atividade.
6. Após a solicitação dos requisitos, fiz o prompt para realizar o Moscow, Invest e 3 C's. Apesar de eu saber inglês, acredito que o ChatGPT poderia ter traduzido os termos durante a resposta, porém no meu caso não faz diferença.
7. Apesar de eu não ter solicitado explicação sobre os termos do prompt anterior, o ChatGPT explicou alguns conceitos, porém acredito que um prompt ou pesquisa mais aprofundada seria necessário, pois ainda fiquei com dúvidas sobre os termos.  

## Checklist de Validação Humana:

1. Cruzamento (Cada RF tem persona associada? Cada RNF é mensurável?)
- R: Com base nas personas criadas, acredito que todas tem algo em comum e nada muito personalizado, então acredito que as RF estão informando as funcionalidades corretas. Sobre os RNFs, acredito que a IA tenha focado nas coisas principais, como teste com público-alvo e largura de tela, fazendo com que precise realmente de pessoas utilizando antes de ter algum tipo de resposta mais clara sobre o caminho que a aplicação seguirá. 

2. Clareza (Um dev novo consegue ler e entender em 5 minutos?)
- R: Acredito que como se trata basicamente de um CRUD de estoque, fique fácil de entender.

3. Viés (IA inventou APIs, bibliotecas ou padrões inexistentes? Verifique)
- R: Como não exigi nada técnico, somente a construção de personas e requisitos, acredito não ser aplicável neste momento.

4. Segurança (RNFs cobrem autenticação, dados sensíveis e LGPD?)
- R: A IA criou uma RNF de Segurança e privacidade, dado que as senhas não podem ser armazenadas em texto puro, segundo ela, já é uma técnica de segurança, porém como não solicitei nada técnico, não tem a informação de como seria feito essa criptografia da senha, porém ela informa sobre HTTPS, que seria o protocolo seguro de internet e também que um usuário não poderá consultar ou alterar os dados de outro. Ainda no mesmo tema, a IA informou nos RNFs o que parece ser a CID de Segurança da Informação.
### **Confidencialidade** : Um usuário não deverá acessar as informações do outro(_RNF04_).
### **Integridade**: As informações aceitas devem ser consistentes (_RNF05_).
### **Disponibilidade**: Após uma movimentação confirmada deve refletir um novo saldo em até 1 minuto (_RNF06_).

> **Obs:** *Apesar de disponibilidade ser mais aderente a parte de o usuário sempre conseguir acessar o sistema quando quiser, acredito que no escopo inicial deste protótipo, a RNF onde ele deverá conseguir consultar em até 1 minuto o novo saldo atualizado, fará parte da disponibilidade pois é algo que a persona deseja ter confiança que estará correto e disponível sempre que precisar, com o máximo de integridade também.