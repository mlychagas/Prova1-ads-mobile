# Prova de Identificação e Correção de Código: Gerenciador de Itens

## 📋 Instruções Importantes

**Nesta prova, você deverá identificar e corrigir erros em um código que implementa um aplicativo mobile com sistema de autenticação e CRUD de itens.**

### ✅ O que é permitido:
- Consultar materiais de apoio (apostilas, slides, PDFs, cadernos)
- Usar recursos online para pesquisa
- Consultar documentação oficial

### ❌ O que é proibido:
- Comunicar-se com outros alunos
- Compartilhar códigos de qualquer forma
- Receber ajuda externa não autorizada

⚠️ **O professor tem plena autonomia para avaliar e aplicar as devidas sanções em caso de descumprimento das regras.**

---

## 🎯 Objetivo da Prova

Você deve corrigir todos os erros presentes no código para que o aplicativo funcione corretamente, implementando:

1. **Sistema de Autenticação** (Login e Registro)
2. **CRUD de Itens** (Criar, Listar, Editar, Deletar)
3. **Navegação entre telas**

---

## 📱 Funcionalidades Esperadas

O aplicativo deve possuir as seguintes telas e funcionalidades:

### 1. Tela de Login (`LoginScreen`)
- Campos para email e senha
- Botão de login
- Link para tela de registro
- **Referência visual**: ![Tela de Login](./prints/login.png)

### 2. Tela de Registro (`RegisterScreen`)
- Campos para nome, email e senha
- Botão de registro
- Link para voltar ao login
- **Referência visual**: ![Tela de Registro](./prints/registrar.png)

### 3. Tela Principal (`HomeScreen`)
- Lista de itens cadastrados
- Botão para adicionar novo item
- Funcionalidades de editar e excluir itens
- **Referência visual**: 
  - ![Tela Principal 1](./prints/img_1.png)
  - ![Tela Principal 2](./prints/img_2.png)
  - ![Tela Principal 3](./prints/img_3.png)
  - ![Tela Principal 4](./prints/img_4.png)

---

## 🔧 Tipos de Erros a Identificar

Analise o código e procure por:

1. **Erros de Sintaxe**
   - Imports incorretos
   - Nomes de componentes mal escritos
   - Pontos e vírgulas faltando

2. **Erros de Lógica**
   - Funções mal implementadas
   - Estados não gerenciados corretamente
   - Navegação incorreta

3. **Inconsistências de Nomenclatura**
   - Variáveis com nomes diferentes
   - Componentes com nomes incorretos

4. **Erros de Digitação**
   - Typos em nomes de arquivos
   - Palavras mal escritas

---

---

## 🚀 API Backend (Necessária para o funcionamento)

**IMPORTANTE**: Antes de executar o aplicativo mobile, você precisa iniciar a API backend.

### Configurando a API

1. **Extraia o arquivo** `API/gerenciamento-itens-api.zip`
2. **Entre na pasta** da API extraída
3. **Instale as dependências**:
   ```bash
   npm install
   ```
4. **Execute a API**:
   ```bash
   node app.js
   ```

⚠️ **Nota**: A API não é o foco da prova - você só precisa executá-la para que o aplicativo mobile possa consumir os dados. O foco da prova é corrigir os erros no código do aplicativo mobile.

---

## 📝 Como Realizar a Prova

1. **Configure a API** (siga as instruções acima)
2. **Analise** todos os arquivos do projeto mobile
3. **Identifique** os erros presentes no código
4. **Corrija** cada erro encontrado
5. **Teste** se o aplicativo funciona corretamente
6. **Verifique** se todas as funcionalidades estão operacionais

### Dicas Importantes:
- Use as imagens de referência acima para ver como as telas devem ficar
- Teste cada funcionalidade após fazer as correções
- Verifique se a navegação entre telas está funcionando
- Confirme se o CRUD de itens está completo

---

## 📤 Entrega

- Envie o código corrigido via **Git**
- Certifique-se de que todos os erros foram corrigidos
- O projeto deve estar funcional e executável

---

## 🎯 Critérios de Avaliação

- **Correção de erros**: Todos os erros identificados e corrigidos
- **Funcionalidade**: Aplicativo executando sem erros
- **Completude**: Todas as funcionalidades implementadas
- **Qualidade do código**: Código limpo e bem estruturado

---

**🚀 Boa prova! Sucesso na correção do código!**