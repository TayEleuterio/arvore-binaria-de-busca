# arvore-binaria-de-busca
Atividade - Árvore Binária de Busca (BST) com Operações Avançadas

# Atividade - Árvore Binária de Busca (BST) com Operações Avançadas


A proposta da presete atividade é gerenciar uma Árvore Binária de Busca (BST) que armazena pares (chave, contador), permitindo a existência de múltiplas cópias (frequência) de uma mesma chave. Além das operações básicas de inserção, busca e remoção, serão implementadas funções mais avançadas, como:

- Remover apenas uma ocorrência de uma chave (decrementando o contador).
- Remover todas as ocorrências de uma chave (caso o contador seja maior que 1).
- Contar quantos nós (ou chaves distintas) existem na árvore.
- Encontrar o k-ésimo menor (ou maior) elemento considerando frequência.
- Imprimir todas as chaves dentro de um intervalo \[min, max].
- Encontrar o Lowest Common Ancestor (LCA) de duas chaves (objetivo opcional)

Seguem listadas abaixo as funções implementadas:

# Funções Básicas
- void inicializar(PONT* raiz)
- PONT criarNo(int valor)
- PONT buscar(PONT raiz, int valor)

# Inserção e Remoção (com contador)
- PONT inserir(PONT raiz, int valor)
- PONT removerUmaOcorrencia(PONT raiz, int valor)
- PONT removerTodasOcorrencias(PONT raiz, int valor)

# Percursos e Impressões
- void exibirInOrder(PONT raiz)

# Funções de Contagem e Estatística
- int contarNos(PONT raiz)
- int contarTotalElementos(PONT raiz)

# Funções Avançadas
- int kEsimoMenor(PONT raiz, int k)
- void imprimirIntervalo(PONT raiz, int min, int max)
- PONT lowestCommonAncestor(PONT raiz, int val1, int val2) (opcional)

# Apontamentos:
- Após diversos testes a função lowestCommonAncestor segue retornando valores diversos dos esperados para LCA(16,18) e LCA(5,18).
