# _Prompt Copilot:_

Estou especificando um MVP de sistema web de gerenciamento de estoque para pequenos negócios (revendedores de produtos de beleza, revendedores de produtos tecnológicos, revendedores de roupas).
Domínio: serviço de estoque, aviso de estoque baixo ou parado a muito tempo.
Região: Brasil. Idioma: Português.
<br>
Gere 3 personas distintas que representem o público-alvo deste sistema. Para cada persona, inclua:
- Nome (fictício, realista)
- Idade, profissão, cidade
- Principal dor relacionada a gerenciamento de estoque
- Nível de familiaridade com tecnologia
- Cenário típico de uso do sistema
- 1 métrica de sucesso que esta persona usaria
<br>
Você é uma pesquisadora UX Sênior com experiência em design de serviços para pequenos negócios.
Markdown | bloco por persona, separadas por ***
No final, inclua uma tabela comparativa das 3 personas(colunas: persona, dor principal, tecnologia, métrica)
<br>

# _Resposta Copilot:_

## Persona 1: Juliana Ferreira, Revendedora de Cosméticos

**Idade:** 38 anos  
**Profissão:** Revendedora de produtos de beleza multimarcas  
**Cidade:** Campinas (SP)

### Principal dor relacionada ao estoque
Juliana trabalha com dezenas de itens de maquiagem, perfumes e cuidados pessoais. Ela frequentemente compra reposições sem saber exatamente o que ainda possui em estoque, gerando excesso de produtos de baixa saída e falta dos mais vendidos.

### Nível de familiaridade com tecnologia
**Médio.** Utiliza WhatsApp Business, Instagram e aplicativos bancários diariamente, mas evita sistemas complexos que exigem treinamento.

### Cenário típico de uso do sistema
No início da semana, Juliana verifica os alertas do sistema para identificar:
- Produtos com estoque abaixo do mínimo;
- Itens próximos de acabar;
- Produtos parados há mais de 90 dias.

Com base nesses alertas, decide quais itens recomprar e quais colocar em promoção.

### Métrica de sucesso
**Redução de rupturas de estoque dos produtos mais vendidos.**

***

## Persona 2: Ricardo Nogueira, Revendedor de Produtos Tecnológicos

**Idade:** 32 anos  
**Profissão:** Proprietário de loja de acessórios para celular e eletrônicos  
**Cidade:** Belo Horizonte (MG)

### Principal dor relacionada ao estoque
Ricardo trabalha com centenas de SKUs (cabos, carregadores, capas, fones e acessórios). Ele perde dinheiro porque alguns produtos ficam esquecidos no estoque enquanto outros acabam sem que ele perceba.

### Nível de familiaridade com tecnologia
**Alto.** Utiliza marketplaces, sistemas de pagamento, planilhas e plataformas digitais regularmente.

### Cenário típico de uso do sistema
Ao final de cada dia, Ricardo consulta o dashboard para acompanhar:
- Quantidade total de produtos por categoria;
- Itens sem movimentação há mais de 60 dias;
- Ranking dos produtos com menor giro.

O objetivo é identificar rapidamente mercadorias que estão ocupando espaço e imobilizando capital.

### Métrica de sucesso
**Redução do valor financeiro em estoque parado.**

***

## Persona 3: Patrícia Alves, Proprietária de Boutique de Roupas

**Idade:** 45 anos  
**Profissão:** Proprietária de loja de roupas femininas  
**Cidade:** Goiânia (GO)

### Principal dor relacionada ao estoque
Patrícia possui muitas variações de tamanho, cor e modelo. Ela tem dificuldade para identificar quais combinações estão faltando e quais peças permanecem encalhadas após cada estação.

### Nível de familiaridade com tecnologia
**Baixo a médio.** Usa sistemas de vendas básicos, mas prefere interfaces simples e intuitivas.

### Cenário típico de uso do sistema
Antes de realizar compras de uma nova coleção, Patrícia acessa o sistema para visualizar:
- Peças com estoque crítico por tamanho;
- Produtos sem venda há mais de 120 dias;
- Distribuição do estoque por categoria.

Essas informações ajudam a evitar compras desnecessárias e a planejar liquidações.

### Métrica de sucesso
**Aumento do giro de estoque por coleção.**

***

## Tabela Comparativa

| Persona | Dor Principal | Tecnologia | Métrica de Sucesso |
|----------|--------------|------------|-------------------|
| **Juliana Ferreira** | Comprar produtos sem visibilidade do estoque real, gerando excesso e falta de itens | Médio | Redução de rupturas de estoque dos produtos mais vendidos |
| **Ricardo Nogueira** | Grande volume de SKUs dificulta identificar produtos parados e faltantes | Alto | Redução do valor financeiro em estoque parado |
| **Patrícia Alves** | Dificuldade em controlar variações de tamanho, cor e coleção | Baixo a médio | Aumento do giro de estoque por coleção |

## Observação UX para o MVP

Essas três personas convergem em duas necessidades centrais que devem ser prioridades do MVP:

1. **Alertas automáticos de estoque baixo**, com definição de estoque mínimo por produto.
2. **Alertas de estoque parado**, destacando itens sem movimentação por períodos configuráveis (30, 60, 90 ou 120 dias).

Essas funcionalidades atacam diretamente os principais riscos para pequenos revendedores: perda de vendas por falta de produtos e capital imobilizado em mercadorias paradas.