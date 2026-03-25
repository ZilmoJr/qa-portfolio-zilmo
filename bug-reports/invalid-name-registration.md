# 🐞 Bug Report — Campo nome aceita caracteres especiais inválidos no cadastro

## 📌 Descrição
Durante o cadastro de usuário, o sistema permite inserir nomes iniciando com caracteres especiais (ex: @), o que pode gerar dados inconsistentes.

## 🧪 Teste adicional
Testado também com:
- Nome iniciando com número
- Nome vazio
---

## 🔁 Passos para reproduzir
1. Acessar página de cadastro
2. No campo "Nome", inserir "@João"
3. Preencher os demais campos corretamente
4. Finalizar cadastro

---

## ✅ Resultado esperado
O sistema deve validar o campo nome e não permitir caracteres especiais no início, exibindo mensagem de erro.

---

## ❌ Resultado atual
O sistema aceita o nome com caractere especial e permite o cadastro normalmente.

---

## ⚠️ Severidade
Média

---

## 🌐 Ambiente
- Navegador: Chrome
- Sistema: Windows
- Data: (coloca hoje)

---

## 🧠 Impacto
Pode gerar dados inválidos no sistema, afetando relatórios, integrações e experiência do usuário.

---

## 💡 Sugestão
Implementar validação no campo nome para aceitar apenas letras e formatos válidos.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/26a3460c-2ee4-4aba-8647-647160c7d8e8" />

