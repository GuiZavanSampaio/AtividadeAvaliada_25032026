Avaliação — Engenharia de Software
Sistema Integrado de Gestão de Farmácia — MVP

Aluno: Guilherme Sampaio
RA: 25000183
Data: 25/03/2026

Definição do MVP

Meu MVP foca na parte de vendas da farmácia, que é o principal uso no dia a dia. Ele cobre desde identificar ou cadastrar o cliente até finalizar a venda.

Dentro do MVP estão as funções de cadastrar cliente, consultar produto, realizar venda, verificar estoque e emitir comprovante.

Fora do MVP eu deixei coisas mais avançadas como relatórios completos, controle financeiro mais detalhado e integração com fornecedores.

Escolhi isso porque a venda é o mais importante no funcionamento da farmácia e já resolve boa parte dos problemas básicos.

Regras de Negócio

RN01 — Não pode vender produto sem estoque

RN02 — Toda venda diminui o estoque automaticamente

RN03 — Venda a prazo gera conta a receber

RN04 — Cliente pode ser cadastrado na hora

RN05 — Sistema deve avisar quando não tem estoque suficiente

Requisitos Funcionais

RF01 — Cadastrar cliente

RF02 — Consultar produto

RF03 — Cadastrar produto

RF04 — Realizar venda

RF05 — Verificar estoque antes da venda

RF06 — Registrar venda a prazo

RF07 — Atualizar estoque automaticamente

RF08 — Emitir comprovante de venda

Requisitos Não Funcionais

RNF01 — Sistema deve ser fácil de usar

RNF02 — Sistema deve responder rápido

RNF03 — Deve funcionar em computador comum

RNF04 — Deve armazenar os dados corretamente

Casos de Uso

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


Documentação dos Casos de Uso

UC01 — Realizar Venda

Ator: Atendente

Descrição:
Permite registrar a venda de produtos para um cliente

Pré-condições:
Sistema funcionando
Produto cadastrado

Pós-condições:
Venda registrada
Estoque atualizado

Fluxo principal

Atendente inicia a venda
Informa ou cadastra o cliente
Seleciona o produto
Sistema verifica o estoque
Informa a quantidade
Sistema calcula o valor
Confirma a venda
Sistema registra a venda
Sistema atualiza o estoque
Sistema emite comprovante

Fluxos alternativos

FA01 — Sem estoque
Sistema informa que não tem produto suficiente

FA02 — Cliente não cadastrado
Permite cadastrar o cliente na hora

Relacionamentos

Include: verificar estoque, fazer comprovante

Extend: registrar venda a prazo
