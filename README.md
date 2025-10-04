# 🐾 PetCare

Aplicativo mobile e web para gestão completa da saúde e rotina dos seus pets.

![PetCare Banner](src/assets/hero-pets.jpg)

## 📱 Sobre o Projeto

PetCare é uma solução moderna e intuitiva para donos de pets que desejam manter o controle total sobre a saúde e bem-estar dos seus animais de estimação. Com uma interface amigável e recursos práticos, você nunca mais esquecerá uma vacina, consulta ou medicamento.

## ✨ Funcionalidades

- **📅 Agenda Completa**: Organize vacinas, consultas veterinárias e compromissos
- **⏰ Lembretes Inteligentes**: Notificações para medicamentos, banho e tosa
- **🐶 Perfis de Pets**: Cadastre múltiplos pets com fotos, raça, idade e informações importantes
- **💉 Controle de Vacinas**: Acompanhe o histórico e próximas datas de vacinação
- **📊 Dashboard Informativo**: Visualize estatísticas e lembretes em um só lugar
- **📱 Mobile-First**: Interface responsiva otimizada para dispositivos móveis

## 🛠️ Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias:

- **[React](https://react.dev/)** - Biblioteca JavaScript para interfaces
- **[TypeScript](https://www.typescriptlang.org/)** - Tipagem estática para JavaScript
- **[Vite](https://vitejs.dev/)** - Build tool e dev server
- **[Tailwind CSS](https://tailwindcss.com/)** - Framework CSS utility-first
- **[shadcn/ui](https://ui.shadcn.com/)** - Componentes de UI reutilizáveis
- **[Capacitor](https://capacitorjs.com/)** - Framework para apps nativos iOS e Android
- **[Lucide React](https://lucide.dev/)** - Ícones modernos
- **[React Router](https://reactrouter.com/)** - Navegação SPA

## 🚀 Como Executar

### Pré-requisitos

- Node.js 18+ e npm instalados
- Para desenvolvimento mobile: Xcode (iOS) ou Android Studio (Android)

### Instalação

```bash
# Clone o repositório
git clone <URL_DO_REPOSITORIO>

# Entre na pasta do projeto
cd tail-wag-planner

# Instale as dependências
npm install

# Execute o projeto em modo de desenvolvimento
npm run dev
```

O aplicativo estará disponível em `http://localhost:5173`

### Build para Produção

```bash
# Gere a build otimizada
npm run build

# Visualize a build localmente
npm run preview
```

## 📱 Desenvolvimento Mobile

### Configurar Plataformas

```bash
# Adicionar plataforma iOS (requer macOS)
npx cap add ios

# Adicionar plataforma Android
npx cap add android

# Sincronizar código com as plataformas nativas
npx cap sync
```

### Executar em Dispositivos

```bash
# iOS
npx cap run ios

# Android
npx cap run android
```

## 🎨 Design System

O PetCare utiliza um design system customizado com:

- **Paleta de Cores**: Tons quentes e acolhedores (coral, teal, roxo)
- **Tipografia**: Sistema de fontes sans-serif moderno
- **Componentes**: Baseados em shadcn/ui com variantes personalizadas
- **Tema**: Suporte a dark mode nativo

## 📂 Estrutura do Projeto

```
src/
├── assets/          # Imagens e recursos estáticos
├── components/      # Componentes React reutilizáveis
│   ├── ui/         # Componentes base do shadcn/ui
│   ├── PetCard.tsx
│   ├── ReminderCard.tsx
│   └── StatsCard.tsx
├── pages/          # Páginas da aplicação
│   ├── Index.tsx
│   └── NotFound.tsx
├── hooks/          # Custom React hooks
├── lib/            # Utilitários e helpers
├── App.tsx         # Componente raiz
└── main.tsx        # Entry point
```

## 🤝 Como Contribuir

Contribuições são sempre bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 📝 Roadmap

- [ ] Sistema de autenticação de usuários
- [ ] Sincronização em nuvem (Lovable Cloud)
- [ ] Histórico médico completo
- [ ] Compartilhamento de perfis entre familiares
- [ ] Integração com clínicas veterinárias
- [ ] Marketplace de produtos e serviços pet
- [ ] Notificações push nativas

## 📄 Licença

Este projeto foi criado com [Lovable](https://lovable.dev) e está disponível sob a licença MIT.

## 🔗 Links Úteis

- [Documentação Lovable](https://docs.lovable.dev/)
- [Lovable Cloud](https://docs.lovable.dev/features/cloud)
- [Comunidade Discord](https://discord.com/channels/1119885301872070706/1280461670979993613)

---

Desenvolvido com ❤️ para pets e seus donos
