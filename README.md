# 🤝 ONG LAÇOS - Organização Não Governamental

> Pequenas ações. Grandes transformações.

## 📋 Visão Geral do Projeto

ONG LAÇOS é uma organização social dedicada a transformar vidas através de iniciativas comunitárias solidárias. Este é um **website profissional responsivo** desenvolvido com HTML5, CSS3 e JavaScript vanilla, sem dependências externas, criado para apresentar os projetos da organização e facilitar o recrutamento de voluntários.

O site funciona como plataforma de engajamento, permitindo que visitantes conheçam os projetos da ONG e se cadastrem como voluntários de forma simples e segura.

---

## 🎯 Sobre a ONG LAÇOS

### 🌟 Nossa Missão
Promover transformação social através de ações colaborativas que fortalecem os vínculos comunitários e criam oportunidades de apoio mútuo.

### 👁️ Nossa Visão
Ser uma referência em mobilização comunitária, inspirando ações solidárias que geram impacto positivo duradouro na sociedade.

### 💡 Nossos Valores
- **Solidariedade**: Compromisso com o bem-estar coletivo
- **Integridade**: Transparência e autenticidade em nossas ações
- **Inclusão**: Espaço acolhedor para todos
- **Sustentabilidade**: Impacto duradouro e responsável

---

## 🏗️ Estrutura do Projeto

```
projetoFaculdade/
├── index.html          # Página inicial (landing page)
├── projetos.html       # Galeria de projetos
├── cadastro.html       # Formulário de cadastro de voluntários
├── style.css           # Estilos e responsividade
├── README.md           # Documentação do projeto
├── .gitignore          # Arquivos ignorados pelo Git
└── img/
    └── logo.png        # Logo da ONG LAÇOS
```

---

## 📄 Páginas do Website

### 1️⃣ **index.html** - Página Inicial
**Objetivo:** Apresentar a ONG e suas iniciativas de forma atrativa.

**Conteúdo:**
- Header com navegação sticky (fixa no topo)
- Seção de introdução com título "LAÇOS" e call-to-action
- Seção "Foco" com Missão, Visão e Valores
- Seção de diferencial com botão para voluntariado
- Footer com informações de copyright

**Funcionalidades:**
- ✅ Menu de navegação responsivo
- ✅ Logo clicável para retornar à página inicial
- ✅ Links para "Projetos" e "Seja Voluntário"
- ✅ Design moderno com gradientes

---

### 2️⃣ **projetos.html** - Galeria de Projetos
**Objetivo:** Detalhar os 4 principais projetos da ONG.

**Projetos Apresentados:**

1. **Mesa Solidária**
   - Alimentação e apoio nutricional para pessoas em situação de vulnerabilidade
   - Descrição: Iniciativa que busca garantir segurança alimentar através de refeições solidárias

2. **Caderno Aberto**
   - Educação e acesso ao conhecimento
   - Descrição: Programa focado em alfabetização e educação complementar

3. **Inverno Acolhedor**
   - Assistência em períodos de frio intenso
   - Descrição: Campanha de arrecadação de roupas e cobertores para pessoas em situação de rua

4. **Tempo Presente**
   - Apoio emocional e social
   - Descrição: Iniciativa de acompanhamento psicossocial e conexão comunitária

**Funcionalidades:**
- ✅ Cards com imagem, título, descrição e como ajudar
- ✅ Seção de Call-to-Action para voluntariado
- ✅ Design elegante com bordas customizadas

---

### 3️⃣ **cadastro.html** - Formulário de Cadastro
**Objetivo:** Capturar informações de voluntários de forma estruturada e segura.

**Seções do Formulário:**

#### 📋 Seus Dados
- Nome Completo (obrigatório)
- E-mail (obrigatório, com validação)
- CPF (obrigatório, com algoritmo de validação e máscara)
- Telefone (obrigatório, com máscara automática)

#### 📍 Onde Você Está
- CEP (obrigatório, com máscara automática)
- Endereço (obrigatório)
- Número (obrigatório)
- Complemento (opcional)
- Cidade (obrigatório)
- Estado (obrigatório, select com 27 opções brasileiras)

#### 🤲 Como Você Quer Ajudar
- **Área de Interesse** (mínimo 1 obrigatório):
  - Mesa Solidária
  - Caderno Aberto
  - Inverno Acolhedor
  - Tempo Presente

- **Disponibilidade** (obrigatório):
  - Segunda a Sexta
  - Finais de Semana
  - Flexível
  - Eventualmente

- **Tipo de Participação** (obrigatório):
  - Doador
  - Voluntário
  - Ambos

#### ✅ Consentimento
- Checkbox com texto de autorização para comunicação e participação em projetos

---

## 🎨 Design e Identidade Visual

### Paleta de Cores Personalizada
A ONG LAÇOS utiliza uma paleta sofisticada e acolhedora:

| Cor | Código | Uso |
|-----|--------|-----|
| Azul Petróleo | `#0F3D3E` | Cores primárias, headings, borders |
| Verde Sálvia | `#A7BFA7` | Acentos, hover effects, seções |
| Rosa Suave | `#E7C9C1` | Call-to-actions, gradientes |
| Areia | `#EDE5D9` | Background secundário, inputs |
| Creme | `#FAF8F3` | Background principal, cards |

### Tipografia
- **Headings e Títulos:** Inter (400-700 weights)
- **Body Text e Parágrafos:** Poppins (400-700 weights)
- **Fonte:** Importadas do Google Fonts para máxima compatibilidade

### Efeitos Visuais
- ✅ Gradientes lineares 135deg em headers e CTAs
- ✅ Box-shadows para profundidade
- ✅ Transições suaves em hover
- ✅ Border-radius 8px para elementos suavizados
- ✅ Transform translateY para efeitos de elevação

---

## ✨ Funcionalidades Principais

### 🔐 Validação de Formulário
O formulário implementa validações robustas em tempo real:

#### **CPF**
- ✅ Máscara automática: `000.000.000-00`
- ✅ Algoritmo de validação: verifica dois dígitos verificadores
- ✅ Rejeita CPF com todos dígitos iguais
- ✅ Feedback visual com borda vermelha em caso de erro

#### **E-mail**
- ✅ Validação por regex
- ✅ Verifica formato padrão: `usuario@dominio.com`

#### **Telefone**
- ✅ Máscara automática: `(11) 99999-9999`
- ✅ Aceita 10 ou 11 dígitos
- ✅ Validação de comprimento

#### **CEP**
- ✅ Máscara automática: `00000-000`
- ✅ Validação de 8 dígitos

#### **Campos Obrigatórios**
- ✅ Marca com asterisco (*)
- ✅ Valida antes de enviar
- ✅ Mensagens de erro claras

#### **Área de Interesse**
- ✅ Requer seleção de mínimo 1 opção
- ✅ Valida quantidade de checkboxes marcados

### 🎯 Mascaramento Automático de Entrada
Todos os campos que aceitam números possuem mascaramento em tempo real:
- Remove automaticamente caracteres não-numéricos
- Formata conforme digita
- Limita quantidade máxima de caracteres
- Melhora significativamente a UX

### 📱 Responsividade Total
O site é totalmente responsivo com breakpoints em:
- **Desktop:** 1200px+ (layout completo)
- **Tablet:** 768px - 1199px (layout ajustado)
- **Mobile:** até 767px (layout otimizado para toque)

---

## 🚀 Tecnologias Utilizadas

| Tecnologia | Versão | Propósito |
|------------|--------|----------|
| HTML5 | 2024 | Estrutura semântica e acessibilidade |
| CSS3 | 2024 | Estilos, layouts flex/grid, media queries |
| JavaScript Vanilla | ES6+ | Validação, mascaramento, interatividade |
| Google Fonts | Última | Inter e Poppins |
| Git | 2.x | Controle de versão |
| Python | 3.x | Servidor local de desenvolvimento |

**Nenhuma dependência externa ou framework!** 🎉

---

## 📊 Recursos Técnicos

### Event Listeners e JavaScript
- ✅ Input listeners para mascaramento em tempo real
- ✅ Blur listeners para validação ao sair do campo
- ✅ Submit listener para validação completa do formulário
- ✅ Sem jQuery, sem frameworks, código 100% vanilla

### CSS Features
- ✅ CSS Variables para fácil manutenção de temas
- ✅ Flexbox para layouts responsivos
- ✅ Media queries para diferentes dispositivos
- ✅ Gradientes lineares para estética moderna
- ✅ Transforms e transitions para interatividade

### SEO e Acessibilidade
- ✅ Meta tags adequadas
- ✅ Title e Description únicos por página
- ✅ Favicon configurado
- ✅ Atributos alt em imagens
- ✅ Labels associados em formulários

---

## 🛠️ Como Rodar o Projeto

### Pré-requisitos
- Python 3.x instalado
- Navegador moderno (Chrome, Firefox, Safari, Edge)
- Git para clonar o repositório

### Passo 1: Clonar o Repositório
```bash
git clone https://github.com/Fejluiza/ong_lacosorganizacion.git
cd projetoFaculdade
```

### Passo 2: Iniciar o Servidor Local
```bash
python3 -m http.server 8000
```

### Passo 3: Acessar no Navegador
```
http://localhost:8000
```

### Passo 4: Navegar pelo Site
- **Página Inicial:** http://localhost:8000/index.html
- **Projetos:** http://localhost:8000/projetos.html
- **Cadastro:** http://localhost:8000/cadastro.html

---

## 📝 Fluxo de Dados do Formulário

```
1. Usuário preenche formulário
   ↓
2. Event listener detecta input (mascaramento em tempo real)
   ↓
3. Usuário sai do campo (blur event)
   ↓
4. Validação individual com feedback visual
   ↓
5. Usuário clica "Quero fazer parte"
   ↓
6. Form submit disparado
   ↓
7. Validação completa (todos os campos)
   ↓
8. Alerta com mensagem de sucesso ou erro
```

---

## 🔍 Detalhes de Validação

### Validação CPF (Algoritmo Oficial)
O CPF é validado usando o algoritmo oficial brasileira:
- Calcula primeiro dígito verificador (peso 10-2)
- Calcula segundo dígito verificador (peso 11-2)
- Rejeita CPFs inválidos ou com dígitos repetidos

### Validação E-mail
Regex: `/^[^\s@]+@[^\s@]+\.[^\s@]+$/`

### Validação Telefone
- Aceita 10 ou 11 dígitos
- Formata em `(XX) XXXXX-XXXX`

### Validação CEP
- Requer exatamente 8 dígitos
- Formata em `XXXXX-XXX`

---

## 🌐 Integração GitHub

O projeto está disponível em:
- **Repository:** https://github.com/Fejluiza/ong_lacosorganizacion.git
- **Main Branch:** código de produção
- **.gitignore:** Ignora arquivos de sistema, IDE e dependências

---

## 📦 Estrutura de Commits

O projeto segue boas práticas de versionamento:
- Commits descritivos em português
- Histórico limpo com mensagens claras
- Tags para versões importantes

---

## 🤝 Como Contribuir

### Passo 1: Fork o Repositório
Clique em "Fork" no GitHub

### Passo 2: Clone sua Cópia
```bash
git clone https://github.com/seu-usuario/ong_lacosorganizacion.git
cd projetoFaculdade
```

### Passo 3: Crie uma Branch
```bash
git checkout -b feature/sua-contribuicao
```

### Passo 4: Faça suas Mudanças
- Adicione novas funcionalidades
- Corrija bugs
- Melhore a documentação

### Passo 5: Teste Localmente
```bash
python3 -m http.server 8000
# Teste em http://localhost:8000
```

### Passo 6: Commit e Push
```bash
git add .
git commit -m "feat: descrição clara da mudança"
git push origin feature/sua-contribuicao
```

### Passo 7: Pull Request
Abra um Pull Request com descrição detalhada

---

## 🎓 Aprendizados Técnicos

Este projeto exemplifica:
- ✅ Desenvolvimento web sem frameworks
- ✅ Validação de formulários robusta
- ✅ Design responsivo com CSS puro
- ✅ Manipulação de DOM com JavaScript vanilla
- ✅ Versionamento e colaboração com Git
- ✅ Boas práticas de código e documentação

---

## 📚 Referências e Padrões

### Validação CPF
Baseado no [algoritmo oficial da Receita Federal](https://www.gov.br/cidadania/pt-br/acesso-a-informacao/dados-abertos/arquivos-baixar)

### CSS Responsivo
Media queries seguem padrões mobile-first de desenvolvimento web moderno

### Acessibilidade
Implementado conforme recomendações [WCAG 2.1](https://www.w3.org/WAI/WCAG21/quickref/)

---

## 🎯 Próximos Passos (Sugestões Futuras)

- 🔄 Integração com backend (Node.js/Python)
- 💾 Banco de dados para persistência de voluntários
- 📧 Envio de e-mails confirmando cadastro
- 📊 Dashboard administrativo
- 🔐 Autenticação de usuários
- 🌍 Multi-idioma (PT, EN, ES)
- 📱 App mobile
- 📈 Analytics e tracking

---

## ⚖️ Licença

Este projeto é open source e pode ser usado livremente para fins educacionais e não-lucrativos.

---

## 👤 Créditos

**Desenvolvedora:** Luiza Goulart  
**Projeto:** ONG LAÇOS - Website Institucional  
**Data de Criação:** 2024  
**Última Atualização:** 2024

---

## 💬 Contato e Suporte

Para dúvidas, sugestões ou contribuições, abra uma [issue no GitHub](https://github.com/Fejluiza/ong_lacosorganizacion.git/issues).

---

## 📸 Galeria do Projeto

O site apresenta design moderno com:
- Interface clean e profissional
- Cores sofisticadas e acolhedoras
- Fluxo de navegação intuitivo
- Formulário completo e validado
- Total responsividade

---

**Feito com ❤️ para fazer a diferença!**
