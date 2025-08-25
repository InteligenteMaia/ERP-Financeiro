<!-- 
🎨 Template de Pull Request - ERP Financeiro
💜 Obrigado por contribuir com nosso projeto!
📝 Preencha as seções abaixo para agilizar a revisão
-->

# <div align="center">🚀 Pull Request</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=150&section=header&text=Pull%20Request&fontSize=30&fontColor=fff&animation=twinkling&fontAlignY=35&desc=ERP%20Financeiro%20•%20Equipe%207&descAlignY=55&descSize=16" width="100%"/>
</div>

<div align="center">
  
  [![PR Type](https://img.shields.io/badge/PR_Type-Feature-blue?style=for-the-badge&logo=github&logoColor=white&labelColor=1a1a2e&color=00d4ff)]()
  [![Status](https://img.shields.io/badge/Status-Ready_for_Review-green?style=for-the-badge&logo=statuspage&logoColor=white&labelColor=1a1a2e&color=00ff88)]()
  [![Priority](https://img.shields.io/badge/Priority-Medium-yellow?style=for-the-badge&logo=fire&logoColor=white&labelColor=1a1a2e&color=ffd700)]()
  
</div>

---

## 📋 **Descrição**

<!-- 
Forneça uma descrição clara e concisa das mudanças.
Explique o problema que está sendo resolvido ou a feature sendo adicionada.
-->

### **🎯 O que este PR faz?**

> Descreva em 1-2 frases o objetivo principal deste PR

### **🔗 Issue Relacionada**

Fixes #(issue number)
<!-- Ou use: Closes, Resolves, Related to -->

---

## 🎨 **Tipo de Mudança**

<!-- Marque com "x" todas as opções aplicáveis -->

<table>
  <tr>
    <td>
      
- [ ] 🐛 **Bug fix** (correção que resolve um problema)
- [ ] ✨ **New feature** (nova funcionalidade)
- [ ] 💔 **Breaking change** (mudança que quebra compatibilidade)
      
</td>
<td>
      
- [ ] 📚 **Documentation** (apenas documentação)
- [ ] 🎨 **Style** (formatação, sem mudança de lógica)
- [ ] ♻️ **Refactoring** (refatoração de código)
      
</td>
<td>
      
- [ ] 🚀 **Performance** (melhoria de performance)
- [ ] 🧪 **Test** (adição ou correção de testes)
- [ ] 🔧 **Chore** (outras mudanças)
      
</td>
  </tr>
</table>

---

## 📸 **Screenshots / Vídeos**

<!-- 
Se aplicável, adicione screenshots ou vídeos das mudanças visuais.
Use a sintaxe: ![descrição](url-da-imagem)
Ou arraste e solte imagens aqui
-->

<details>
<summary><b>🖼️ Ver Screenshots</b></summary>

### **Antes:**
> Adicione screenshot do estado anterior (se aplicável)

### **Depois:**
> Adicione screenshot do estado atual

</details>

---

## ✅ **Checklist**

<!-- Marque com "x" todos os itens completados -->

### **📝 Código & Qualidade**

- [ ] 💻 Meu código segue o **style guide** do projeto
- [ ] 👀 Fiz **self-review** do meu código
- [ ] 💬 Adicionei **comentários** em áreas complexas
- [ ] 📚 Atualizei a **documentação** (se necessário)
- [ ] ⚠️ Sem **warnings** no console
- [ ] 🔄 **Sincronizado** com a branch main/master

### **🧪 Testes**

- [ ] ✅ Testes **existentes** passando
- [ ] 🆕 **Novos testes** adicionados (para features/fixes)
- [ ] 📊 **Cobertura** mantida ou aumentada
- [ ] 🔍 Testado **manualmente** as mudanças

### **🚀 Deploy & Performance**

- [ ] 📦 **Build** passando sem erros
- [ ] 🎯 Sem **impacto negativo** na performance
- [ ] 📱 Testado em **diferentes dispositivos** (se UI)
- [ ] 🌐 Funciona em **diferentes browsers** (se aplicável)

---

## 🧪 **Como Testar**

<!-- 
Forneça instruções claras de como testar suas mudanças.
Seja específico sobre configurações, dados de teste, etc.
-->

### **📋 Passos para Reproduzir**

1. Faça checkout desta branch
2. Execute `npm install` para instalar dependências
3. Execute `npm run dev` para iniciar o servidor
4. Navegue até `http://localhost:3000/...`
5. ...

### **🔍 Casos de Teste**

<!-- Liste os principais cenários que devem ser testados -->

- [ ] **Caso 1:** Descrição do teste
- [ ] **Caso 2:** Descrição do teste
- [ ] **Caso 3:** Descrição do teste

---

## 💭 **Notas Adicionais**

<!-- 
Informações extras que os revisores devem saber.
Decisões de design, trade-offs, problemas conhecidos, etc.
-->

<details>
<summary><b>📝 Notas para Revisores</b></summary>

> Adicione aqui qualquer contexto adicional ou explicações específicas

</details>

---

## 🔄 **Dependencies**

<!-- Liste PRs ou issues que precisam ser merged primeiro -->

- [ ] Depende do PR #___
- [ ] Bloqueia o PR #___

---

## 📊 **Impacto**

### **🎯 Áreas Afetadas**

<!-- Marque as áreas do sistema impactadas -->

<table>
  <tr>
    <td>
      
**Frontend:**
- [ ] Dashboard
- [ ] Relatórios
- [ ] Fluxo de Caixa
- [ ] Autenticação
      
</td>
<td>
      
**Backend:**
- [ ] API Routes
- [ ] Database
- [ ] Authentication
- [ ] Services
      
</td>
<td>
      
**DevOps:**
- [ ] CI/CD
- [ ] Docker
- [ ] Environment
- [ ] Scripts
      
</td>
  </tr>
</table>

### **⚠️ Breaking Changes**

<!-- Se houver breaking changes, descreva o impacto e como migrar -->

<details>
<summary><b>Ver Breaking Changes (se aplicável)</b></summary>

```diff
- Código antigo que não funcionará
+ Novo código necessário
```

**Migration Guide:**
1. Passo 1...
2. Passo 2...

</details>

---

## 🏷️ **Labels Sugeridas**

<!-- 
O revisor deve adicionar estas labels ao PR:
enhancement, bug, documentation, testing, refactor, etc.
-->

`enhancement` `needs-review` `frontend` `backend` `priority-medium`

---

## 📝 **Definition of Done**

<!-- Todos devem estar marcados para o PR ser considerado pronto -->

- [ ] ✅ Código implementado e funcionando
- [ ] 📚 Documentação atualizada
- [ ] 🧪 Testes escritos e passando
- [ ] 👥 Code review aprovado
- [ ] 🚀 Pronto para deploy

---

<div align="center">

### **👥 Revisores Sugeridos**

<!-- @mention dos membros da equipe que devem revisar -->

@michael @larissa @najla @lucas @rubens @nathalia @felipe @thaynara

</div>

---

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">
</div>

<div align="center">
  
  ### **📊 Status do PR**
  
  [![CI/CD](https://img.shields.io/badge/CI/CD-Checking...-yellow?style=for-the-badge&logo=githubactions&logoColor=white&labelColor=1a1a2e)]()
  [![Tests](https://img.shields.io/badge/Tests-Running...-yellow?style=for-the-badge&logo=jest&logoColor=white&labelColor=1a1a2e)]()
  [![Coverage](https://img.shields.io/badge/Coverage-Calculating...-yellow?style=for-the-badge&logo=codecov&logoColor=white&labelColor=1a1a2e)]()
  
</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=100&section=footer&fontSize=20&fontColor=fff&animation=twinkling" width="100%"/>
  
  ### **💜 Obrigado pela Contribuição!**
  
  **⭐ Equipe 7 - ERP Financeiro ⭐**
  
</div>

<!-- 
🎯 Dicas para um PR perfeito:
- Mantenha o PR pequeno e focado
- Escreva mensagens de commit claras
- Responda rapidamente aos comentários
- Teste tudo antes de marcar como ready
- Seja gentil e profissional
-->
