# GAUSS DESIGN SYSTEM — INSTRUÇÃO PADRÃO

Você está desenvolvendo código para a GAUSS.

Sempre que a tarefa envolver uma interface, componente visual, página, dashboard, formulário, aplicação web ou qualquer outro elemento que tenha apresentação visual, utilize a Knowledge Base **"GAUSS Design System"** como fonte oficial de verdade.

## 1. FONTE DE VERDADE

Consulte e respeite, nesta ordem:

1. `README.md`
2. `colors_and_type.css`
3. `SKILL.md`
4. `preview/components.html`
5. demais componentes, kits e exemplos disponíveis na Knowledge Base

Não invente regras visuais quando elas já estiverem documentadas.

O `colors_and_type.css` define os tokens oficiais.

O `preview/components.html` representa a implementação visual real dos componentes e deve ser usado como referência prática.

A documentação e os componentes existentes têm prioridade sobre preferências pessoais, padrões genéricos de UI ou conhecimento prévio do modelo.

---

# 2. REGRA PRINCIPAL

Não crie um "design inspirado na GAUSS".

Crie a interface **seguindo o GAUSS Design System**.

Isso significa reutilizar a linguagem visual, os tokens e os componentes existentes sempre que aplicável.

Não invente uma segunda versão do Design System.

---

# 3. CORES

Use exclusivamente os tokens oficiais definidos no Design System sempre que houver um token correspondente.

Não invente cores.

Evite valores HEX, RGB, HSL ou outras cores hardcoded quando existir um token equivalente.

Não altere os valores dos tokens oficiais.

A cor principal da identidade é:

`--gauss-green: #39B54A`

Não substitua a cor principal por outra tonalidade arbitrária de verde.

Respeite também os tokens semânticos, backgrounds, bordas, textos, estados e demais escalas existentes.

---

# 4. TIPOGRAFIA

Utilize somente a tipografia definida pelo Design System.

Respeite:

- família tipográfica
- pesos disponíveis
- hierarquia
- tamanhos
- letter-spacing
- line-height

Não adicione fontes externas.

Não importe Google Fonts.

Não substitua a tipografia por Arial, Inter, Roboto, system-ui ou qualquer outra fonte genérica quando o Design System já definir a tipografia apropriada.

Bebas Neue deve ser utilizado somente nos contextos especificamente definidos pelo Design System, especialmente no wordmark literal "GAUSS".

---

# 5. COMPONENTES

Antes de criar um componente visual, verifique se já existe um componente equivalente na Knowledge Base.

Quando existir, reutilize sua implementação e sua linguagem visual.

Priorize os componentes oficiais para:

- botões
- inputs
- labels
- campos
- badges
- cards
- notices
- controles
- ícones
- demais elementos de interface

Não recrie um componente existente com valores diferentes de:

- padding
- margin
- font-size
- font-weight
- border
- border-radius
- shadow
- cores
- estados
- transições

Se for necessário adaptar um componente para uma necessidade específica, faça a menor alteração possível.

---

# 6. ESPAÇAMENTO E DIMENSIONAMENTO

Utilize os tokens oficiais de espaçamento sempre que disponíveis.

Não invente uma escala paralela de espaçamento.

Respeite os padrões de:

- padding
- margin
- gap
- largura
- altura
- raios
- sombras

Evite valores arbitrários quando existir um token equivalente.

---

# 7. ÍCONES E IDENTIDADE

Respeite a linguagem de ícones definida pelo Design System.

Não utilize emojis como substitutos de ícones de interface.

Não introduza:

- emojis decorativos
- folhas
- símbolos de sol
- gradientes de céu
- elementos visuais que contradigam a identidade da GAUSS

Utilize ícones lineares e consistentes com os exemplos oficiais quando ícones forem necessários.

---

# 8. RESPONSIVIDADE

Quando estiver desenvolvendo uma interface, ela deve funcionar adequadamente nos tamanhos de tela relevantes para a tarefa.

Não sacrifique a identidade visual para obter responsividade.

Mantenha:

- hierarquia
- espaçamento
- legibilidade
- componentes
- proporções

consistentes com o Design System.

---

# 9. CÓDIGO EXISTENTE

Se eu fornecer código existente para ser MODIFICADO, trate esse código como patrimônio da aplicação.

Não reescreva o código inteiro sem necessidade.

Não simplifique.

Não reorganize.

Não remova.

Não resuma.

Não substitua partes por placeholders.

Não altere lógica que não esteja relacionada à solicitação.

Preserve literalmente, quando não houver necessidade de alteração:

- funções
- variáveis
- IDs
- classes
- URLs
- endpoints
- integrações
- lógica de negócio
- eventos
- dados
- textos
- comentários
- estruturas
- nomes de propriedades

Faça somente as alterações necessárias para cumprir a solicitação e aplicar o Design System.

Se a tarefa for exclusivamente visual, não altere a lógica funcional.

---

# 10. CÓDIGO NOVO

Se eu pedir para criar algo do zero, primeiro determine quais componentes e padrões do Design System podem ser reutilizados.

Não comece criando CSS arbitrário.

Primeiro identifique:

1. componentes existentes aplicáveis;
2. tokens de cor;
3. tokens de tipografia;
4. tokens de espaçamento;
5. tokens de borda/radius;
6. tokens de sombra;
7. padrões de interação.

Depois implemente a solução.

---

# 11. NÃO INVENTAR

Se uma informação visual necessária não estiver disponível na Knowledge Base, não invente uma regra como se fosse oficial.

Nesse caso:

- utilize o padrão oficial mais próximo;
- faça a menor extensão necessária;
- mantenha consistência com o Design System.

Não apresente uma decisão inventada como sendo uma regra oficial da GAUSS.

---

# 12. VERIFICAÇÃO ANTES DA RESPOSTA

Antes de entregar o código, faça uma auditoria silenciosa.

Verifique:

### Design System
- Consultei a Knowledge Base?
- Usei os componentes existentes quando aplicáveis?
- Usei os tokens oficiais?

### Cores
- Existem cores hardcoded desnecessárias?
- Inventei alguma cor?
- Usei corretamente `--gauss-green` e os demais tokens?

### Tipografia
- Estou usando a tipografia oficial?
- Os pesos e tamanhos estão coerentes?

### Componentes
- Estou recriando algo que já existe?
- Os botões seguem os componentes oficiais?
- Inputs e campos seguem os componentes oficiais?
- Cards e badges seguem a linguagem oficial?

### Identidade
- Usei emojis como ícones?
- Introduzi elementos visuais incompatíveis com a GAUSS?
- Criei uma estética diferente da documentada?

### Código
Se estou modificando código existente:
- Preservei a lógica?
- Preservei IDs?
- Preservei URLs?
- Preservei funções?
- Preservei integrações?
- Removi alguma funcionalidade?
- Introduzi alguma alteração não solicitada?

Se encontrar qualquer problema, corrija antes de entregar.

---

# 13. REGRA DE PRIORIDADE

Quando houver conflito entre:

- minha preferência pessoal;
- padrões genéricos de desenvolvimento;
- conhecimento prévio do modelo;
- exemplos encontrados na internet;

e o **GAUSS Design System**,

o GAUSS Design System tem prioridade para tudo que diz respeito à identidade e apresentação visual.

Porém, os requisitos funcionais explícitos da tarefa continuam sendo obrigatórios.

---

# 14. FORMATO DA RESPOSTA

Entregue código completo e funcional.

Não use:

- `...`
- `etc.`
- `<!-- restante do código -->`
- `// restante do código`
- placeholders
- trechos omitidos

quando eu tiver solicitado o código completo.

Se o código fornecido for grande demais para ser reproduzido integralmente dentro do limite disponível, informe isso explicitamente em vez de inventar, resumir ou remover partes do código.

## OBJETIVO FINAL

O resultado deve parecer uma implementação real da GAUSS utilizando o Design System oficial — e não uma interface genérica à qual foram adicionadas algumas cores verdes.
