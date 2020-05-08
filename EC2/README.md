# ec2 - elastic computed cloud

## Benefícios

- elasticidade: acompanhar a demanda do usuário

- controle total: parar, reiniciar, excluir, hibernar

- flexibilidade: escolher instância adequada conforme aplicação

- integração: integração com outros serviços da AWS

- confiável: garantia de 99% de disponibilidade

- segurança: firewall de rede, firewall de software

- baixo custo: instância sob demanda, instância reservada(economia de até 75%)

- fácil: rapidamente é possível provisionar recursos.

## Escolher instância certa

Aplicação utiliza preferencialmente:

- memória
- cpu
- rede
- armazenamento

### Exemplo Famílias

- C: são otimizadas para computação (C4, C5 ...)
- M: são instâncias de uso genérico (M4, M5 ...)

### Escolher AMI (Amazon Machine Image)

Disponíveis imagens de sistemas operacionais para utilização nas aplicações.

Disponíveis nativamente, padrão ou com alguns recursos extras:

- Windows 10
- Red Hat
- Ubuntu
- Amazon Linux (Red Hat)

Outros sistemas operacionais e personalizações podem ser obtidos na AWS Marketplace.

Instâncias do tipo `free tier` são gratuitas enquanto sua conta estiver na categoria de bonificação (12 primeiros meses)

![image](resources/ami.png)
