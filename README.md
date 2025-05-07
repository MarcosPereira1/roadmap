# Flutter Developer Roadmap

Este roadmap te guiará desde os conceitos básicos até habilidades avançadas. Use as marcações para monitorar seu progresso:  
✅ `[x]` Concluído – 🔄 `[~]` Em andamento – ❌ `[ ]` Pendente

---

## 1. Fundamentos de Programação
- [x] **Programação Orientada a Objetos (OOP)**
  - [x] Classes, herança, polimorfismo, encapsulamento, abstração.
  - [x] Composição vs herança.
  - [x] Modelagem de sistemas com OOP.
- [x] **Linguagem Dart**
  - [x] Variáveis, tipos, funções, métodos.
  - [x] Controle de fluxo: if/else, loops, switch.
  - [x] Assíncrono: `Future`, `async/await`, `Stream`, `Completer`.
  - [x] Coleções: `List`, `Map`, `Set`, `map`, `where`, `fold`, `expand`.
  - [x] Avançado: `extension`, `enum`, `typedef`, `mixin`, `sealed class`.

---

## 2. Primeiros Passos com Flutter
- [x] **Configuração do Ambiente**
  - [x] Instalar SDK, Android Studio/VS Code.
  - [x] Rodar app em emulador ou dispositivo físico.
  - [x] Conhecer estrutura de pastas.
- [x] **Entendendo Widgets**
  - [x] `StatelessWidget` vs `StatefulWidget`.
  - [x] Layouts com `Column`, `Row`, `Container`, `Stack`, `Expanded`.
  - [x] Listagens com `ListView`, `GridView`, `CustomScrollView`.
  - [x] Layout responsivo: `MediaQuery`, `LayoutBuilder`, `Wrap`.
  - [x] Widgets personalizados reutilizáveis.

---

## 3. Conceitos Intermediários de Flutter
- [x] **Gerenciamento de Estado**
  - [x] `setState()` e escopo local.
  - [x] Provider com `ChangeNotifier`, `Consumer`, `watch/read`.
  - [~] BLoC com `flutter_bloc`, `BlocBuilder`, `Cubit`, eventos/estados.
  - [ ] Testes com bloc.
  - [ ] Riverpod: `StateProvider`, `NotifierProvider`, `ref`, codegen.

- [x] **Navegação e Rotas**
  - [x] `Navigator.push/pop`, rotas nomeadas.
  - [x] Argumentos entre telas.
  - [x] Diálogos: `showDialog`, `showModalBottomSheet`.
  - [ ] Deep linking e rotas protegidas.

- [x] **Integração com APIs**
  - [x] Requisições com `http` e `Dio`, interceptadores.
  - [x] Parsing JSON com `jsonDecode`, `json_serializable`, `freezed`.
  - [x] Tratamento de estados: loading, error, sucesso.
  - [x] Retry, timeout, debounce, cancelamento.

- [x] **Persistência de Dados**
  - [x] `SharedPreferences`.
  - [ ] SQLite com `sqflite`, `drift`, migrations.
  - [ ] Firebase Firestore com streams e segurança.

---

## 4. Desenvolvimento Avançado em Flutter
- [~] **Animações**
  - [x] Implícitas: `AnimatedContainer`, `AnimatedSwitcher`, `Opacity`.
  - [ ] Explícitas: `AnimationController`, `Tween`, `AnimatedBuilder`.
  - [ ] Integração com **Rive** e **Lottie**.

- [~] **Otimização de Performance**
  - [x] Flutter DevTools: CPU, memória, repaints.
  - [x] Lazy loading: `ListView.builder`, cache de imagens.
  - [ ] Otimizar rebuilds: `const`, `RepaintBoundary`.
  - [ ] Compressão de assets, debounce, throttling.

- [x] **Testes**
  - [x] Unitários com `test`, `mocktail`.
  - [x] Testes de widgets com `pumpWidget`, `tap`, `expect`.
  - [x] Integração com `integration_test`, mocks e fluxo completo.

- [x] **Integração com Funcionalidades Nativas**
  - [x] Plugins nativos: câmera, GPS, sensores, arquivos.
  - [ ] Platform Channels: comunicação nativa com Swift/Kotlin.
  - [ ] Criar plugin próprio com canal de plataforma.

---

## 5. Estrutura de Projeto e Boas Práticas
- [x] **Arquitetura Limpa**
  - [x] Separação por camadas: UI, domínio, dados.
  - [x] BLoC aplicado à Clean Architecture.
  - [x] MVVM com Provider ou Riverpod.
  - [~] Injeção de dependência com `get_it`, `injectable`.
  - [x] Modularização por features.
  - [x] Princípios SOLID, DRY, YAGNI, Clean Code.

---

## 6. Publicação de Apps Flutter
- [x] **Deploy Cross-platform**
  - [x] Android: `build.gradle`, versão, permissões, assinatura.
  - [ ] iOS: Provisionamento, certificados, `Info.plist`.
  - [x] Ícones e splash: `flutter_launcher_icons`, `flutter_native_splash`.
  - [x] Web com Firebase Hosting.
    - [x] `flutter build web` + `firebase deploy`.
    - [x] Configurar domínio, regras e cache.
    - [x] Publicado com layout responsivo.

- [~] **Autenticação com Firebase**
  - [~] Projeto Firebase configurado (com suporte Web).
  - [~] Autenticação por e-mail/senha (`firebase_auth`).
  - [ ] Provedores externos: Google, Apple, GitHub.
  - [ ] Controle de sessão e proteção de rotas.
  - [ ] `Stream<User?>` para controle global de login.

- [ ] **Firebase Avançado**
  - [ ] Firestore com regras por usuário.
  - [ ] Firebase Functions para lógica de backend.
  - [ ] Firebase Analytics + Crashlytics.
  - [ ] Firebase Remote Config.

---

### Recursos Recomendados
- [Flutter Oficial](https://flutter.dev/docs)
- [Reso Coder](https://resocoder.com)
- [Flutterando](https://flutterando.com.br)
- [Fireship.io](https://www.youtube.com/c/Fireship)
- [FilledStacks](https://www.filledstacks.com)

---

> 💡 Dica: crie pequenos projetos reais por seção — como app de tarefas, login com Firebase, ou visualizador de dados da API — para consolidar conhecimento.
