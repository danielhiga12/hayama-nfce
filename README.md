# Hayama NFC-e Retirada - Site de Recibos

Este projeto é um **site para gerar recibos NFC-e para retirada no Hayama Sushi**, no estilo de delivery (como o iFood).

---

## Funcionalidades

- Adição manual de itens (nome do item, quantidade e valor unitário)
- Inserção do **nome do cliente**
- Título grande **RETIRADA** no recibo
- Tabela detalhada de itens: **QTD | ITEM | VALOR**
- Total calculado automaticamente
- Layout otimizado para **impressoras térmicas 58mm/80mm**
- Fundo estilo **sushi** na tela
- Ao clicar em **IMPRIMIR NFC-e**, gera apenas o recibo limpo, pronto para impressão

---

## Como usar

1. Abra o site (`index.html` ou link do Render)
2. Digite:
   - Nome do cliente
   - Nome do item
   - Quantidade
   - Valor unitário
3. Clique **Adicionar Item** para cada item
4. Clique **IMPRIMIR NFC-e** para gerar o recibo no estilo delivery
5. O recibo será impresso com:
   - RETIRADA (título grande)
   - Nome do cliente
   - Tabela de itens
   - Total destacado
6. O fundo de sushi é apenas visual na tela; a impressão será limpa

---

## Observações

- Este site **não emite NFC-e oficial**; é apenas para recibos de retirada interna.
- Layout testado para impressoras térmicas 58mm e 80mm.
- É possível hospedar no **GitHub + Render** ou abrir localmente no navegador.
