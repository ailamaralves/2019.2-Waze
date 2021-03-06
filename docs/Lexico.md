# Léxico Aplicado da Linguagem

## 1. Introdução
<p align="justify">
O LAL (Léxico Aplicado da Linguagem) é uma técnica que procura descrever os símbolos de uma linguagem. A ideia central do LAL é a existência da linguagem de aplicação, e parte do princípio que no universo de informações existe uma ou mais culturas e que cada cultura (grupo social) tem sua linguagem própria. O objetivo dos engenheiros de requisitos é a identificação de palavras ou frases peculiares ao meio social da aplicação sob estudo.
</p>

## 2. Metodologia

| Tag léxico | Título |  
|--|--|
|**Data**| -- |
|**Hora**| -- |
|**Autor(es)**| -- |
|**Classificação**| --- |
|**Noção**| --- <br> ---|
|**Impacto**| --- <br> --- |
|**Rastro**| --- <br> --- |

## 3. Léxicos

### **L01 - Definir o destino**

| L01 | Definir o destino |  
|--|--|
|**Data**| 27/09 |
|**Hora**| 8:56 |
|**Autor(es)**| Renan Cristyan |
|**Classificação**| Verbo |
|**Noção**|O usuário digita na área de pesquisa uma palavra-chave|
|**Impacto**|O Waze irá calcular a melhor rota possível <br>|
|**Rastro**| [ST04](../Storytelling/#31-moscow) |

<br>

### **L02 - Smartphone**

| L02 | Smartphone |  
|--|--|
|**Data**| 29/09 |
|**Hora**| 16:40 |
|**Autor(es)**| Lucas Alexandre |
|**Classificação**| Objeto |
|**Noção**| Aparelho onde será instalado o Waze <br> Responsável pela interação entre o usuário e o app |
|**Impacto**| Através dele serão realizadas as tarefas do app <br> Feedback para o usuário |
|**Rastro**| [BS08](../Brainstorm/#moscow) |

<br>

### **L03 - Usuário está se locomovendo**

| L03 | Usuário está se locomovendo |  
|--|--|
|**Data**| 29/09 |
|**Hora**| 16:48 |
|**Autor(es)**| Renan Cristyan |
|**Classificação**| Estado |
|**Noção**| O Waze acessa a localização do usuário em tempo real <br> O usuário utiliza os recursos do app para orientação |
|**Impacto**| O Waze notifica o usuário caso alguma algum evento ocorra na rota |
|**Rastro**| [INS08](../introspeccao/#31-moscow), [ST01](../Storytelling/#moscow) |

<br>

### **L04 - Planejar rota**

| L04 | Planejar rota |  
|--|--|
|**Data**| 29/09 |
|**Hora**| 17:05 |
|**Autor(es)**| Matheus Estanislau |
|**Classificação**| Verbo |
|**Noção**| O usuário informa o local que deseja ir <br> O usuário informa o horário que deseja chegar |
|**Impacto**| O Waze calcula o transito e a rota <br> O Waze informa o usuário quando ele deve sair para chegar na hora desejada |
|**Rastro**| [INS08](../introspeccao/#31-moscow), [ST01](../Storytelling/#moscow) |

<br>

### **L05 - Veículo**

| L05 | Veículo |  
|--|--|
|**Data**| 29/09 |
|**Hora**| 17:15 |
|**Autor(es)**| Lucas Alexandre |
|**Classificação**| Objeto |
|**Noção**| Meio de transporte do usuário|
|**Impacto**| O usuário utiliza o veículo para se locomover <br> O Waze calcula a velocidade do veículo utilizando os sensores do smartphone <br> Através da velocidade do veículo o app informa caso o usuário esteja excedendo a velocidade da via |
|**Rastro**| [Q04](../Questionario/#moscow)|

<br>

### **L06 - O usuário está com pressa**

| L06 | O usuário está com pressa |  
|--|--|
|**Data**| 29/09 |
|**Hora**| 17:29 |
|**Autor(es)**| Renan Cristyan |
|**Classificação**| Estado |
|**Noção**| O usuário quer chegar ao seu destino o mais rápido possível <br> O usuário só quer do app a rota mais rápida possível e descarta as outras rotas mais lentas/longas|
|**Impacto**| O Waze mostra a rota mais rápida possível|
|**Rastro**| [ST01](../Storytelling/#moscow), [ST03](../Storytelling/#moscow)|

<br>

### **L07 - Feedback**

| L07 | Feedback |  
|--|--|
|**Data**| 29/09 |
|**Hora**| 17:46 |
|**Autor(es)**| Matheus Estanislau |
|**Classificação**| Verbo |
|**Noção**| Usuário quer informar os eventos da sua rota <br> O Waze disponibiliza uma ferramenta para o usuário fornecer feedback|
|Impacto| O Waze exibe o feedback para outros usuários em tempo real <br> |
|**Rastro**| [INS02](../introspeccao/#31-moscow) |

<br>

### **L08 - Avaliar feedback**

| L08 | Avaliar feedback |  
|--|--|
|**Data**| 29/09 |
|**Hora**| 17:57 |
|**Autor(es)**| Lucas Alexandre |
|**Classificação**| Verbo |
|**Noção**| O Waze mostra o feedback de vários usuários <br> O usuário confirma ou não se o feedback procede|
|**Impacto**| Se o feedback receber avaliações negativas ele será removido do app|
|**Rastro**| [BS13](../Brainstorm/#moscow)|

<br>

### **L09 - Mapa**

| L09 | Mapa |  
|--|--|
|**Data**|29/09|
|**Hora**| 20:00 |
|**Autor(es)**| Renan Cristyan |
|**Classificação**| Objeto |
|**Noção**| Waze utiliza para realizar cálculos e definir a melhor rota|
|**Impacto**| Usuário utiliza para se orientar e chegar ao destino <br> Usuário utiliza para procurar novos lugares interessantes|
|**Rastro**| [BS11](../Brainstorm/#31-moscow)|

<br>

### **L10 - Engarrafamento**

| L10 | Engarrafamento |  
|--|--|
|**Data**| 29/09 |
|**Hora**| 20:10 |
|**Autor(es)**| Matheus Estanislau |
|**Classificação**| Estado |
|**Noção**| Pista lenta/bloqueada <br> Usuário quer evitar a qualquer custo|
|**Impacto**| Através dos feedbacks de usuários, aquela rota não será oferecida pelo Waze aos usuários que podem passar por ali|
|**Rastro**| [ST01](../Storytelling/#moscow) |

<br>

### **L11 - Fiscalização eletrônica**

| L11 | Fiscalização eletrônica | 
|--|--|
|**Data**| 29/09 |
|**Hora**| 20:18 |
|**Autor(es)**| Lucas Alexandre |
|**Classificação**| Objeto |
|**Noção**| Objeto que registra a velocidade do veículo ao passar por ele <br> O Waze exibe as localizações das barreiras eletrônicas|
|**Impacto**| Se a velocidade for maior que a da via, o dono do veículo receberá uma multa <br> O usuário pode informar a localização de barreiras eletrônicas|
|**Rastro**| [Q04](../Questionario/#moscow)|

<br>

### **L12 - Consultar postos de combustível**

| L12 | Consultar postos de combustível |  
|--|--|
|**Data**| 29/09 |
|**Hora**| 20:30 |
|**Autor(es)**| Renan Cristyan |
|**Classificação**| Verbo |
|**Noção**| O usuário quer saber os postos de combustível mais próximos <br> O usuário quer saber o preço dos postos de combustível próximos|
|**Impacto**| O Waze informa o posto de combustível mais próximo <br> O Waze informa o preço dos combustíveis dos postos |
|**Rastro**| [ST02](../Storytelling/#moscow)|

<br>

### **L13 - Acidentes na rota**

| L13 | Acidentes na rota |  
|--|--|
|**Data**| 29/09 |
|**Hora**| 20:54 |
|**Autor(es)**| Matheus Estanislau |
|**Classificação**| Estado |
|**Noção**| O usuário quer ser informado de acidentes na pista <br> Os usuários podem informar sobre acidentes na rota|
|**Impacto**| O Waze informa se ocorreu algum acidente na rota do usuário <br>|
|**Rastro**| [Q05](../Questionario/#moscow), [AP09](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)|

<br>

### **L14 - Eventos**

| L14 | Eventos |  
|--|--|
|**Data**| 29/09 |
|**Hora**| 21:10 |
|**Autor(es)**| Lucas Alexandre |
|**Classificação**| Estado |
|**Noção**| O Waze acessa os eventos das redes sociais do usuário|
|**Impacto**| O Waze indica as rotas para esses eventos|
|**Rastro**| [BS12](../Brainstorm/#moscow) |

<br>

### **L15 - Adicionar locais favoritos**

| L15 | Adicionar locais favoritos |  
|--|--|
|**Data**| 30/09 |
|**Hora**| 14:00 |
|**Autor(es)**| Renan Cristyan |
|**Classificação**| Verbo |
|**Noção**| Usuário quer adicionar locais para ter acesso mais rápido <br> Usuário acessa facilmente os favoritos, sem precisar reescrever o local sempre que usar o app|
|**Impacto**| O Waze salva os locais favoritos e exibe de maneira clara para o usuário|
|**Rastro**| [BS02](../Brainstorm/#moscow) |

<br>

### **L16 - Ouvir músicas no aplicativo**

| L16 | Ouvir músicas no aplicativo |  
|--| -- |
|**Data**| 30/09 |
|**Hora**| 14:15 |
|**Autor(es)**| Renan Cristyan |
|**Classificação**| Verbo |
|**Noção**| Usuário quer ouvir músicas enquanto utiliza o app <br>|
|**Impacto**| O Waze disponibiliza uma ferramenta que é integrada com aplicativos de música como Spotify e Deezer <br> Usuário utiliza os mapas para se orientar e ouve música ao mesmo tempo com o Waze|
|**Rastro**| [Q02](../Questionario/#moscow), [BS10](../introspeccao/#31-moscow)|

<br>

### **L17 - Utilizar o Waze onde não há sinal de internet**

| L17 | Utilizar o Waze onde não há sinal de internet |  
|--| -- |
|**Data**| 30/09 |
|**Hora**| 20:05 |
|**Autor(es)**| Lucas Alexandre |
|**Classificação**| Verbo |
|**Noção**| Um usuário que estiver viajando quer ser capaz de usar a navegação do Waze mesmo em lugares sem sinais |
|**Impacto**| O Waze é capaz de funcionar mesmo quando não há internet |
|**Rastro**| [Q03](../Questionario/#moscow), [BS16](../introspeccao/#31-moscow) |

### **L18 - Definir casa**

| L18 | Definir casa |  
|--|--|
|**Data**| 15/10 |
|**Hora**| 08:50 |
|**Autor(es)**| Renan Cristyan |
|**Classificação**| Verbo |
|**Noção**| Usuário quer definir o local da sua casa para acesso rápido <br> Útil para evitar digitar o mesmo local várias vezes|
|**Impacto**| A localização informada como "Casa" se torna um atalho no menu de busca do aplicativo <br> O acesso às rotas é muito mais rápido e prático |
|**Rastro**| [BS02](../Brainstorm/#moscow) |

### **L19 - Definir trabalho**

| L19 | Definir trabalho |  
|--|--|
|**Data**| 15/10 |
|**Hora**| 09:00 |
|**Autor(es)**| Renan Cristyan |
|**Classificação**| Verbo |
|**Noção**| Usuário quer definir o local do seu trabalho para acesso rápido <br> Útil para evitar digitar o mesmo lugar várias vezes|
|**Impacto**| A localização informada como "Trabalho" se torna um atalho no menu de busca do aplicativo <br> O acesso às rotas é muito mais fácil e prático |
|**Rastro**| [BS02](../Brainstorm/#moscow) |

### **L20 - Configurar ou Personalizar**

| L20 | Configurar/Personalizar |  
|--|--|
|**Data**| 15/10 |
|**Hora**| 09:10 |
|**Autor(es)**| Renan Cristyan |
|**Classificação**| Verbo |
|**Noção**| Usuário deseja alterar alguma configuração do aplicativo <br> Usuário deseja personalizar alguma funcionalidade do aplicativo |
|**Impacto**| Após acessar a área "Configurações", é possível alterar uma série de configurações do aplicativo, como notificações, idioma, pesquisa por voz, entre outras|
|**Rastro**| [INS07](../introspeccao/#31-moscow), [AP02](../analiseProtocolo/#41-moscow) |


### **L21 - Criar uma conta**

| L21 | Criar uma conta |  
|--|--|
|**Data**| 15/10 |
|**Hora**| 09:20 |
|**Autor(es)**| Renan Cristyan |
|**Classificação**| Verbo |
|**Noção**| Usuário quer trocar de dispositivo mas não quer ter que transferir todos os locais favoritos manualmente <br> Usuário pode criar uma conta gratuita no Waze|
|**Impacto**| Apesar de não ser obrigatório, criar uma conta no Waze oferece benefícios interessantes, como ter os locais favoritos salvos caso o usuário troque de dispositivo|
|**Rastro**| [INS07](../introspeccao/#31-moscow) |


## 4. Referências Bibliográficas

> Léxico Aplicado da Linguagem (Resumo). Disponível em: http://www-di.inf.puc-rio.br/~julio/lal.pdf Acesso em: 27/09/19

> Waze - Política de Privacidade. Disponível em : https://www.waze.com/pt-BR/legal/privacy Acesso em: 29/09/19

## 5. Histórico de versões

| Data | Versão | Descrição | Autor(es) |
|:--:|:--:|:--:|:--:|
|24/09/19|1.0|Criação do documento|Renan Cristyan|
|27/09/19|1.1|Inclusão na Wiki|Renan Cristyan|
|27/09/19|1.2|Adicionados introdução, referências bibliográficas e histórico de versões|Renan Cristyan|
|29/09/19|1.3|Várias inclusões de léxicos|Lucas Alexandre, Matheus Estanislau, Renan Cristyan|
|30/09/19|1.4|Adicionado Rastro aos Léxicos| Matheus Estanislau, Lucas Alexandre|
|30/09/19|1.5|Adicionado L16|Renan Cristyan|
|30/09/19|1.6|Refatorado o documento|Lucas Alexandre, Matheus Estanislau|
|30/09/19|1.7|Adicionado L17|Lucas Alexandre|
|01/10/19|1.8|Adicionado mais rastros| Matheus Estanislau|
|15/10/19|1.9|Adicionados L18, L19, L20 e L21|Renan Cristyan|
|23/10/19|2.0|Adicionado rastros L14,L18,L19,L21|Lucas Alexandre, Moacir Mascarenha|
|14/11/19|3.0|Correções feitas a partir da verificação|João Pedro, Renan Cristyan|
