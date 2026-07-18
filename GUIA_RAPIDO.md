# 🎯 Guia Rápido - Central de Estoque

## ✅ O que foi feito

1. **Implementado armazenamento local** (localStorage)
   - Todos os dados são salvos no navegador
   - Sem necessidade de backend
   - Pronto para Vercel

2. **Configurado para deploy no Vercel**
   - Arquivo `vercel.json` adicionado
   - Roteamento automático configurado
   - Suporte para acesso direto

3. **Documentação completa**
   - README.md com instruções
   - package.json configurado
   - .gitignore para controle de versão

## 🚀 Para usar localmente

```bash
# Opção 1: Abrir direto no navegador
# Clique duas vezes em "estoque.html"

# Opção 2: Servidor local (Python 3)
python -m http.server 8000
# Abra http://localhost:8000/estoque.html
```

## 📤 Para fazer deploy no Vercel

### Passo 1: Git e GitHub
```bash
git init
git add .
git commit -m "Central de Estoque - Deploy inicial"
```

### Passo 2: Criar repositório no GitHub
- Vá para https://github.com/new
- Crie um novo repositório
- Copie o comando `git remote add` e execute

### Passo 3: Deploy Automático
- Acesse https://vercel.com
- Clique "Import Project"
- Conecte seu GitHub
- Clique "Deploy"
- Pronto! Seu site estará online em poucos segundos

## 💾 Dados do Sistema

O sistema vem com 7 produtos de exemplo. Para adicionar mais:
1. Clique em "Novo produto"
2. Preencha os dados
3. Clique em "Salvar produto"
4. Pronto! Dados salvos automaticamente

## ⚠️ Informações Importantes

- **Dados Locais**: Cada navegador/dispositivo tem seus próprios dados
- **Compartilhamento**: Para compartilhar dados entre equipes, exporte e importe manualmente
- **Backup**: Limpar cache do navegador apagará os dados (use backups)

## 🎨 Recursos

- ✅ Dashboard com gráficos em tempo real
- ✅ Filtros avançados de busca
- ✅ Histórico de movimentações
- ✅ Interface responsiva (mobile/desktop)
- ✅ Modo escuro preparado
- ✅ Sem JavaScript complexo (vanilla JS puro)

---

**Desenvolvido para funcionar 100% no navegador, sem qualquer dependência de servidor!**
