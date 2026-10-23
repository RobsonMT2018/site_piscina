# 🏊‍♂️ Robson Maciel - Landing Page de Tratamento de Piscinas

Uma landing page moderna, responsiva e de alta conversão para serviços de limpeza, manutenção e tratamento químico de piscinas. Desenvolvida para captar orçamentos de forma simples via simulação e redirecionamento direto para o WhatsApp.

![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🚀 Funcionalidades

- **Design Responsivo:** Adaptado perfeitamente para dispositivos móveis, tablets e desktops.
- **Calculadora/Simulador de Orçamento:** Permite ao cliente selecionar o tipo, tamanho, estado da água e frequência desejada.
- **Integração Direta com WhatsApp:** Formata as respostas do simulador e gera um link pronto de atendimento pelo WhatsApp.
- **Seção Antes e Depois:** Exibição clara de resultados para gerar autoridade e confiança.
- **Navegação Fluida:** Menu fixo com scroll suave para as seções principais.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & JavaScript Vanilla:** Estrutura semântica e lógica interativa sem dependências de frameworks pesados.
- **Tailwind CSS (via CDN):** Estilização moderna e rápida.
- **Font Awesome:** Ícones vetoriais interativos.
- **Google Fonts (Inter):** Tipografia limpa e de excelente legibilidade.

---

## ⚙️ Como Configurar para Produção

Antes de publicar o site no GitHub Pages, você precisa configurar seu **número do WhatsApp** real no código.

1. Abra o arquivo da landing page (ex: `index.html`).
2. Procure pela função JavaScript no final do arquivo:

```javascript
// Número do WhatsApp (Substitua 5500000000000 pelo número real com DDD)
const numeroWhatsApp = "5500000000000";
```

3. Substitua `"5500000000000"` pelo seu número no formato internacional: `55 + DDD + Número` (exemplo: `5511999998888`).
4. Atualize também os links `<a href="https://wa.me/5500000000000...">` presentes nos botões do topo, meio e rodapé do site.

---

## 🌐 Como Publicar no GitHub Pages

1. Crie um novo repositório no seu GitHub.
2. Faça o upload do arquivo da landing page renomeando-o para `index.html`.
3. Adicione este arquivo `README.md` ao mesmo repositório.
4. No GitHub, acesse a aba **Settings** (Configurações) do seu repositório.
5. No menu lateral esquerdo, clique em **Pages**.
6. Em **Build and deployment** -> **Source**, selecione a branch `main` (ou `master`) e a pasta `/ (root)`.
7. Clique em **Save**.
8. Aguarde alguns instantes e o GitHub fornecerá o link público do seu site!

---

## 📂 Estrutura de Arquivos

```text
.
├── index.html          # Código-fonte principal da Landing Page
└── README.md           # Documentação do projeto
```

---

## 📝 Licença

Este projeto está sob a licença MIT. Sinta-se à vontade para utilizar, modificar e adaptar para outros serviços de manutenção e prestação de serviços.
