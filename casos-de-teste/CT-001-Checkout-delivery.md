- ID: CT-001
- Funcionalidade: Checkout
- Objetivo: Verificar o comportamento com nome e cep
- Pré-condição: Estar logado

**Passos:**
1. Adicionar item ao carrinho
2. Ir para o checkout
3. Preencher os campos:
   - First Name: 12345
   - Last Name: Teste
   - ZIP Code: 12345
4. Clicar em “Continue”

**Resultado Esperado:**
- O sistema deve exibir mensagem de erro: “Nome inválido” ou impedir o avanço

**Resultado Obtido:**
- ❌ Falhou: O sistema aceitou o nome com números e continuou para a próxima tela
