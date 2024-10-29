# Flutter Developer Roadmap

Este roadmap te guiará desde os conceitos básicos até habilidades avançadas, com uma visão clara das áreas de aprendizado e dificuldade. Use as marcações para monitorar seu progresso e identificar áreas que exigem mais prática.

---

## 1. Fundamentos de Programação
- [x] **Programação Orientada a Objetos (OOP)**
  - [x] Entender os pilares: classes, herança, polimorfismo, encapsulamento, abstração.
- [x] **Linguagem Dart**
  - [x] Sintaxe básica: variáveis, tipos, funções, métodos.
  - [x] Estruturas de controle: if/else, loops.
  - [x] Programação assíncrona: `async`/`await`, `Future`, e `Stream`.
  - [x] Coleções: `List`, `Map`, `Set`.

---

## 2. Primeiros Passos com Flutter
- [x] **Configuração do Ambiente**
  - [x] Instalar o SDK do Flutter e configurar IDE (Android Studio/VS Code).
  - [x] Construir a interface básica com widgets como `Container`, `Column`, `Row` e `Text`.
- [x] **Entendendo Widgets**
  - [x] Diferença entre `StatelessWidget` e `StatefulWidget`.
  - [x] Layout básico usando `ListView`, `GridView`.
  - [x] Criar widgets personalizados reutilizáveis.
  - [x] Explorar como funciona o **layout** e **constraints** dos widgets.

---

## 3. Conceitos Intermediários de Flutter
- [x] **Gerenciamento de Estado**
  - [x] Usar `setState()` para gerenciar estado local. _(Nota: Às vezes tenho dificuldade para saber o momento certo de usar)_
  - [x] Implementar **Provider** para estados globais.
  - [ ] Explorar padrões avançados como **BLoC** e **Riverpod** _(só explorei BLoC até agora)_.

- [x] **Navegação e Rotas**
  - [x] Navegar entre telas com `Navigator` e rotas nomeadas.
  - [x] Passar dados entre telas usando argumentos de rota.
  - [x] Criar modais e diálogos com `showModalBottomSheet` e `AlertDialog`.

- [x] **Integração com APIs**
  - [x] Fazer requisições com `http` ou `Dio`.
  - [x] Parsear respostas JSON e criar modelos em Dart.
  - [x] Gerenciar estados de carregamento, sucesso e erro.

- [x] **Persistência de Dados**
  - [x] Armazenar dados localmente com **SharedPreferences**.
  - [ ] Implementar banco de dados SQLite com o pacote `sqflite`.
  - [ ] Explorar armazenamento em nuvem com **Firebase Firestore**.

---

## 4. Desenvolvimento Avançado em Flutter
- [ ] **Animações**
  - [x] Implementar animações implícitas (`AnimatedContainer`, `AnimatedOpacity`).
  - [ ] Aprender animações explícitas com `AnimationController` e `Tween`.
  - [ ] Explorar animações com **Rive** e **Lottie**.

- [ ] **Otimização de Performance**
  - [x] Usar o **Flutter DevTools** para perfilar a performance.
  - [ ] Otimizar o uso de memória e renderização de UI.
  - [x] Implementar carregamento preguiçoso (lazy loading) e caching.

- [x] **Testes**
  - [x] Escrever testes unitários para lógica de negócios.
  - [x] Criar testes de widgets para componentes de UI.
  - [x] Implementar testes de integração para simular fluxos de usuário.

- [ ] **Integração com Funcionalidades Nativas**
  - [x] Usar plugins nativos como câmera, GPS, sensores.
  - [ ] Integrar com APIs específicas de plataforma via canais de plataforma (Platform Channels).

---

## 5. Estrutura de Projeto e Boas Práticas
- [x] **Arquitetura Limpa (Clean Architecture)**
  - [ ] Seguir padrões como **BLoC**, MVVM para uma estrutura de código escalável. _(Nunca usei MVVM ou outras estruturas)_
  - [x] Separar camadas de UI, lógica de negócios e dados.
  - [ ] Implementar **injeção de dependências** com o pacote `get_it`. _(Apliquei muito pouco)_
  - [x] Seguir boas práticas de código limpo (Clean Code).

---

## 6. Publicação de Apps Flutter
- [x] **Deploy Cross-platform**
  - [x] Configurar arquivos de build para Android.
  - [ ] Configurar arquivos de build para iOS.
  - [x] Configurar ícones, permissões e assinatura de apps.
  - [ ] Explorar **Flutter Web** e **Flutter Desktop** para ampliar o alcance.

---

### Recursos Recomendados:
- [Flutter Oficial](https://flutter.dev/docs)
