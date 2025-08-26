# MyFinance 💸

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/c3saroliveira/maratona-discover/blob/main/LICENSE)
[![Netlify Status](https://api.netlify.com/api/v1/badges/1e0665b2-cb18-4d84-8911-71060b308d2e/deploy-status)](https://myfincance-onilio99.netlify.app)

## 📋 Sobre o Projeto

**MyFinance** é uma aplicação web para **controle financeiro pessoal** desenvolvida com tecnologias web fundamentais. O sistema permite o registro e acompanhamento de receitas e despesas de forma simples e intuitiva, oferecendo uma visão clara do saldo financeiro atual do usuário.

🔗 **Demo:** [https://myfincance-onilio99.netlify.app](https://myfincance-onilio99.netlify.app)

## ✨ Funcionalidades

- 💰 **Registro de Transações** - Adicione entradas e saídas financeiras
- 📊 **Cálculo Automático** - Visualize receitas, despesas e saldo total
- 🗂️ **Lista de Transações** - Histórico completo com descrição, valor e data
- ❌ **Remoção de Registros** - Delete transações indesejadas
- 💾 **Persistência Local** - Dados salvos no localStorage do navegador
- 📱 **Interface Responsiva** - Funciona em desktop e dispositivos móveis

## 🖼️ Layout da Aplicação

### Tela Principal
Interface principal mostrando o resumo financeiro com cards de entradas, saídas e total, além da lista de transações.

![Tela Principal](https://github.com/c3saroliveira/maratona-discover/blob/main/images/myfinance.PNG)

### Modal de Nova Transação
Modal para adicionar novas transações financeiras com campos para descrição, valor e categoria (entrada/saída).

![Modal de Transação](https://github.com/c3saroliveira/maratona-discover/blob/main/images/myfinance_modal.PNG)

### Visão com Saldo Total
Demonstração do cálculo automático do saldo total baseado nas transações registradas, com indicadores visuais de status.

![Saldo Total](https://github.com/c3saroliveira/maratona-discover/blob/main/images/myfinance_total.PNG)

## 🚀 Tecnologias Utilizadas

### Frontend
- **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML)** - Estruturação semântica da aplicação
- **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS)** - Estilização e layout responsivo
- **[JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)** - Lógica de negócio e interatividade

### Recursos Utilizados
- **Local Storage** - Persistência de dados no navegador
- **DOM Manipulation** - Interação dinâmica com elementos da página
- **CSS Grid & Flexbox** - Layout moderno e responsivo
- **Modal System** - Interface de diálogo para entrada de dados

## 🌐 Deploy e Hospedagem

- **Frontend:** [Netlify](https://netlify.com/) - Hospedagem estática com deploy contínuo

## 📦 Como Executar o Projeto

### Execução Local
```bash
# Clone o repositório
git clone https://github.com/c3saroliveira/maratona-discover

# Acesse a pasta do projeto
cd maratona-discover

# Abra o arquivo index.html no seu navegador
# Ou utilize um servidor local como Live Server (VS Code)
```

### Servidor de Desenvolvimento
```bash
# Se você tem Python instalado
python -m http.server 8000

# Se você tem Node.js instalado
npx serve .

# Acesse http://localhost:8000 no seu navegador
```

## 🎯 Conceitos Aplicados

- **Manipulação do DOM** - Criação e modificação dinâmica de elementos
- **Event Listeners** - Captura de eventos de formulário e cliques
- **Local Storage API** - Armazenamento persistente de dados
- **CSS Moderno** - Grid, Flexbox e variáveis CSS
- **Programação Funcional** - Uso de métodos de array (map, reduce, filter)
- **Responsive Design** - Layout adaptável para diferentes telas
- **Modularização** - Organização do código em funções específicas

## 📱 Responsividade

A aplicação foi desenvolvida com **mobile-first approach**, garantindo uma experiência otimizada em:
- 📱 Smartphones (320px+)
- 📱 Tablets (768px+)  
- 💻 Desktop (1024px+)

## 📄 Licença

Este projeto está sob licença MIT. Veja o arquivo [LICENSE](https://github.com/c3saroliveira/maratona-discover/blob/main/LICENSE) para mais detalhes.

## 👨‍💻 Autor

**Júlio Guimarães**
- GitHub: [@ocesar9](https://github.com/ocesar9)
- LinkedIn: [Seu perfil LinkedIn](https://linkedin.com/in/seu-perfil)

---

⭐ Se este projeto te ajudou, deixe uma estrela no repositório!
