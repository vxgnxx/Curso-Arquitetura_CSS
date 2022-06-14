# Alura_Arquitetura-CSS
Curso de Arquitetura CSS da Alura, focado em Atomic Design e BEM Methodology

## [Atomic Design](https://atomicdesign.bradfrost.com/chapter-2/)
Atomic design é uma metodologia composta de cinco estágios diferentes que trabalham juntos para criar sistemas de design de interfaces de maneira mais deliberada e hierárquica. Esses cinco estágios são:

- Átomos
- Moléculas
- Organismos
- Templates
- Páginas

O atomic design não é um processo linear, mas sim um modelo mental para nos ajudar a pensar em nossas UI como um todo coeso e uma coleção de partes ao mesmo tempo. Cada um dos cinco estágios tem um papel essencial na hierárquia do nosso sistema de design de interfaces.

### 1. Átomos
> Atomos servem como a base da nossa interface, os tijolos que constroem toda UI. Os átomos incluem elementos HTML básicos como form labels, inputs, buttons, e outros que não podem ser divididos em pedaços menores sem deixarem de ser funcionais

### 2. Moléculas
> As moléculas são grupos relativamente simples de elementos da UI que funcionam juntos como uma coisa só. Por exemplo um form label, um input de pesquisa e um botão podem ser agrupados para criar uma molécula de um formulário de pesquisa

### 3. Organismos
> Organismo são grupos mais complexos formados por moléculas e/ou átomos e/ou outros organismo da UI. Esses organismo formam as diferentes seções da interface.

### 4. Templates
> Os templates são objetos de nível de página que colocam componentes em um layout e articulam a estrutura de conteúdo subjacente do design.

### 5. Páginas
> As páginas são instâncias específicas de templates que mostram a aparência de uma interface do usuário com conteúdo representativo real.

## [Metodologia BEM](https://en.bem.info/methodology/quick-start/)
BEM (Bloco, Elemento, Modificador) é uma abordagem baseada em componentes para o desenvolvimento web. A ideia é dividir a UI em blocos independentes. Isso faz o desenvolvimento de interfaces mais fácil e rápido até mesmo com uma UI complexa, e permite a reutilização de código já existente sem ctrl+c, ctrl+v
