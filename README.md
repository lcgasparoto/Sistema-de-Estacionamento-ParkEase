# 🅿️ **ParkEase - Sistema de Estacionamento Inteligente**

![ParkEase Banner](https://img.shields.io/badge/ParkEase-v1.0.0-blue)
![Python Version](https://img.shields.io/badge/Python-3.8%2B-green)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange)

<div align="center">
  <img src="https://via.placeholder.com/800x400/2c3e50/ffffff?text=ParkEase+-+Estacionamento+Inteligente" alt="ParkEase Banner">
  
  ### 🚗 **Sistema Completo de Gerenciamento de Estacionamento**
  
  [🇧🇷 Português](#português) | [🇺🇸 English](#english)
</div>

---

## 👨‍💻 **Desenvolvedor**

<div align="center">
  
### **Lucas Clanes Gasparoto**

[![Instagram](https://img.shields.io/badge/Instagram-%40lcgasparoto-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/lcgasparoto)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-c-gasparoto-9b5a12381/)
[![GitHub](https://img.shields.io/badge/GitHub-lucasclanes-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lucasclanes)

**Este projeto foi totalmente desenvolvido por mim, com dedicação e paixão por tecnologia!** 🚀

</div>

---

## 📑 **Índice**
- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Demonstração](#-demonstração)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como Instalar](#-como-instalar)
- [Como Usar](#-como-usar)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Contribuição](#-contribuição)
- [Licença](#-licença)
- [Contato](#-contato)

---

## 📖 **Sobre o Projeto**

O **ParkEase** é um sistema completo e moderno para gerenciamento de estacionamentos, desenvolvido inteiramente em Python com interface gráfica intuitiva. O sistema oferece uma solução profissional para controle de entrada e saída de veículos, cálculo automático de valores, geração de relatórios e muito mais.

### 🎯 **Objetivo**
Facilitar o dia a dia de administradores de estacionamentos, proporcionando uma ferramenta simples, eficiente e com design agradável para gerenciar todas as operações necessárias.

---

## ✨ **Funcionalidades**

### 🚗 **Gerenciamento de Veículos**
| Funcionalidade | Descrição |
|----------------|-----------|
| ✅ **Registro de Entrada** | Cadastro completo com proprietário, veículo e placa |
| ✅ **Atribuição Automática** | Sistema inteligente de alocação de vagas |
| ✅ **Busca em Tempo Real** | Filtro instantâneo por placa ou proprietário |
| ✅ **Visualização em Tabela** | Lista organizada de veículos estacionados |

### 💰 **Sistema de Pagamento**
| Funcionalidade | Descrição |
|----------------|-----------|
| ✅ **Preço por Hora** | Tarifa configurável pelo usuário |
| ✅ **Cálculo Automático** | Baseado no tempo de permanência (mínimo 1 hora) |
| ✅ **Múltiplas Formas** | Dinheiro, Cartão de Crédito/Débito, PIX |
| ✅ **Detalhamento** | Visualização completa do cálculo |

### 📊 **Estatísticas e Relatórios**
| Funcionalidade | Descrição |
|----------------|-----------|
| ✅ **Painel de Vagas** | Visualização em tempo real da ocupação |
| ✅ **Gráficos** | Representação visual dos dados |
| ✅ **Relatório Diário** | Resumo completo das operações do dia |
| ✅ **Histórico** | Registro de todas as saídas |

### 🎨 **Interface**
| Funcionalidade | Descrição |
|----------------|-----------|
| ✅ **Design Moderno** | Interface limpa e intuitiva |
| ✅ **Cores Personalizadas** | Paleta de cores agradável e profissional |
| ✅ **Cards Organizados** | Informações distribuídas em cards funcionais |
| ✅ **Feedback Visual** | Mensagens claras de sucesso/erro |

### 💾 **Persistência**
| Funcionalidade | Descrição |
|----------------|-----------|
| ✅ **Salvamento Automático** | Dados preservados entre sessões |
| ✅ **Formato JSON** | Fácil importação/exportação |
| ✅ **Backup Manual** | Opção de salvar dados manualmente |

---

## 🎥 **Demonstração**

<div align="center">
  
### 📸 **Tela Principal**
```
┌─────────────────────────────────────────────────────────────┐
│  🚗 ParkEase - Estacionamento Inteligente      🟢 Sistema Online│
├─────────────────────────────────────────────────────────────┤
│  ┌─────────────┐  ┌──────────────────────┐  ┌─────────────┐│
│  │ 🅿️ Vagas    │  │ 📋 Veículos         │  │ ➕ Nova     ││
│  │ 15/50       │  │                     │  │   Entrada   ││
│  │ ████████    │  │ Vaga | Proprietário │  ├─────────────┤│
│  ├─────────────┤  ├──────────────────────┤  │ 🔍 Busca   ││
│  │ 📊 Estatís- │  │ 1    | João Silva   │  ├─────────────┤│
│  │   ticas     │  │ 2    | Maria Santos │  │ ⚡ Ações   ││
│  │ R$ 450,00   │  │ 3    | Pedro Souza  │  │   Rápidas  ││
│  └─────────────┘  └──────────────────────┘  └─────────────┘│
└─────────────────────────────────────────────────────────────┘
```

### 🎬 **Fluxo de Operações**
1. **Registro de Entrada** → Preencha os dados do veículo
2. **Acompanhamento** → Visualize na tabela principal
3. **Cálculo de Pagamento** → Sistema calcula automaticamente
4. **Registro de Saída** → Finalize e libere a vaga

</div>

---

## 🛠 **Tecnologias Utilizadas**

<div align="center">

| Tecnologia | Versão | Finalidade |
|------------|--------|------------|
| ![Python](https://img.shields.io/badge/Python-3.8%2B-blue) | ≥ 3.8 | Linguagem principal |
| ![Tkinter](https://img.shields.io/badge/Tkinter-8.6-green) | 8.6 | Interface gráfica |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5%2B-orange) | ≥ 3.5 | Geração de gráficos |
| ![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-yellow) | ≥ 1.3 | Manipulação de dados |
| ![TkCalendar](https://img.shields.io/badge/TkCalendar-1.6%2B-red) | ≥ 1.6 | Seleção de datas |

</div>

---

## 📥 **Como Instalar**

### Pré-requisitos
- Python 3.8 ou superior instalado
- pip (gerenciador de pacotes Python)

### Passo a Passo

1. **Clone o repositório**
```bash
git clone https://github.com/lucasclanes/parkease.git
cd parkease
```

2. **Crie um ambiente virtual (opcional, mas recomendado)**
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Linux/Mac
python3 -m venv venv
source venv/bin/activate
```

3. **Instale as dependências**
```bash
pip install -r requirements.txt
```

4. **Execute o sistema**
```bash
python parkease.py
```

### 📦 **Arquivo requirements.txt**
```txt
tkcalendar==1.6.1
matplotlib==3.5.0
pandas==1.3.0
```

---

## 📖 **Como Usar**

### 🚀 **Primeiros Passos**

1. **Ao iniciar o sistema**, você verá a interface principal com 3 áreas:
   - **Painel Esquerdo**: Estatísticas e vagas disponíveis
   - **Área Central**: Tabela de veículos estacionados
   - **Painel Direito**: Ações e formulários

2. **Registre um veículo**:
   - Preencha os campos no card "Nova Entrada"
   - Clique em "Registrar Entrada"
   - O sistema atribuirá automaticamente uma vaga

3. **Acompanhe os veículos**:
   - Visualize todos na tabela central
   - Use o campo de busca para filtrar
   - Veja o tempo de permanência e valor atualizado

4. **Realize o pagamento**:
   - Selecione um veículo na tabela
   - Clique em "Calcular Pagamento"
   - Escolha a forma de pagamento
   - Confirme a operação

5. **Registre a saída**:
   - Após o pagamento, confirme a saída
   - A vaga será liberada automaticamente

### ⌨️ **Atalhos e Dicas**
- A tabela atualiza automaticamente a cada minuto
- Use a busca para localizar veículos rapidamente
- O sistema salva os dados automaticamente ao fechar

---

## 📁 **Estrutura do Projeto**

```
parkease/
│
├── 📄 parkease.py              # Arquivo principal do sistema
├── 📄 requirements.txt          # Dependências do projeto
├── 📄 README.md                 # Documentação em português
├── 📄 README-EN.md              # Documentação em inglês
├── 📄 LICENSE                   # Licença do projeto
│
├── 📁 assets/                   # Recursos visuais
│   ├── 🖼️ icon.ico              # Ícone do aplicativo
│   ├── 🖼️ banner.png            # Banner para o README
│   └── 🖼️ screenshots/          # Capturas de tela
│       ├── tela-principal.png
│       ├── relatorio.png
│       └── pagamento.png
│
├── 📁 data/                     # Dados do sistema
│   └── 📄 parkease_dados.json   # Banco de dados JSON
│
└── 📁 docs/                     # Documentação adicional
    ├── 📄 manual-usuario.pdf
    └── 📄 especificacoes.md
```

---

## 🤝 **Contribuição**

Contribuições são sempre bem-vindas! Veja como você pode ajudar:

### 📝 **Como contribuir**

1. **Fork** o projeto
2. **Crie uma branch** para sua feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. **Push** para a branch (`git push origin feature/AmazingFeature`)
5. **Abra um Pull Request**

### ✅ **Diretrizes**
- Mantenha o código limpo e comentado
- Atualize a documentação quando necessário
- Teste suas alterações antes de enviar
- Siga o estilo de código existente

### 🎯 **Sugestões de Melhorias**
- [ ] Integração com banco de dados SQLite
- [ ] Sistema de cadastro de clientes frequentes
- [ ] Emissão de comprovantes em PDF
- [ ] Módulo de reservas online
- [ ] Sistema de fidelidade com descontos
- [ ] Notificações por WhatsApp/SMS
- [ ] Painel administrativo com usuários
- [ ] Backup automático em nuvem

---

## 📄 **Licença**

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

```
MIT License

Copyright (c) 2024 Lucas Clanes Gasparoto

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 📞 **Contato**

<div align="center">

### **Lucas Clanes Gasparoto**

[![Instagram](https://img.shields.io/badge/Instagram-%40lcgasparoto-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/lcgasparoto)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-c-gasparoto-9b5a12381/)
[![GitHub](https://img.shields.io/badge/GitHub-lucasclanes-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lucasclanes)
[![Email](https://img.shields.io/badge/Email-Contato-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lucas.gasparoto@email.com)

---

### ⭐ **Gostou do projeto?**
Deixe uma estrela no GitHub e compartilhe com outros desenvolvedores!

### 🐛 **Encontrou um bug?**
Abra uma issue [aqui](https://github.com/lucasclanes/parkease/issues)

### 💡 **Tem uma sugestão?**
Fique à vontade para contribuir ou entrar em contato!

---

## 🏆 **Reconhecimentos**

- **Desenvolvido 100% por:** Lucas Clanes Gasparoto
- **Instagram:** [@lcgasparoto](https://instagram.com/lcgasparoto)
- **LinkedIn:** [Lucas C Gasparoto](https://www.linkedin.com/in/lucas-c-gasparoto-9b5a12381/)
- **GitHub:** [@lucasclanes](https://github.com/lucasclanes)

</div>

---

## 📊 **Estatísticas do Projeto**

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/lucasclanes/parkease?style=social)
![GitHub forks](https://img.shields.io/github/forks/lucasclanes/parkease?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/lucasclanes/parkease?style=social)
![GitHub followers](https://img.shields.io/github/followers/lucasclanes?style=social)

**Última atualização:** Fevereiro/2025  
**Versão atual:** 1.0.0  
**Linhas de código:** ~1.500  
**Funcionalidades:** 25+  
**Desenvolvedor:** Lucas Clanes Gasparoto

</div>

---

## 🎉 **Agradecimentos**

- A todos que testaram e forneceram feedback
- Comunidade Python pelo suporte
- Usuários que confiam no ParkEase

---

<div align="center">
  
### Desenvolvido com ❤️ por **Lucas Clanes Gasparoto**

[![Instagram](https://img.shields.io/badge/Follow-%40lcgasparoto-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/lcgasparoto)
[![LinkedIn](https://img.shields.io/badge/Connect-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-c-gasparoto-9b5a12381/)
[![GitHub](https://img.shields.io/badge/Follow-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/lucasclanes)

**ParkEase - Simplificando o gerenciamento do seu estacionamento** 🚗

[⬆ Voltar ao topo](#-parkease---sistema-de-estacionamento-inteligente)

</div>

---

## 📝 **Notas da Versão**

### Versão 1.0.0 (Fevereiro/2025)
- 🎉 Lançamento inicial do ParkEase
- ✅ Interface gráfica completa
- ✅ Sistema de registro de entrada/saída
- ✅ Cálculo automático de valores
- ✅ Relatórios e estatísticas
- ✅ Persistência de dados em JSON
- ✅ Design moderno e intuitivo

### Próximas Atualizações
- 🔄 Integração com banco de dados
- 🔄 Sistema de clientes frequentes
- 🔄 Emissão de comprovantes PDF
- 🔄 Reservas online

---

<div align="center">
  
**© 2025 Lucas Clanes Gasparoto - Todos os direitos reservados**

</div>
