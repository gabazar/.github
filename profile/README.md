![gabazar_c](https://user-images.githubusercontent.com/9539009/150692199-ce527a01-063c-47be-99e2-869311f0a899.png)

# Hello there 👋

O Projeto Gabazar é uma plataforma para troca de livros open source.

## Gitflow

Os commits seguem o padrão de descrição visual do https://gitmoji.dev/

## Arquitetura

A arquitetura esta dividida em dominios, cada dominio segue o padrão de arquitetura hexagonal com fronteiras logicas onde as regras de negocio (core) estão bem isoladas de objetos externos atravez de adapters. Todos os objetos externos à aplicação são traduzidos/mapeados antes de serem trafegados entre os pacotes a fim de evitar extensas refatorações a cada alteração de contrato. 

## Cobertura
https://app.codecov.io/gh/gabazar

## Projetos

### Microsserviços:
| Projeto | Build | Cobertura | Maintainability
| -- | -- | -- | -- | 
| [gabazar-autores](https://github.com/gabazar/gabazar-autores) | [![Build Status](https://app.travis-ci.com/gabazar/gabazar-autores.svg?branch=main)](https://app.travis-ci.com/gabazar/gabazar-autores) | [![codecov](https://codecov.io/gh/gabazar/gabazar-autores/branch/main/graph/badge.svg?token=JOIUBJXYJ9)](https://codecov.io/gh/gabazar/gabazar-autores) | [![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=gabazar_gabazar-autores&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=gabazar_gabazar-autores) |
| [gabazar-editoras](https://github.com/gabazar/gabazar-editoras) | [![Build Status](https://app.travis-ci.com/gabazar/gabazar-editoras.svg?branch=main)](https://app.travis-ci.com/gabazar/gabazar-editoras) | [![codecov](https://codecov.io/gh/gabazar/gabazar-editoras/branch/main/graph/badge.svg?token=6INNSA35FZ)](https://codecov.io/gh/gabazar/gabazar-editoras) | [![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=gabazar_gabazar-editoras&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=gabazar_gabazar-editoras)|
| [gabazar-leitores](https://github.com/gabazar/gabazar-leitores) | [![Build Status](https://app.travis-ci.com/gabazar/gabazar-leitores.svg?branch=main)](https://app.travis-ci.com/gabazar/gabazar-leitores) | [![codecov](https://codecov.io/gh/gabazar/gabazar-leitores/branch/main/graph/badge.svg?token=J3DD2YVSYJ)](https://codecov.io/gh/gabazar/gabazar-leitores) | [![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=gabazar_gabazar-leitores&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=gabazar_gabazar-leitores) |
| [gabazar-livros](https://github.com/gabazar/gabazar-livros) | | | |
| [gabazar-exemplares](https://github.com/gabazar/gabazar-exemplares) | | |
| [gabazar-trocas](https://github.com/gabazar/gabazar-trocas) | | | |

### Workers:

| Projeto | Build | Cobertura |
| -- | -- | --| 
| [gabazar-radar](https://github.com/gabazar/gabazar-radar) | | |

### Front-end:
| Projeto | Build | Cobertura |
| -- | -- | --| 
| [gabazar-front](https://github.com/gabazar/gabazar-front) | | |

