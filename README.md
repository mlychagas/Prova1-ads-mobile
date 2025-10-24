# 📱 Projeto: Gerenciador de Itens Mobile

## 📋 Documento de Requisitos Técnicos

**Empresa**: TechCorp Solutions  
**Projeto**: Sistema Mobile de Gerenciamento de Itens  
**Tipo**: Correção e Implementação de Funcionalidades  
**Horário de Início**: 19:00  
**Prazo de Entrega**: 20:00 (1 hora)  
**Horário Final**: 22:30 

---

## 🎯 Visão Geral do Projeto

A TechCorp Solutions está desenvolvendo um aplicativo mobile para gerenciamento de itens com sistema de autenticação. O projeto atual possui um código base com diversos erros que precisam ser identificados e corrigidos para que o sistema funcione corretamente.

### Objetivo
Implementar um aplicativo mobile funcional que permita:
- Autenticação de usuários (login/registro)
- Gerenciamento completo de itens (CRUD)
- Interface intuitiva e responsiva

---

## ⏰ Sistema de Entrega e Penalizações

### ⏱️ Cronograma
- **Início**: 19:00
- **Prazo Ideal**: 20:00 (1 hora)
- **Prazo Final**: 22:30

### 💰 Sistema de Penalização por Atraso

**Como funciona:**
- **Entrega pontual (até 20:00)**: Sem penalização
- **Atraso progressivo**: Penalização crescente conforme o tempo de atraso
- **Penalização máxima**: 40% para entregas próximas ao prazo final
- **Prazo final (22:30)**: Último momento aceito
- **Após prazo final**: Entrega não será aceita

**Observação**: O sistema de penalização é rigoroso e aplicado automaticamente. Recomenda-se fortemente a entrega no prazo ideal para evitar descontos na avaliação.

### ⚠️ Observações Importantes
- **Horário de referência**: Relógio do servidor da empresa
- **Entrega única**: Não serão aceitas reenvios após o prazo
- **Validação automática**: Sistema verifica horário de commit
- **Sem exceções**: Penalizações aplicadas rigorosamente

---

## 📱 Especificações Técnicas

### Stack Tecnológica
- **Frontend**: React Native + Expo
- **Navegação**: React Navigation
- **Backend**: API Node.js (fornecida)
- **Armazenamento**: AsyncStorage

### Arquitetura do Sistema
```
Mobile App (React Native)
    ↓
API Backend (Node.js)
    ↓
Database (Simulada)
```

---

## 📊 Fichas Técnicas Detalhadas

### FICHA TÉCNICA #001 - Sistema de Autenticação
**ID**: AUTH-001  
**Prioridade**: ALTA  
**Complexidade**: MÉDIA  

**Descrição Detalhada**:
Implementar sistema completo de autenticação com duas telas principais: Login e Registro. O sistema deve validar credenciais, gerenciar sessões e permitir navegação fluida entre as telas.

**Funcionalidades Esperadas**:
- Tela de login com campos de email e senha
- Tela de registro com campos de nome, email e senha
- Validação de dados de entrada
- Persistência de sessão do usuário
- Navegação entre telas de autenticação

---

### FICHA TÉCNICA #002 - Gerenciamento de Itens (CRUD)
**ID**: CRUD-001  
**Prioridade**: ALTA  
**Complexidade**: ALTA  

**Descrição Detalhada**:
Implementar operações completas de gerenciamento de itens com interface intuitiva. O sistema deve permitir criar, listar, editar e excluir itens com validações apropriadas.

**Funcionalidades Esperadas**:
- Listagem de todos os itens cadastrados
- Adição de novos itens ao sistema
- Edição de itens existentes
- Exclusão de itens com confirmação
- Validação de dados antes de salvar
- Interface responsiva para todas as operações

---

### FICHA TÉCNICA #003 - Navegação e Interface
**ID**: NAV-001  
**Prioridade**: MÉDIA  
**Complexidade**: BAIXA  

**Descrição Detalhada**:
Implementar sistema de navegação fluida entre todas as telas do aplicativo com transições suaves e gerenciamento de estado de navegação.

**Funcionalidades Esperadas**:
- Navegação fluida entre todas as telas
- Transições suaves entre telas
- Botões de navegação funcionais
- Gerenciamento correto do histórico de navegação
- Headers apropriados para cada tela

---

### FICHA TÉCNICA #004 - Validação e Tratamento de Erros
**ID**: VAL-001  
**Prioridade**: ALTA  
**Complexidade**: MÉDIA  

**Descrição Detalhada**:
Implementar sistema robusto de validação de dados e tratamento de erros para garantir estabilidade e boa experiência do usuário.

**Funcionalidades Esperadas**:
- Validação de dados de entrada em tempo real
- Tratamento adequado de erros de rede
- Tratamento de erros de validação
- Feedback visual para o usuário sobre erros
- Mensagens de erro claras e informativas

---

### FICHA TÉCNICA #005 - Integração com API
**ID**: API-001  
**Prioridade**: ALTA  
**Complexidade**: MÉDIA  

**Descrição Detalhada**:
Implementar integração completa com a API backend para todas as operações de autenticação e gerenciamento de itens.

**Funcionalidades Esperadas**:
- Integração com API backend para autenticação
- Integração com API backend para operações de itens
- Tratamento adequado de respostas da API
- Gerenciamento de estados de carregamento
- Tratamento de erros de conectividade

---

### FICHA TÉCNICA #006 - Interface e UX
**ID**: UI-001  
**Prioridade**: MÉDIA  
**Complexidade**: BAIXA  

**Descrição Detalhada**:
Implementar interface de usuário responsiva e intuitiva seguindo as especificações visuais fornecidas.

**Funcionalidades Esperadas**:
- Interface responsiva e intuitiva
- Componentes reutilizáveis e bem estruturados
- Paleta de cores consistente
- Feedback visual adequado para ações do usuário
- Layout adaptável a diferentes tamanhos de tela

---

## 🔧 Requisitos Funcionais

### RF001 - Sistema de Autenticação
**Descrição**: Implementar sistema completo de login e registro de usuários

**Critérios de Aceitação**:
- [ ] Tela de login com campos email e senha
- [ ] Tela de registro com campos nome, email e senha
- [ ] Validação de campos obrigatórios
- [ ] Navegação entre telas de login e registro
- [ ] Persistência de sessão do usuário

**Referência Visual**: ![Tela de Login](./prints/login.png) ![Tela de Registro](./prints/registrar.png)

### RF002 - Gerenciamento de Itens (CRUD)
**Descrição**: Implementar operações completas de gerenciamento de itens

**Critérios de Aceitação**:
- [ ] Listagem de todos os itens cadastrados
- [ ] Adição de novos itens
- [ ] Edição de itens existentes
- [ ] Exclusão de itens
- [ ] Interface responsiva e intuitiva

**Referência Visual**: 
- ![Lista de Itens](./prints/img_1.png)
- ![Adicionar Item](./prints/img_2.png)
- ![Editar Item](./prints/img_3.png)
- ![Interface Principal](./prints/img_4.png)

### RF003 - Navegação entre Telas
**Descrição**: Implementar navegação fluida entre todas as telas do aplicativo

**Critérios de Aceitação**:
- [ ] Navegação funcional entre Login, Registro e Home
- [ ] Botões de navegação funcionando corretamente
- [ ] Transições suaves entre telas
- [ ] Gerenciamento de estado de navegação

---

## 🐛 Problemas Identificados (Para Correção)

### Categoria 1: Erros de Sintaxe
- [ ] Imports incorretos ou faltando
- [ ] Nomes de componentes mal escritos
- [ ] Pontuação incorreta (ponto e vírgula, chaves, etc.)
- [ ] Extensões de arquivo incorretas

### Categoria 2: Erros de Lógica
- [ ] Funções mal implementadas
- [ ] Estados não gerenciados corretamente
- [ ] Navegação incorreta entre telas
- [ ] Validações ausentes ou incorretas

### Categoria 3: Inconsistências de Nomenclatura
- [ ] Variáveis com nomes diferentes para mesma função
- [ ] Componentes com nomes incorretos
- [ ] Props com nomes inconsistentes

### Categoria 4: Erros de Digitação
- [ ] Typos em nomes de arquivos
- [ ] Palavras mal escritas no código
- [ ] Comentários com erros ortográficos

---

## 🛠️ Ambiente de Desenvolvimento

### Pré-requisitos
- **Node.js** (versão 16 ou superior)
- **Expo CLI** instalado globalmente
- **Git** para controle de versão
- **Dispositivo móvel** com app Expo Go

### Configuração do Projeto

#### 1. Configuração da API Backend
```bash
# Extrair arquivo da API
unzip API/gerenciamento-itens-api.zip

# Navegar para pasta da API
cd gerenciamento-itens-api

# Instalar dependências
npm install

# Executar API
node app.js
```
---

## 📋 Checklist de Desenvolvimento Detalhado

### FASE 1: Análise e Identificação
**Objetivo**: Mapear todos os problemas existentes no código

#### AUTH-001 - Sistema de Autenticação
- [ ] Analisar telas de login e registro
- [ ] Verificar funcionamento da autenticação
- [ ] Identificar problemas de validação
- [ ] Verificar persistência de sessão
- [ ] Testar navegação entre telas

#### CRUD-001 - Gerenciamento de Itens
- [ ] Analisar tela principal e componentes
- [ ] Verificar operações de listagem
- [ ] Verificar operações de adição
- [ ] Verificar operações de edição
- [ ] Verificar operações de exclusão

#### NAV-001 - Navegação
- [ ] Testar navegação entre todas as telas
- [ ] Verificar botões de navegação
- [ ] Verificar transições entre telas
- [ ] Identificar problemas de roteamento

#### VAL-001 - Validação e Erros
- [ ] Testar validações de formulário
- [ ] Verificar tratamento de erros
- [ ] Testar feedback para o usuário
- [ ] Verificar mensagens de erro

#### API-001 - Integração
- [ ] Testar conectividade com API
- [ ] Verificar operações de autenticação
- [ ] Verificar operações de itens
- [ ] Testar tratamento de erros de rede

#### UI-001 - Interface
- [ ] Verificar layout das telas
- [ ] Testar responsividade
- [ ] Verificar consistência visual
- [ ] Comparar com referências fornecidas

---

### FASE 2: Correção e Implementação
**Objetivo**: Corrigir todos os erros identificados

#### Correções de Sintaxe
- [ ] Corrigir erros de sintaxe identificados
- [ ] Ajustar nomenclatura incorreta
- [ ] Corrigir formatação e pontuação
- [ ] Ajustar extensões de arquivo

#### Correções de Lógica
- [ ] Corrigir validações de dados
- [ ] Ajustar gerenciamento de estado
- [ ] Corrigir navegação entre telas
- [ ] Implementar tratamento de erros

#### Correções de Interface
- [ ] Ajustar estilos e layout
- [ ] Corrigir componentes faltantes
- [ ] Ajustar responsividade
- [ ] Corrigir paleta de cores

#### Correções de Integração
- [ ] Corrigir configuração da API
- [ ] Ajustar integração com backend
- [ ] Corrigir endpoints da API
- [ ] Ajustar tratamento de respostas

---

### FASE 3: Testes e Validação
**Objetivo**: Garantir que todas as funcionalidades estejam operacionais

#### Testes de Autenticação
- [ ] Testar login com credenciais válidas
- [ ] Testar login com credenciais inválidas
- [ ] Testar registro de novo usuário
- [ ] Testar validação de campos
- [ ] Testar persistência de sessão

#### Testes de CRUD
- [ ] Testar listagem de itens
- [ ] Testar adição de novo item
- [ ] Testar edição de item existente
- [ ] Testar exclusão de item
- [ ] Testar validações de formulário

#### Testes de Navegação
- [ ] Testar navegação entre telas
- [ ] Testar botões de voltar
- [ ] Testar transições suaves
- [ ] Testar gerenciamento de estado

#### Testes de Interface
- [ ] Testar responsividade
- [ ] Testar feedback visual
- [ ] Testar loading states
- [ ] Testar mensagens de erro

#### Testes de Integração
- [ ] Testar conectividade com API
- [ ] Testar tratamento de erros de rede
- [ ] Testar timeout de requisições
- [ ] Testar retry automático

---

### FASE 4: Entrega e Documentação
**Objetivo**: Preparar o projeto para entrega

#### Preparação do Código
- [ ] Remover console.logs desnecessários
- [ ] Limpar código comentado
- [ ] Verificar formatação consistente
- [ ] Validar que não há erros de lint

#### Preparação da Entrega
- [ ] Verificar que API está funcionando
- [ ] Testar aplicativo completo
- [ ] Preparar commit com mensagens descritivas
- [ ] Verificar que não há arquivos desnecessários

#### Documentação
- [ ] Atualizar README.md se necessário
- [ ] Documentar mudanças principais
- [ ] Verificar instruções de execução
- [ ] Confirmar critérios de entrega

---

## 📤 Critérios de Entrega

### Arquivos a Entregar
- ✅ Código fonte corrigido
- ✅ README.md atualizado
- ❌ **NÃO incluir**: pasta `API/`, `node_modules/`, arquivos temporários

### Formato de Entrega
- **Plataforma**: Git (GitHub/GitLab)
- **Branch**: `main` ou `develop`
- **Commit**: Mensagens descritivas das correções

### 🎯 Critérios de Qualidade
- **Funcionalidade**: 100% das funcionalidades operacionais
- **Código Limpo**: Sem erros de sintaxe ou lógica
- **Interface**: Conforme especificações visuais
- **Navegação**: Fluida e intuitiva

---

## 🎯 Critérios de Avaliação

| Critério | Peso | Descrição |
|----------|------|-----------|
| **Correção de Erros** | 40% | Todos os erros identificados e corrigidos |
| **Funcionalidade** | 30% | Aplicativo executando sem erros |
| **Interface** | 20% | Conformidade com especificações visuais |
| **Qualidade do Código** | 10% | Código limpo e bem estruturado |

---

## 📞 Suporte e Recursos

### Documentação Oficial
- [React Native Docs](https://reactnative.dev/docs/getting-started)
- [Expo Documentation](https://docs.expo.dev/)
- [React Navigation](https://reactnavigation.org/)

### Recursos de Referência
- Imagens de referência na pasta `prints/`
- Código base fornecido
- API backend funcional

---

## ⚠️ Observações Importantes

1. **Foco Principal**: Correção do código mobile, não desenvolvimento da API
2. **API Backend**: Apenas para consumo, não para modificação
3. **Testes**: Validar todas as funcionalidades após correções
4. **Interface**: Seguir exatamente as referências visuais fornecidas

---

**🚀 Boa sorte no desenvolvimento! Sucesso na entrega do projeto!**

*TechCorp Solutions - Departamento de Desenvolvimento Mobile*