# 💰 Controle de Gastos

Aplicação em Java para registrar receitas e despesas, ver o saldo e filtrar por categoria.

O projeto começa simples, no console, e cresce em etapas junto com o meu estudo de Java até virar uma **API REST com Spring Boot**.

> 🚧 Em desenvolvimento. Estou aprendendo Java e este projeto é o meu primeiro passo para backend.

## Etapas

- [ ] **Etapa 1: Java puro no console** (classes, `enum`, `ArrayList`, menu)
- [ ] **Etapa 2: Persistência em arquivo**, tratamento de erros e testes simples
- [ ] **Etapa 3: API REST com Spring Boot** e banco de dados

### Etapa 1: o que vai ter

- [ ] Estrutura do projeto e README
- [ ] Classe `Transacao` (descrição, valor, data, tipo)
- [ ] `enum` para tipo (receita/despesa) e para categoria
- [ ] Lista de transações com `ArrayList`
- [ ] Menu no console (adicionar, listar, ver saldo)
- [ ] Filtrar transações por categoria

## Tecnologias

- Java 17
- Maven

## Como rodar

Pré-requisitos: JDK 17 ou superior e Maven.

```bash
git clone https://github.com/LuisGCS/controle-de-gastos.git
cd controle-de-gastos
mvn compile
java -cp target/classes br.com.luisgcs.controledegastos.Main
```

Ou abra a pasta no IntelliJ IDEA e execute a classe `Main`.

## Estrutura

```
controle-de-gastos/
├── pom.xml
└── src/main/java/br/com/luisgcs/controledegastos/
    └── Main.java
```

## Autor

Feito por [Luis Guilherme](https://github.com/LuisGCS).
