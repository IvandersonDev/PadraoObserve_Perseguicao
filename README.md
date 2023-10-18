# Simulação de Perseguição Policial

Este é um projeto de simulação de uma perseguição policial em Java, usando o padrão Observer. O projeto inclui um carro roubado (observado) e viaturas de polícia (observadores) que seguem e registram os movimentos do carro roubado.

## Como Funciona

O projeto consiste em três classes principais:

1. `CarroRoubado` (Classe Observado):
   - Representa o carro roubado.
   - Mantém uma lista de observadores (viaturas).
   - Notifica os observadores sobre suas ações, como "frente", "esquerda", "direita" e "parar".

2. `Viatura` (Classe Observador):
   - Representa a viatura da polícia.
   - É registrada como observadora do carro roubado.
   - Registra as ações do carro roubado, como "frente", "esquerda", "direita" e "parar".

3. `Main` (Classe Principal):
   - No método `main`, criamos uma instância do carro roubado, duas viaturas e as registramos como observadoras do carro roubado.
   - Em seguida, simulamos os movimentos do carro roubado e das viaturas para demonstrar a perseguição.

## Como Executar

1. Certifique-se de ter o ambiente de desenvolvimento Java configurado.

2. Clone este repositório em sua máquina local.

3. Execute a classe `Main` para iniciar a simulação.

## Contribuições

Sinta-se à vontade para contribuir para este projeto. Você pode adicionar recursos, corrigir bugs ou melhorar a documentação.

## Agradecimento

Espero que este projeto seja útil e divertido! Se tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato.
