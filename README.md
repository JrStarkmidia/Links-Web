# Links-Web

# StarkMidia Link

Página de Links personalizada para a StarkMidia, centralizando acesso rápido aos principais canais de contato, redes sociais e informações da empresa. Inspirado nos melhores padrões de UI/UX para Linktree e páginas de bio, com foco em design responsivo, praticidade e performance.

![Preview StarkMidia](https://midias.top/logo.png) <!-- Troque para uma URL real da imagem, se desejar -->

## 💡 Sobre

Este projeto oferece uma **única página de links**, com todos os canais importantes da StarkMidia:
- WhatsApp
- Instagram
- Facebook
- Site Oficial
- Chave PIX (com botão copiar)
- Google Maps (endereço)
- Botão de compartilhar link

## ⚙️ Como funciona

- **Responsivo**: Se adapta perfeitamente em dispositivos móveis e desktop.
- **Dark/Light Mode**: Alternância de tema manual via botão (no canto superior direito).
- **Ícones modernos**: SVG de alta qualidade, alinhados ao design do TailwindCSS.
- **Chave Pix**: Botão que copia automaticamente a chave Pix para a área de transferência.
- **Compartilhamento**: Botão de compartilhar usando a [Web Share API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Share_API) — sempre que o navegador suportar.
- **Open Graph e SEO**: A página inclui meta tags para gerar preview de imagem e texto ao ser compartilhada no WhatsApp, Facebook, etc.

## 🚀 Deploy

Basta subir os arquivos em qualquer serviço de hospedagem estática (Vercel, Netlify, GitHub Pages, etc.)  
Não exige backend. É só HTML, CSS (Tailwind via CDN) e SVG.

## 📝 Observações

- O preview da imagem ao compartilhar depende das **meta tags** na página (Open Graph).
- Para o botão de compartilhar funcionar em todos os dispositivos, o navegador do usuário precisa suportar a **Web Share API**.
- Os ícones podem ser facilmente trocados por outros SVGs.
- Para editar links, ícones ou layout, basta alterar o arquivo `index.html`.
- O botão Pix apenas copia a chave Pix — não faz pagamento automático.
- O projeto não coleta nenhum dado dos visitantes.

## 🎨 Personalização

Se quiser adaptar para outra empresa ou pessoa:
- Troque as URLs e textos nos botões
- Altere as cores e o logo conforme sua identidade visual
- Substitua ícones ou ordem dos links conforme preferência

## 👨‍💻 Créditos

Desenvolvido por StarkMidia  
[https://midias.top](https://midias.top)

---

Sinta-se à vontade para **forkar**, adaptar e divulgar!  
Para dúvidas ou sugestões, envie um pull request ou abra uma issue.


