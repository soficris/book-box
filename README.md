# Book Box

O **Book Box** é um projeto acadêmico planejado para gerenciamento de uma biblioteca pessoal, com proposta inspirada em plataformas como Skoob e Goodreads.

## Status do projeto

Atualmente, este repositório está na etapa de preparação e gerenciamento de configuração. A aplicação ainda não foi implementada. A estrutura de pastas e os arquivos de configuração estão sendo organizados para as próximas etapas da disciplina.

## Tecnologias planejadas

- Flutter
- Dart
- Git e GitHub

## Estrutura do repositório

```text
book-box/
├── .github/              # Modelos de colaboração do GitHub
├── docs/                 # Documentação do projeto
├── lib/                  # Código-fonte Flutter (futuro)
├── test/                 # Testes automatizados (futuro)
├── .env.example          # Modelo de variáveis de ambiente
├── .gitattributes        # Padronização de arquivos
├── .gitignore            # Arquivos ignorados pelo Git
├── pubspec.yaml          # Configuração do projeto Dart/Flutter
└── README.md             # Documentação principal
```

## Pré-requisitos

Para as próximas etapas de desenvolvimento, será necessário instalar o [Flutter SDK](https://docs.flutter.dev/get-started/install) e configurar um ambiente de desenvolvimento compatível.

## Preparação do projeto

Depois de instalar o Flutter, execute na raiz do repositório:

```bash
flutter pub get
```

Esse comando resolve as dependências declaradas no `pubspec.yaml` e gera/atualiza o `pubspec.lock`, que deve ser versionado.

> **Atenção:** como a aplicação ainda não possui código-fonte nem ponto de entrada (`lib/main.dart`), os comandos `flutter run` e `flutter test` ainda não se aplicam. Eles serão utilizados quando a implementação e os testes forem criados.

## Colaboração

- Alterações na `main` devem ocorrer por Pull Request.
- Todo Pull Request deve receber ao menos uma aprovação de outro colaborador.
- Os modelos de Pull Request e Issues estão em `.github/`.
- As regras de branches e proteção são configuradas nas configurações do repositório no GitHub.

## Segurança

Não versione senhas, tokens ou chaves de API. Utilize variáveis de ambiente para configurações locais e GitHub Secrets para valores sigilosos usados em automações.
