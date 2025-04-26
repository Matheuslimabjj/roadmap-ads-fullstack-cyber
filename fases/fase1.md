# 📍 Fase 1 – Fundamentos da Web + Segurança

Bem-vindo à primeira fase da minha jornada! Aqui estou focando em entender os fundamentos da web e os primeiros conceitos de segurança, com direito a mão na massa. 🤓

---

## 🎯 Objetivos desta fase

- [x] Entender o básico de HTML, CSS e JavaScript
- [x] Criar um formulário simples com envio de dados
- [x] Aprender o que é XSS e como ele funciona
- [x] Criar um mini projeto com vulnerabilidade simulada

---

## 💡 O que estudei

### 🧱 HTML e CSS
- Estrutura básica de uma página
- Elementos como `<form>`, `<input>`, `<button>`
- Estilização com classes, cores, margens, paddings

### ⚙️ JavaScript
- Manipulação do DOM com `document`
- `window.location.search` para pegar parâmetros da URL
- Uso de `document.write()` (e por que ele é perigoso 😅)

---

## 🧪 Projeto da Fase

**🔗 [`xss-lab`](https://github.com/SEU_USUARIO/xss-lab)**  
Simulei uma aplicação com vulnerabilidade XSS para entender como o JavaScript pode ser explorado se os dados do usuário não forem validados.

> Exemplo: digite `<script>alert("XSS!")</script>` no campo e veja o que acontece.

---

## 🧠 Anotações e prints

Veja minhas anotações e prints no repositório [`notes-cybersec`](https://github.com/SEU_USUARIO/notes-cybersec) para entender melhor como funciona a vulnerabilidade XSS.

---

## 🧩 Aprendizados-chave

- Qualquer entrada de usuário deve ser validada ou escapada.
- Formulários podem ser explorados se não forem tratados corretamente.
- Segurança deve ser pensada desde o início do desenvolvimento.

---

## ⏭️ Próximo passo: Fase 2 – Full Stack + Segurança
Nesta próxima fase vou aprender backend com Express e PostgreSQL, além de autenticação e proteção de APIs.