# [Angry Duck](https://github.com/Ninjaok/Angry-Duck) - [IADE](https://www.iade.europeia.pt/) - [UE](https://www.europeia.pt/)

**Universidade:** [Universidade Europeia](https://www.europeia.pt/)  
**Faculdade:** [IADE - Faculdade de Design, Tecnologia e Comunicação](https://www.iade.europeia.pt/)  
**Curso:** [Engenharia Informática](https://www.iade.europeia.pt/licenciaturas/engenharia-informatica/)  
**Disciplina:** Redes e Comunicações de Dados  
**Professor:** [Pedro Miguel Gomes Silva Rosa](https://www.linkedin.com/in/pedro-mgs-rosa/?originalSubdomain=pt)

## Índice

- [Índice](#índice)
- [Elementos do Grupo](#elementos-do-grupo)
- [Objetivo do Projeto](#objetivo-do-projeto)
- [Descrição](#descrição)
  - [Motivação](#motivação)
  - [Objetivo](#objetivo)
  - [Mercado e Público-Alvo](#mercado-e-público-alvo)
  - [Modelo de Negócio](#modelo-de-negócio)
  - [Localização](#localização)
    - [Requisitos da Localização](#requisitos-da-localização)
    - [Localização Escolhida](#localização-escolhida)
- [Infraestrutura do Edifício](#infraestrutura-do-edifício)
- [Sistema de IoT](#sistema-de-iot)
  - [Sistema de Emergência para Gases Nocivos](#sistema-de-emergência-para-gases-nocivos)
  - [Sistema de Incêndio](#sistema-de-incêndio)
  - [Sistema de Segurança](#sistema-de-segurança)
  - [Sistema de Controle de Temperatura](#sistema-de-controle-de-temperatura)
- [Equipamentos de Rede](#equipamentos-de-rede)
  - [Redes Interna](#redes-interna)
  - [Redes Externa](#redes-externa)
- [Resumo da Infraestrutura de Rede](#resumo-da-infraestrutura-de-rede)
  - [Resumo Redes Internas](#resumo-redes-internas)
  - [Resumo Redes Externa](#resumo-redes-externa)
-[Notas Adcionais](#notas-adicionais)

## Elementos do Grupo

- **[Luan Kacio da Silva Ribeiro](https://github.com/Ninjaok)** - 20230689
- **[Adjami Victor de Carvalho Regula](https://github.com/CFZ13)** - 20231145

## Objetivo do Projeto

O objetivo deste projeto foi criar um plano de infraestrutura de rede para os edifícios da **Angry Duck**, incluindo o edifício principal e um edifício secundário. O plano contemplou a distribuição dos equipamentos de rede, a conectividade entre os diferentes andares e áreas, além de um sistema de automação IoT, utilizando o **Cisco Packet Tracer** para simulação e modelagem da rede.

## Descrição

A **Angry Duck** é uma empresa dedicada à produção e fornecimento de produtos avícolas, comprometida com o bem-estar animal e a sustentabilidade. Nossa missão é oferecer ovos, carne, penas e outros derivados com máxima qualidade, garantindo um processo de criação responsável que reduz o estresse dos animais.  
Com um modelo de produção eco-friendly, utilizamos tecnologias inovadoras, como Internet das Coisas (IoT) e automação, para monitorar o ambiente e proporcionar as melhores condições para as aves. Além disso, valorizamos a transparência e a proximidade com nossos clientes, permitindo visitas às nossas instalações para que possam conhecer de perto nossos processos e o cuidado com os animais.  
Atendemos tanto consumidores individuais, que buscam alimentos frescos e saudáveis, quanto empresas do setor alimentício, têxtil e de utensílios domésticos que necessitam de matérias-primas de alta qualidade. Nosso sistema de delivery eficiente garante que nossos produtos cheguem com praticidade e frescor diretamente ao cliente.  
A **Angry Duck** está revolucionando o mercado avícola, unindo tradição, inovação e responsabilidade ambiental para construir um futuro mais sustentável para a produção de aves.

### Motivação

O amor pelos animais sempre foi a nossa maior inspiração. Acreditamos que todas as aves merecem um ambiente seguro, onde possam viver com dignidade e bem-estar. Foi essa paixão que nos motivou a criar a **Angry Duck**, uma empresa comprometida com práticas sustentáveis e um modelo de produção eco-friendly.  
Nosso objetivo vai além de fornecer produtos de qualidade queremos transformar a criação de aves, reduzindo o estresse dos animais e promovendo um equilíbrio entre a produção e o respeito à natureza.

### Objetivo

- Criar um ambiente seguro e sustentável para as aves, garantindo o bem-estar animal.
- Adotar práticas eco-friendly para reduzir o impacto ambiental da produção.
- Permitir um ambiente saudável para o desenvolvimento da comunidade, promovendo a criação de oportunidades de emprego e crescimento econômico local.
- Implementar tecnologias inovadoras, como IoT, para monitoramento e melhoria contínua dos processos.
- Avaliação e feedback contínuos para otimizar a qualidade dos produtos e serviços.
- Integração com mapas e navegação para facilitar a logística e a transparência na cadeia produtiva.

### Mercado e Público-Alvo

- Consumidores que buscam produtos avícolas de alta qualidade, frescos e sustentáveis.
- Supermercados, restaurantes e indústrias alimentícias interessadas em insumos confiáveis.
- Indústrias têxteis e fabricantes de utensílios domésticos que utilizam penas e outros derivados.
- Empresas e distribuidores que valorizam práticas sustentáveis e transparência na produção.

### Modelo de Negócio

- Venda direta de ovos, carne e derivados para consumidores finais.  
- Fornecimento de matéria-prima para indústrias e empresas parceiras.  
- Serviço de delivery para garantir a entrega eficiente e rápida de produtos frescos.  
- Parcerias estratégicas com supermercados, restaurantes e distribuidores.  
- Implementação de tecnologias para otimizar a rastreabilidade e a eficiência produtiva.

### Localização

#### [Requisitos da Localização](/Documentos/Briefing.pdf)

- **Localização:** Campus situado próximo a Coimbra, com potencial de expansão.  
- **Edifício Principal:**  
  - 6 andares, projetado para acomodar aproximadamente 100 funcionários, com previsão de duplicação em três anos.  
  - Infraestrutura de rede com backbone duplo, bastidores distribuídos por andar e conectados ao piso 1.  
  - Cobertura Wi-Fi com quatro pontos de acesso por andar.  
  - Datacenter localizado no piso 0 (160 m²), atuando como centro de comunicações.  
- **Edifício Secundário:**  
  - **Centralização:** Conectividade de internet e rede integradas ao Datacenter do edifício principal.  
  - **Expansão:** Estrutura preparada para suportar o crescimento do campus e a construção de novos edifícios.  

#### Localização Escolhida  

Com base nesses requisitos, selecionamos um [terreno](https://www.idealista.pt/imovel/33768148/) de 15.300 m², que oferece espaço adequado para a construção dos edifícios planejados. O valor do terreno é de 150.000,00 euros, conforme informações do site [Idealista.pt](https://www.idealista.pt).

## Infraestrutura do Edifício

- **Edifício Principal:**  

  - **Rés do Chão**
    - **Datacenter:** 160 m², com racks, servidores, switches e roteadores.
    - **Recepção:** 30 m², com balcão, sofás e sistema de controle de acesso.
    - **Loja:** 50 m², para venda de produtos avícolas e derivados.

  - **Primeiro Andar**
    - **Escritórios Administrativos:** 100 m², com salas de reunião e estações de trabalho.
    - **Recursos Humanos:** 50 m², com escritórios e sala de entrevistas.
    - **Vendas:** 50 m², com escritórios e sala de reuniões.

  - **Segundo Andar**
    - **Controle de Qualidade:** 100 m², com laboratórios e escritórios.
    - **Pesquisa e Desenvolvimento:** 100 m², com laboratórios e estações de trabalho.

  - **Terceiro Andar**
    - **TI e Suporte:** 100 m², com escritórios e sala de servidores.
    - **Marketing:** 100 m², com escritórios e sala de reuniões.

  - **Quarto Andar**
    - **Financeiro:** 100 m², com escritórios e sala de reuniões.
    - **Diretoria:** 100 m², com escritórios e sala de reuniões.

  - **Edifício Secundário:**
    - **Escritório de Monitoramento:** 50 m², com estações de trabalho e monitores.
    - **Viveiros:** 30 m² cada, para criação e monitoramento das aves.

## Sistema de IoT

O sistema de IoT foi dividido em quatro partes principais: sistema de emergência para detecção de gases nocivos, sistema de incêndio, sistema de segurança e sistema de controle de temperatura.

Para facilitar a implementação e a manutenção, os sistemas foram organizados de forma modular. Cada um desses módulos estará presente em todos os andares do edifício principal, no edifício secundário e também em áreas específicas já designadas, como os viveiros.

### Sistema de Emergência para Gases Nocivos

Este sistema tem como objetivo detectar a presença de gases perigosos no ambiente e atuar automaticamente para garantir a segurança. Ele é composto por:

- Sensor de CO₂
- Sensor de CO
- Sirene de alarme
- Sistema de ventilação autônoma
- Janelas de ventilação automatizadas

### Sistema de Incêndio

Projetado para identificar focos de incêndio e responder rapidamente para minimizar danos. Seus componentes incluem:

- Sensor de incêndio
- Sprinklers automáticos

### Sistema de Segurança

Responsável pelo controle de acesso e monitoramento de áreas restritas. Os principais elementos são:

- Portas de acesso automatizadas
- Leitor de cartões RFID

### Sistema de Controle de Temperatura

Esse sistema regula o ambiente térmico interno, proporcionando conforto e economia de energia. É composto por:

- Sensor de temperatura
- Central de controle de temperatura
- Ar-condicionado
- Aquecedor

## Equipamentos de Rede

### **Redes Interna**

#### **Rés do Chão**

- **Switch**
  - **Datacenter**
    - **Switch**
      - Servidor D-NS
      - Servidor FTP
      - Servidor Email
      - Servidor DHCP
      - Servidor Web
      - Servidor IOT
      - **IOT's**
        - Sistema de Emergência de Gases Nocivos
        - Sistema de Incêndio
        - Sistema de Segurança
        - Sistema de Controle de Temperatura

  - **Recepção**
    - Computador Pessoal (PC 1)
    - **IOT's**
      - Sistema de Emergência de Gases Nocivos
      - Sistema de Incêndio
      - Sistema de Segurança
      - Sistema de Controle de Temperatura

  - **Loja**
    - Computador Pessoal (PC 2)
    - **IOT's**
      - Sistema de Emergência de Gases Nocivos
      - Sistema de Incêndio
      - Sistema de Segurança
      - Sistema de Controle de Temperatura

#### **Primeiro Andar**

- **Switch**
  - **Escritórios Administrativos**
    - Computador Pessoal (3 PCs)
  - **Recursos Humanos**
    - Computador Pessoal (3 PCs)
  - **Vendas**
    - Computador Pessoal (3 PCs)
  - **IOT's**
    - Sistema de Emergência de Gases Nocivos
    - Sistema de Incêndio
    - Sistema de Segurança
    - Sistema de Controle de Temperatura

#### **Segundo Andar**

- **Switch**
  - **Controle de Qualidade**
    - Computador Pessoal (3 PCs)
  - **Pesquisa e Desenvolvimento**
    - Computador Pessoal (3 PCs)
  - **IOT's**
    - Sistema de Emergência de Gases Nocivos
    - Sistema de Incêndio
    - Sistema de Segurança
    - Sistema de Controle de Temperatura

#### **Terceiro Andar**

- **Switch**
  - **TI e Suporte**
    - Computador Pessoal (3 PCs)
  - **Marketing**
    - Computador Pessoal (3 PCs)
- **IOT's**
  - Sistema de Emergência de Gases Nocivos
  - Sistema de Incêndio
  - Sistema de Segurança
  - Sistema de Controle de Temperatura

#### **Quarto Andar**

- **Switch**
  - **Financeiro**
    - Computador Pessoal (3 PCs)
  - **Diretoria**
    - Computador Pessoal (3 PCs)
- **IOT's**
  - Sistema de Emergência de Gases Nocivos
  - Sistema de Incêndio
  - Sistema de Segurança
  - Sistema de Controle de Temperatura

#### **Edifício Secundário**

- **Switch**
  - **Escritório de Monitoramento**
    - Computadores de Controle (3 PCs)
    - **IOT's**
      - Sistema de Emergência de Gases Nocivos
      - Sistema de Incêndio
      - Sistema de Segurança
      - Sistema de Controle de Temperatura
  - **Viveiros**
    - **IOT's**
      - Sistema de Emergência de Gases Nocivos
      - Sistema de Incêndio
      - Sistema de Segurança
      - Sistema de Controle de Temperatura

### **Redes Externa**

- **Sites Externos**
  - **Router**
    - **Switch**
      - **Servidor**
        - `www.google.com`
        - `www.portal.pt`

## Resumo da Infraestrutura de Rede

### **Resumo Redes Internas**  

- **2 Roteadores**
- **9 Switches**
- **6 Servidores**
- **39 Computadores**
- **44 IoTs**

### **Resumo Redes Externa**

- **1 Roteador**
- **1 Switch**
- **2 Servidores Externos**  
  - `www.google.com`
  - `www.portal.pt`  

## Notas Adcionais

- A empresa foi concebida com foco em futuras expansões, e a quantidade apresentada neste projeto representa apenas os **requisitos mínimos** necessários para seu funcionamento inicial.
