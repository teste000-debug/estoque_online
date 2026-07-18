# Central de Estoque - Roçadeiras & Máquinas

Sistema de gerenciamento de estoque completamente funcional, sem dependência de backend. Todos os dados são armazenados localmente no navegador usando localStorage.

## 🚀 Funcionalidades

- ✅ **Painel Geral**: Dashboard com estatísticas de estoque
- ✅ **Catálogo de Produtos**: Visualize e filtre todos os produtos
- ✅ **Controle de Estoque**: Ajuste quantidades em tempo real
- ✅ **Histórico de Movimentações**: Acompanhe todas as alterações
- ✅ **Armazenamento Local**: Dados persistem no navegador
- ✅ **Interface Responsiva**: Funciona em desktop e mobile

## 💾 Como Usar

1. Abra `estoque.html` no navegador
2. Clique em "Novo produto" para adicionar itens ao catálogo
3. Use a aba "Estoque" para ajustar quantidades
4. Visualize gráficos e histórico no "Painel Geral"

**Observação**: Os dados são salvos automaticamente no localStorage do seu navegador. Se você limpar o cache/cookies, os dados serão perdidos.

## 🌐 Deploy no Vercel

### Passo 1: Preparar o repositório
```bash
cd seu-diretório
git init
git add .
git commit -m "Initial commit"
```

### Passo 2: Enviar para GitHub
1. Crie um novo repositório no [GitHub](https://github.com/new)
2. Execute:
```bash
git remote add origin https://github.com/seu-usuario/seu-repositorio.git
git branch -M main
git push -u origin main
```

### Passo 3: Deploy no Vercel
1. Acesse [vercel.com](https://vercel.com)
2. Clique em "Import Project"
3. Conecte seu repositório GitHub
4. Clique em "Deploy"

**Pronto!** Seu site estará disponível em `seu-projeto.vercel.app`

## 📋 Dados de Exemplo

O sistema vem com 7 produtos de exemplo para facilitar testes:
- Roçadeira a Gasolina
- Motosserra
- Gerador a Diesel
- E mais...

## 💡 Dicas

- **Backup**: Exporte regularmente seus dados (console browser)
- **Compartilhamento**: Cada pessoa tem seu próprio banco de dados no navegador
- **Múltiplos Dispositivos**: Use em vários computadores/celulares de forma independente

## 🛠️ Tecnologia

- HTML5 + CSS3 + JavaScript vanilla
- localStorage para persistência
- Design responsivo e moderno
- Sem dependências externas

---

Desenvolvido com ❤️ para gerenciamento eficiente de estoque.
