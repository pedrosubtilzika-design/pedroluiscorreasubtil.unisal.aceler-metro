# Leitor de Acelerômetro — Pedro Luís Correa Subtil

Aplicação Android desenvolvida com Kotlin + Jetpack Compose e Material 3.

## Personalizações realizadas
- Cabeçalho com identificação do aluno.
- Indicador visual de sensor ativo.
- Agrupamento das leituras por eixo e das medições calculadas.
- Cards com cantos arredondados e elevação.
- Paleta Material 3 personalizada.
- Hierarquia visual com títulos, subtítulos e valores destacados.
- Descrição individual para X, Y e Z.
- Indicação explícita da unidade m/s².
- Atualização contínua dos sensores.

## Informações exibidas
- Aceleração no eixo X
- Aceleração no eixo Y
- Aceleração no eixo Z
- Aceleração linear
- Aceleração da gravidade

## Tecnologias
- Android Studio
- Kotlin
- Jetpack Compose
- Material 3
- SensorManager / sensores Android

## Pacote
`br.com.pedroluiscorreasubtil.acelerometro`

## Observação
Teste a aplicação no seu dispositivo/emulador e leia o código antes da entrega, especialmente a parte de SensorManager e das funções Compose.

### Comentários no código
Os comentários foram mantidos apenas nos pontos relevantes da implementação, como acesso aos sensores, atualização dos dados, eixos X/Y/Z, estado do Jetpack Compose e liberação do listener.
