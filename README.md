# Combo 4 Aulões — site de vendas

Site estático do Combo 4 Aulões da Wanessa Massafelli (empadinha na modeladora, nhoque em 3 formas,
pão de queijo na modeladora e na mão, nhoque gourmet de alho-poró com parmesão).

- Gerado pelo `build_site.py` (guardado no projeto CURSOS SITES, no Claude), a partir do canvas de Design.
- Publicado na Hostinger por deploy automático deste repositório.

## Trocar os links de compra sem rebuild
Edite `index.html`, no bloco `window.ABC_CONFIG` do topo:
- `linkCheckout`: link da Kiwify do combo (R$ 39,90).
- `linkOferta`: link do pop-up, se houver oferta menor.
- `utmifyPixelId`: id do pixel da Utmify.

Enquanto `linkCheckout` estiver vazio, os botões COMPRAR AGORA levam ao bloco de preço.
