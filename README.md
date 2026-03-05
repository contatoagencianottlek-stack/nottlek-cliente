# 🔷 N.O.T.T.L.E.K™ — Painel do Cliente

Painel de acompanhamento dos 30 dias de estruturação comercial.

---

## Como publicar na Vercel (passo a passo)

### PASSO 1 — Suba no GitHub

1. Acesse **github.com** e faça login
2. Clique em **New repository** (botão verde)
3. Nome: `nottlek-cliente`
4. Deixa como **Public**
5. Clica em **Create repository**
6. Na próxima tela, clica em **uploading an existing file**
7. **Arrasta todos os arquivos desta pasta** para a área de upload
   - Importante: inclui a pasta `src/` e o arquivo `package.json`
8. Clica em **Commit changes**

---

### PASSO 2 — Deploy na Vercel

1. Acesse **vercel.com** e clica em **Sign up with GitHub**
2. Autoriza a Vercel acessar seu GitHub
3. Clica em **Add New → Project**
4. Seleciona o repositório `nottlek-cliente`
5. Clica em **Deploy** (as configurações já estão corretas)
6. Aguarda 1-2 minutos

---

### PASSO 3 — Seu link está pronto

A Vercel vai gerar um link do tipo:
```
https://nottlek-cliente.vercel.app
```

Esse link você manda para o cliente acessar pelo celular ou computador.

---

## Como personalizar para cada cliente

Abra o arquivo `src/App.jsx` e edite as linhas no topo:

```js
const CLIENTE = {
  nome: "Nome do Cliente",        // ← troca aqui
  empresa: "Nome da Empresa",     // ← troca aqui
  inicio: "Março 2026",           // ← troca aqui
  prazo: "30 dias",
};
```

Salva, faz commit no GitHub — a Vercel atualiza o site automaticamente.

---

## Desenvolvido por

**Keltton Belizario** · Método N.O.T.T.L.E.K™  
Engenharia de Vendas para Integradoras Solares  
@okelttonbeli
