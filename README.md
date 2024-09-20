# Flutter Developer Roadmap

Este roadmap te guiará desde os conceitos básicos até as habilidades intermediárias, focando em tópicos essenciais para o desenvolvimento com Flutter. Use a lista de verificação para monitorar seu progresso.

---

## 1. Fundamentos de Programação
- [ ] **Programação Orientada a Objetos (OOP)**
  - [ ] Entender os pilares: classes, herança, polimorfismo, encapsulamento, abstração.
- [ ] **Linguagem Dart**
  - [ ] Sintaxe básica: variáveis, tipos, funções, métodos.
  - [ ] Estruturas de controle: if/else, loops.
  - [ ] Programação assíncrona: `async`/`await`, `Future`, e `Stream`.
  - [ ] Coleções: `List`, `Map`, `Set`.

---

## 2. Primeiros Passos com Flutter
- [ ] **Configuração do Ambiente**
  - [ ] Instalar o SDK do Flutter e configurar IDE (Android Studio/VS Code).
  - [ ] Construir a interface básica com widgets como `Container`, `Column`, `Row` e `Text`.
- [ ] **Entendendo Widgets**
  - [ ] Diferença entre `StatelessWidget` e `StatefulWidget`.
  - [ ] Layout básico usando `ListView`, `GridView`.
  - [ ] Criar widgets personalizados reutilizáveis.
  - [ ] Explorar como funciona o **layout** e **constraints** dos widgets.

---

## 3. Conceitos Intermediários de Flutter
- [ ] **Gerenciamento de Estado**
  - [ ] Usar `setState()` para gerenciar estado local.
  - [ ] Implementar **Provider** para estados globais.
  - [ ] Explorar padrões avançados como **BLoC** e **Riverpod**.
- [ ] **Navegação e Rotas**
  - [ ] Navegar entre telas com `Navigator` e rotas nomeadas.
  - [ ] Passar dados entre telas usando argumentos de rota.
  - [ ] Criar modais e diálogos com `showModalBottomSheet` e `AlertDialog`.
- [ ] **Integração com APIs**
  - [ ] Fazer requisições com `http` ou `Dio`.
  - [ ] Parsear respostas JSON e criar modelos em Dart.
  - [ ] Gerenciar estados de carregamento, sucesso e erro.
- [ ] **Persistência de Dados**
  - [ ] Armazenar dados localmente com **SharedPreferences**.
  - [ ] Implementar banco de dados SQLite com o pacote `sqflite`.
  - [ ] Explorar armazenamento em nuvem com **Firebase Firestore**.

---

## 4. Desenvolvimento Avançado em Flutter
- [ ] **Animações**
  - [ ] Implementar animações implícitas (`AnimatedContainer`, `AnimatedOpacity`).
  - [ ] Aprender animações explícitas com `AnimationController` e `Tween`.
  - [ ] Explorar animações com **Rive** e **Lottie**.
- [ ] **Otimização de Performance**
  - [ ] Usar o **Flutter DevTools** para perfilar a performance.
  - [ ] Otimizar o uso de memória e renderização de UI.
  - [ ] Implementar carregamento preguiçoso (lazy loading) e caching.
- [ ] **Testes**
  - [ ] Escrever testes unitários para lógica de negócios.
  - [ ] Criar testes de widgets para componentes de UI.
  - [ ] Implementar testes de integração para simular fluxos de usuário.
- [ ] **Integração com Funcionalidades Nativas**
  - [ ] Usar plugins nativos como câmera, GPS, sensores.
  - [ ] Integrar com APIs específicas de plataforma via canais de plataforma (Platform Channels).

---

## 5. Estrutura de Projeto e Boas Práticas
- [ ] **Arquitetura Limpa (Clean Architecture)**
  - [ ] Seguir padrões como **BLoC**, MVVM para uma estrutura de código escalável.
  - [ ] Separar camadas de UI, lógica de negócios e dados.
  - [ ] Implementar **injeção de dependências** com o pacote `get_it`.
  - [ ] Seguir boas práticas de código limpo (Clean Code).

---

## 6. Publicação de Apps Flutter
- [ ] **Deploy Cross-platform**
  - [ ] Configurar arquivos de build para Android e iOS.
  - [ ] Configurar ícones, permissões e assinatura de apps.
  - [ ] Explorar **Flutter Web** e **Flutter Desktop** para ampliar o alcance.

---

### Recursos Recomendados:
- [Flutter Oficial](https://flutter.dev/docs)

