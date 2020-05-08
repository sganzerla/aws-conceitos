# aws-conceitos

AWS Cloud

Utilização de recursos computacionais e infraestrutura sob demanda.

## Formas de provisionamento de recursos AWS

- Console: site web de fácil uso com interface gráfica

- CLI: Command line interface, linha de comando

- SDK: kit de desenvolvimento de software

## Benefícios

- Custos variáveis sob demanda

- Não desperdiça recursos computacionais e nem deixa ficar sobrecarregado por escalar sob demanda recursos

- Upgrade e Downgrade de recursos computacionais em minutos

- 22 regiões e 69 Zonas de disponibilidades

## Regiões

Pontos geográficos ao redor do mundo com datacenters e instraestrutura da AWS.

Cada região conta com zonas de diponibilidades isoladas uma da outra e afastadas geograficamente afim de manter os serviços em funcionamente em casos de falha em uma zona específica.

A escolha das regiões deve ser guiada pelos tópicos:

- 1° requisito legais, dados do governo, legislação
- 2° proximidade dos clientes, baixa latência
- 3° disponibilidade de algum serviço
- 4° custos da região

Edge locations, é um datacenter próximo as zonas de disponibilidade que mantém cache de arquivos estáticos melhorando a latência dos acessos, funciona com um CDN.
