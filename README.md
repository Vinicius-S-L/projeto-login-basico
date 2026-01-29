# 🔐 Sistema de Login Básico

## 📋 O Que É Este Projeto?

Este é um **formulário de login** (tela de acesso) simples e bonito que funciona em qualquer aparelho:
- 📱 Celulares
- 📲 Tablets  
- 💻 Computadores

O design se ajusta automaticamente ao tamanho da tela, deixando tudo fácil de usar e bonito visualmente!

---

## � Como Funciona? (Bem Simples!)

### **Passo 1: Usuário Abre a Página**
O cliente abre a página no navegador e vê uma tela bonita com:
- Uma imagem de fundo (segurança/cadeado)
- Um quadro branco no meio com o formulário
- Campos para digitar o usuário/email
- Campo para digitar a senha
- Botão "Entrar"
- Link "Esqueci a Senha"

### **Passo 2: Usuário Preenche os Dados**
```
1. Clica no campo de e-mail/usuário
2. Digita seu e-mail ou nome
3. Clica no campo de senha
4. Digita sua senha (aparece como pontos para privacidade)
5. Clica em "Entrar"
```

### **Passo 3: Validação Automática**
A página verifica automaticamente:
- ✅ Se o e-mail/usuário foi preenchido
- ✅ Se a senha tem no mínimo 8 caracteres
- ✅ Se está tudo correto, envia para o servidor

### **Passo 4: Processamento no Servidor**
Os dados chegam a um arquivo (registro.php) que:
- Verifica se o usuário existe
- Confirma se a senha está correta
- Libera ou nega o acesso

---

## 🎨 Visual e Cores

O projeto usa uma paleta profissional com **tons de azul** (transmite segurança):

| Elemento | Cor | Para Quê |
|----------|-----|----------|
| Fundo | Azul bem escuro | Dá destaque ao formulário |
| Botões | Azul médio | Convida a clicar |
| Campos de input | Azul bem claro | Fácil de ver onde digitar |
| Bordas | Marrom escuro | Toque elegante |

**Fonte usada**: Estilo clássico e elegante (Georgia, Cambria)

---

## 📱 Funciona em Qualquer Tela!

O projeto é **responsivo**, ou seja, se adapta automaticamente:

### **No Celular (Mobile)**
```
┌────────────┐
│  Imagem    │  ← Cadeado de segurança
│  bonita    │
├────────────┤
│   Login    │  ← Título
│ E-mail     │  ← Campo
│ Senha      │  ← Campo  
│ [Entrar]   │  ← Botão
└────────────┘
```

### **No Tablet (Tela Média)**
```
┌──────────────────────────────┐
│  Imagem  │  Login             │
│ Cadeado  │  E-mail []         │
│   bonita │  Senha  []         │
│          │  [Entrar]          │
└──────────────────────────────┘
```

### **No Computador (Desktop)**
```
┌───────────────────────────────────────┐
│  Imagem Bonita  │  ⭐ Formulário Grande ⭐  │
│  (Lado Direito) │  E-mail []              │
│                 │  Senha  []              │
│                 │  [Entrar] [Esqueci]     │
└───────────────────────────────────────┘
```

---

## 🛠️ O Que Foi Usado para Fazer?

Tecnicamente falando, usamos 3 ingredientes principais:

### **1️⃣ HTML (A Estrutura)**
É como o "esqueleto" da página. Define:
- Onde colocar os campos
- Onde colocar os botões
- Validações básicas (obrigatório, mínimo de caracteres)
- Ícones de segurança (cadeado e chave)

### **2️⃣ CSS (O Visual)**
É o "maquiador" da página. Controla:
- Cores (tons de azul)
- Tamanhos
- Arredondamentos
- Efeitos ao passar o mouse
- Animações suaves

### **3️⃣ Media Queries (O Ajuste Automático)**
É como o "maestro" que coordena tudo. Diz:
- "Se for celular, faça assim..."
- "Se for tablet, faça diferente..."
- "Se for computador, faça de outra forma..."

---

## 🔒 É Seguro?

**Segurança básica**: ✅ SIM
- A senha aparece como pontos (ninguém vê o que você digita)
- A página valida antes de enviar

**Segurança completa**: ⚠️ Precisa do servidor
- O PHP (no servidor) valida tudo de novo
- A senha é criptografada
- Usa conexão HTTPS (fechada)

---

## 📁 Arquivo e Pastas

```
📂 projeto-login-basico
 ├─ 📄 index.html           ← A página em si
 ├─ 📄 README.md            ← Este arquivo (instruções)
 ├─ 📄 LICENSE              ← Permissão de uso
 │
 ├─ 📂 estilos/             ← Pasta com as cores e design
 │  ├─ style.css           ← Estilos para telas normais
 │  └─ media-query.css     ← Ajustes para diferentes telas
 │
 └─ 📂 imagens/             ← Pasta com fotos
    ├─ favicon.svg          ← Ícone da aba do navegador
    └─ pexels-pixabay...    ← Imagem de fundo bonita
```

---

## 👨‍💻 Criado por

**Vinicius Silva de Lima**  
Janeiro de 2026

**Status**: ✅ Pronto para usar!
