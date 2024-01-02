# DIO - Trilha .NET - Programação orientada a objetos

Mais um `Projeto na Linguagem de Programação C#`e também mais um desafio da trilha `.NET` do Decola Tech Avanade 4ª Edição 2024. 

## Resultado do Projeto
<img>

## Tecnologias Utilizadas

| Linguagens de Programação | Ferramentas e Tecnologias |
| :-----------------: | :-----------------------: |
| <img height="40" src="https://github.com/rhayssakramer/rhayssakramer/blob/main/assets/icon/C%23.svg"> <img height="40" src="https://github.com/rhayssakramer/rhayssakramer/blob/main/assets/icon/dotnet.svg"> <img height="40" src="https://github.com/rhayssakramer/rhayssakramer/blob/main/assets/icon/NodeJS-Dark.svg"> | <img height="40" src="https://github.com/rhayssakramer/rhayssakramer/blob/main/assets/icon/VSCode-Dark.svg">

## Requisitos do Projeto

#### Projeto - Sistema de Celulares

- Desafio de projeto: Para este desafio, foi preciso usar os conhecimentos adquiridos no módulo de orientação a objetos, da trilha .NET da DIO.

- Contexto: Na proposta desafio o desenvoledor é responsável por modelar um sistema que trabalha com celulares. Para isso, foi solicitado que você faça uma abstração de um celular e disponibilize maneiras de diferentes marcas e modelos terem seu próprio comportamento, possibilitando um maior reuso de código e usando a orientação a objetos.

- Proposta: Foi preciso criar um sistema em .NET, do tipo console, mapeando uma classe abstrata e classes específicas para dois tipos de celulares: Nokia e iPhone. Foi preciso criar as classes de acordo com o diagrama abaixo:

<img width="220" src="">

#### Contém três classes com as seguintes propriedades:

- Smartphone: `numero`  (string), `modelo`  (string), `imei` (string) e `memoria` (int). Sendo modelo, IMEI e memoria `privadas` e numero `pública`.  
- Iphone: numero, modelo, imei e memoria com herança da classe smartphone.
- Nokia: numero, modelo, imei e memoria com herança da classe smartphone.

#### E métodos:

- Smarthpone: `Ligar()`, `ReceberLigacao()` e `IntalarAplicativos` (abstract).
- Iphone: `InstalarAplicativos` (string nome) com herança da classe Smartphone.
- Nokia: `InstalarAplicativos` (string nome) com herança da classe Smartphone..

### Regras e validações
1. A classe Smartphone deve ser abstrata, não permitindo instanciar e servindo apenas como modelo.
2. A classe Nokia e Iphone devem ser classes filhas de Smartphone.
3. O método InstalarAplicativo deve ser sobrescrito na classe Nokia e iPhone, pois ambos possuem diferentes maneiras de instalar um aplicativo.

### Solução
O código está pela metade, e você deverá dar continuidade obedecendo as regras descritas acima, para que no final, tenhamos um programa funcional. Procure pela palavra comentada "TODO" no código, em seguida, implemente conforme as regras acima.

#### Especificações de conteúdo:
- Sua composição de sistema (classes, propriedades e métodos).
- A saída deve exibir as classes e métodos para testes.

#### Especificações técnicas:
- Todos os dados são capturados pelo sistema.
- Exibir as mensagens apropriadas a cada situação  para eficiência dos testes..
- Compor os parâmetros para as propriedades.
- Utilize propriedades privadas e pública.

### Instruções de Uso

1. Clone ou baixe este repositório para a sua máquina local.

2. Certifique-se de ter o [Node.js](https://nodejs.org/en/download/current) e [.NET 8.0](https://dotnet.microsoft.com/pt-br/download) instalado em sua máquina.

3. Abra o terminal e navegue até o diretório raiz do projeto.

4. Para executar, utilize o comando:
```
dotnet run
```

### Créditos
Este projeto foi desenvolvido como parte de avaliação de desafio do Decola Tech Avanade 4ª Edição 2024, para avaliar o ensinado na bootcamp de POO da linguagem de programação `C#`.

*Nota: Este projeto é apenas para fins educacionais e não possui nenhuma afiliação oficial com a franquia DIO ou Avanade ou suas empresas associadas.*

## Autora:
<table>
  <tr>
    <td>
      <img width="80px" align="center" src="https://github.com/rhayssakramer/rhayssakramer/blob/main/assets/images/logo.png"/>
    </td>
    <td align="left">
      <a href="https://github.com/rhayssakramer">
        <span><b>Rhayssa Kramer</b></span>
      </a>
      <br>
      <span>Desenvolvedora Full Stack</span>
    </td>
  </tr>
</table>

##
<div align="center">Feito por <a href="https://github.com/rhayssakramer">@devrhakramer</a>.</div>