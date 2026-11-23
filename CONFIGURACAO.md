# Dados a preencher antes de lançar

| Campo | Valor |
|---|---|
| WhatsApp comercial | PENDENTE |
| Instagram comercial | PENDENTE |
| Checkout plano Básico | PENDENTE |
| Checkout plano PRO | PENDENTE |
| Checkout oferta adicional | PENDENTE |
| Nome/marca e suporte | PENDENTE |
| Domínio | agenciaaztro.online (registrado na Hostinger; DNS e GitHub Pages ainda pendentes) |
| Pixel Meta | PENDENTE |
| Analytics | PENDENTE |
| Política de privacidade | PENDENTE |
| Termos de uso | PENDENTE |
| Política de reembolso | PENDENTE |

Os links do checkout e de WhatsApp no HTML continuam desativados (`data-preview-link`) e devem ser configurados somente depois da escolha do provedor e validação do produto.

Você **pode colocar tudo isso depois**, inclusive checkout. Para simplesmente salvar e preparar o código não é necessário ter os links agora. Antes de divulgar ou receber visitantes comprando, conecte e teste os links.

## Publicação no domínio (em andamento)

- Repositório do site: `Carloszw45/monetize-gta6`, branch `main`, raiz.
- O arquivo `CNAME` já foi criado com `agenciaaztro.online`.
- No Cloudflare (Free), adicionar `agenciaaztro.online`, manter DNS only durante a ativação e configurar:
  - `A @ 185.199.108.153`
  - `A @ 185.199.109.153`
  - `A @ 185.199.110.153`
  - `A @ 185.199.111.153`
  - `CNAME www carloszw45.github.io`
- Na Hostinger, configurar os dois nameservers EXATAMENTE conforme informados pelo Cloudflare (não utilizar valores genéricos).
- No GitHub: Settings > Pages > Custom domain = `agenciaaztro.online`; salvar, verificar DNS e ativar Enforce HTTPS quando estiver disponível.
- Antes de divulgar: obter os links reais do checkout Bravo Pay, confirmar que o produto digital será entregue e remover a faixa de demonstração somente depois dos testes.
