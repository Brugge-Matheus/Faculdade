
## E-commerce de eletrônicos

### Dados gerados

#### 1- *Dados Usuário* - Guarda as informações do usuário
(IdUsuario *Primary Key*,
NomeCompleto, 
E-mail,
Cpf,
Endereço
);

#### *2- Suporte de atendimento ao cliente (SAC)*
(
idCliente *Primary Key*,
NumeroPedido,
problema,
status,
);


#### 1- e-commerce
(
idproduto *Primary Key*,
nome,
preço,
descrição,
imagem
)

##### 1.1 - Categoria
(
idproduto *Primary Key*,
nome
)

##### 1.2 - Pedidos
(
clienteid *Primary Key*,
pedidoid *Foreign Key*,
datapedidos,
)

##### 1.2.1 - Itens Pedido
(
itempedidoid *Primary Key*,
pedidoid *Foreign Key*,
produtoid *Foreign Key*,
quantidade,
precoUnitario
)








#### Centro de distribuição
## Informações HoGa_TECH

### Informações Operacionais

1.  **E-commerce:** A HoGa_TECH é uma empresa de comércio eletrônico que oferece uma ampla variedade de produtos, desde componentes de computador até periféricos e eletrônicos. Seu site tem uma interface amigável e várias opções de pagamento.
    
2.  **Centro de distribuição:** A empresa possui um centro de distribuição estrategicamente localizado para garantir uma entrega eficiente em todo o Brasil.
    
3.  **Atendimento ao cliente:** Valorizando o atendimento ao cliente, a HoGa_TECH oferece suporte via chat online, e-mail e telefone, além de uma seção de perguntas frequentes em seu site.
 
### Informações Gerenciais

1. **Vendas e Receitas**: Monitoramento do volume de vendas e da receita gerada ao longo do tempo.
    
2. **Margens de Lucro**: Acompanhamento das margens de lucro por produto e categoria.
    
3. **Custos Operacionais**: Controle dos custos de operação, como pessoal, marketing e logística.
    
4. **Estoques**: Gestão eficiente do estoque para atender à demanda sem excessos.

### Informações Estratégicas

1. **Inovação Tecnológica:** Investimento em tecnologia para aprimorar a experiência do cliente e otimizar processos.
    
2. **Estratégias de Marketing:** Desenvolvimento de estratégias para aumentar a visibilidade da marca e atrair novos clientes.
    
3. **Atendimento ao Cliente:** Priorização do atendimento de qualidade para garantir a satisfação do cliente