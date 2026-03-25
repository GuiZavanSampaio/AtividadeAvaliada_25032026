Avaliação — Engenharia de Software
Sistema Integrado de Gestão de Farmácia — MVP Definido pelo Estudante

Aluno: Guilherme Sampaio
RA: 25000183
Data: 25/03/2026

---

1. Definição do MVP

Meu MVP cobre o processo de venda desde a identificação ou cadastro do cliente até a emissão do comprovante, incluindo a verificação de estoque.

O que está dentro do MVP:
Cadastro de cliente, consulta de produto, realização de venda, verificação de estoque, atualização de estoque e emissão de comprovante.

O que está fora do MVP:
Relatórios mais completos, controle financeiro detalhado, integração com fornecedores e controle de usuários.

Por que você fez essas escolhas:
Escolhi focar na parte de vendas porque é a principal função da farmácia no dia a dia e já resolve boa parte dos problemas básicos.

---

2. Regras de Negócio

RN01 — Não é permitido vender produtos sem estoque disponível

RN02 — Toda venda realizada deve diminuir automaticamente o estoque

RN03 — Vendas a prazo devem gerar uma conta a receber

RN04 — O cliente pode ser cadastrado durante a venda

RN05 — O sistema deve avisar quando o estoque for insuficiente

---

3. Requisitos Funcionais

RF01 — O sistema deve permitir cadastrar clientes

RF02 — O sistema deve permitir consultar produtos

RF03 — O sistema deve permitir cadastrar produtos

RF04 — O sistema deve permitir realizar vendas

RF05 — O sistema deve verificar o estoque antes da venda

RF06 — O sistema deve permitir registrar vendas a prazo

RF07 — O sistema deve atualizar o estoque automaticamente

RF08 — O sistema deve emitir comprovante de venda

---

4. Requisitos Não Funcionais

RNF01 — O sistema deve ser fácil de usar

RNF02 — O sistema deve ter resposta rápida

RNF03 — O sistema deve funcionar em computadores comuns

RNF04 — O sistema deve armazenar os dados corretamente

---

5. Casos de Uso

Cadastrar cliente
Consultar produto
Cadastrar produto
Realizar venda
Verificar estoque
Registrar venda a prazo
Atualizar estoque
Emitir comprovante
Fazer login
Cancelar venda


---

6. Documentação dos Casos de Uso

UC01 — Realizar Venda

Ator(es):
Atendente

Descrição:
Permite que o atendente registre a venda de produtos para um cliente

Pré-condições:
Sistema funcionando
Produto cadastrado

Pós-condições:
Venda registrada no sistema
Estoque atualizado

---

Fluxo Principal

1. Atendente inicia a venda
2. Sistema solicita o cliente
3. Atendente informa ou cadastra o cliente
4. Atendente seleciona o produto
5. Sistema verifica o estoque
6. Atendente informa a quantidade
7. Sistema calcula o valor
8. Atendente confirma a venda
9. Sistema registra a venda
10. Sistema atualiza o estoque
11. Sistema emite comprovante

---

Fluxos Alternativos / Exceções

FA01 — Produto sem estoque
O sistema informa que não há quantidade disponível

FA02 — Cliente não cadastrado
O sistema permite cadastrar o cliente na hora

---

Relacionamentos

Include:
Verificar estoque
Atualizar estoque
Emitir comprovante

Extend:
Registrar venda a prazo
