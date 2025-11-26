# WooCommerce Cart Quantity Validation

Snippets personalizados para WooCommerce que controlam a quantidade de produtos no carrinho com base em regras específicas.

## Regras implementadas

- **Múltiplos de 3 obrigatórios**: Exige que a quantidade total de produtos de uma categoria específica (ex.: `vinhos-verdes`) esteja em múltiplos de 3 (ex.: 3, 6, 9…).
- **Quantidade mínima de 3**: Bloqueia o checkout se a quantidade for menor que 3 produtos da categoria.

## Personalização

Os snippets podem ser facilmente adaptados alterando o slug da categoria no código:

```php
has_term('vinhos-verdes', 'product_cat', $produto->get_id())



---

## ✅ Como adicionar isso no GitHub:

1. Acesse seu repositório.
2. Clique em **"Add file" → "Create new file"**.
3. No campo de nome, digite `README.md`.
4. Cole o conteúdo acima.
5. Clique em **"Commit new file"**.

---

Se preferir, posso gerar esse `README.md` como arquivo e enviar em `.zip` junto dos `.php`. Deseja isso?
