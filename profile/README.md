# ZenWave 360 - Landscape

> Work-in-progress

![ZenWave360 Landscape](ZenWave-360-Landscape.excalidraw.svg)

- [ZenWave 360 - Landscape](#zenwave-360---landscape)
  - [ZenWave Code Generator](#zenwave-code-generator-) ![Alpha](https://img.shields.io/badge/lifecycle-alpha-yellow)
  - [ZenWave Editor](#zenwave-editor-) ![Comming Soon](https://img.shields.io/badge/lifecycle-Comming_Soon-lightgray)
    - [ZenWave KarateIDE for visual studio code](#zenwave-karateide-for-visual-studio-code-) ![General Availability](https://img.shields.io/badge/lifecycle-GA-green)
    - [ZenWave ApiMock for REST APIs](#zenwave-apimock-for-rest-apis-) ![Beta](https://img.shields.io/badge/lifecycle-beta-red)
    - [Karate+OpenAPI PetStore Contract Testing complete source code](#karateopenapi-petstore-contract-testing-complete-source-code-)
  - [ZenWave API Registry](#zenwave-api-registry-) ![Comming Soon](https://img.shields.io/badge/lifecycle-Comming_Soon-lightgray)

## ZenWave Code Generator ![Alpha](https://img.shields.io/badge/lifecycle-alpha-yellow)

[Zen Wave Code Generator](https://zenwave360.github.io/zenwave-code-generator/)

ZenWave Code Generator is a configurable and extensible code generator tool for **Domain Driven Design (DDD)** and **API-First** that can generate code from a mix of different models including:

- JHipster Domain Language (JDL)
- AsyncAPI
- OpenAPI

## ZenWave Editor ![Comming Soon](https://img.shields.io/badge/lifecycle-Comming_Soon-lightgray)

- ZenWave Visual Studio Code API Editor
  - JDL Editor and visulizer
  - OpenAPI/AsyncAPI visualizer
  - Linting and Autofix
  - REST Client

### ZenWave KarateIDE for visual studio code ![General Availability](https://img.shields.io/badge/lifecycle-GA-green)

[ZenWave KarateIDE](https://github.com/ZenWave360/karate-ide) for visual studio code is:

- A **Test Runner/Debugger** and **REST Client** that uses [KarateDSL](https://github.com/karatelabs/karate) to explore your API, import/export from cURL and generate tests/mocks from OpenAPI.
- **OpenAPI Generator** that generates:
  - **Karate Tests** you can immediately run, with validation, inline payload examples and scenario outlines for each response code of your API.
  - **Stateful Mocks**: combining OpenAPI schemas for validation and examples to load mock datasets.
  - **Mock Validation Tests**: simpler tests to validate your mocks.
  - **Business Flow Tests**: you can even generate tests that spans multiple API calls reusing generated karate tests

KarateIDE is by far the best user experience for KarateDSL and Contract Testing!!

### ZenWave ApiMock for REST APIs ![Beta](https://img.shields.io/badge/lifecycle-beta-red)

[ZenWave ApiMock](https://github.com/ZenWave360/zenwave-apimock) - Where OpenAPI meets KarateDSL Server Side Features for REST API mocking:

- Powerful yet simple **stateful mocks using KarateDSL**. You can even generate those mocks from your OpenAPI definition using [KarateIDE](https://marketplace.visualstudio.com/items?itemName=KarateIDE.karate-ide) vscode extension.
- Request/response validation from your OpenAPI schemas.
- **Declarative stateless mocks** from your OpenAPI examples with `'x-apimock-when'`.
- Flexible and powerful **dynamic data generators** for your OpenAPI examples with `x-apimock-transform` (both built-in and custom defined).
- Use openapi examples to **populate your karate mocks** initial data with `x-apimock-karate-var` and `x-apimock-seed`.

### Karate+OpenAPI PetStore Contract Testing complete source code. ![General Availability](https://img.shields.io/badge/lifecycle-GA-green)

[This repo](https://github.com/ZenWave360/karate-openapi-petstore) contains a complete Contract Testing solution for the online demo REST API at https://petstore3.swagger.io/

You can find very detailed instructions at:

- [From Manual to Contract Testing with KarateDSL and KarateIDE](https://medium.com/@ivangsa/from-manual-to-contract-testing-with-karatedsl-and-karateide-i-5884f1732680)
- [High Fidelity Stateful Mocks (Consumer Contracts) with OpenAPI and KarateDSL](https://medium.com/@ivangsa/high-fidelity-stateful-mocks-consumer-contracts-with-openapi-and-karatedsl-85a7f31cf84e)

## ZenWave API Registry ![Comming Soon](https://img.shields.io/badge/lifecycle-Comming_Soon-lightgray)

- API & Models Artifact Files
- Full Text Search Index
- Addons:
  - API Quality (Linting results)
  - API Test Results
  - API Test Coverage
  - Dependencies graph
  -
