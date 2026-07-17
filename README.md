# 📅 React Native | Calendário Personalizado

Projeto desenvolvido utilizando a biblioteca **react-native-calendars**, demonstrando como implementar um calendário moderno, responsivo e altamente personalizável em aplicações React Native.

Além da implementação básica, o projeto apresenta recursos como localização em português, personalização visual, seleção de datas e restrição de datas anteriores.

---

## 📸 Preview

<img src="./assets/screen.png" alt="Preview do React Native Calendar">

---

## 🚀 Tecnologias

- React Native
- TypeScript
- react-native-calendars

---

## ✨ Funcionalidades

- Calendário totalmente personalizável
- Seleção de datas
- Destaque da data selecionada
- Bloqueio de datas anteriores
- Internacionalização (Português - Brasil)
- Customização de cores, fontes e navegação
- Exibição da data selecionada em formato personalizado

---

## 📚 Conceitos Aplicados

Este projeto demonstra diversos conceitos importantes para o desenvolvimento de interfaces mobile.

- Utilização da biblioteca **react-native-calendars**
- Componentização no React Native
- Gerenciamento de estado com Hooks (`useState`)
- Internacionalização utilizando `LocaleConfig`
- Personalização de temas
- Marcação dinâmica de datas
- Manipulação e formatação de datas
- Configuração de propriedades do componente
- Estilização com StyleSheet
- Desenvolvimento de interfaces responsivas

---

## 📦 Instalação

```bash
yarn add react-native-calendars
```

ou

```bash
npm install react-native-calendars
```

A biblioteca é escrita em JavaScript e **não requer configuração nativa adicional**.

---

## ▶️ Executando o Projeto

```bash
npm install

npm start
```

ou

```bash
yarn

yarn start
```

---

## 🧩 Exemplo Básico

```tsx
import { Calendar } from 'react-native-calendars';

<Calendar
  onDayPress={(day) => {
    console.log(day.dateString);
  }}
/>
```

---

## 🎨 Personalizações Demonstradas

O projeto apresenta diversas possibilidades de customização da biblioteca.

- Tema personalizado
- Cabeçalho customizado
- Alteração das cores do calendário
- Idioma Português (Brasil)
- Datas marcadas dinamicamente
- Destaque para a data selecionada
- Ocultação dos dias excedentes do mês
- Restrição para impedir seleção de datas passadas

---

## 🌎 Internacionalização

O calendário foi configurado para utilizar o idioma **Português (Brasil)** através do `LocaleConfig`.

```tsx
LocaleConfig.locales['pt-br'] = ptBR;
LocaleConfig.defaultLocale = 'pt-br';
```

---

## 🎯 Objetivos de Aprendizagem

- Aprender a utilizar bibliotecas externas no React Native.
- Implementar componentes de calendário em aplicações mobile.
- Personalizar aparência e comportamento de componentes.
- Trabalhar com datas e eventos.
- Aplicar boas práticas na organização do código.

---

## 💡 Possíveis Evoluções

- Agenda de compromissos
- Integração com API
- Eventos recorrentes
- Calendário de reservas
- Controle de disponibilidade
- Agenda médica
- Aplicativo de tarefas
- Planejamento de viagens

---

## 👨‍💻 Autor

Desenvolvido por **Jorge Cruz**.
