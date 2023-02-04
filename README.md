# Para que e como usar o arquivo LICENSE na prática (Tutorial)

Bem-vindo ao nosso tutorial sobre LICENSE em projetos open source. Neste tutorial, você aprenderá sobre a importância de incluir um arquivo LICENSE em seus projetos open source e como escolher a licença apropriada para o seu projeto. Você também aprenderá como criar e adicionar o arquivo LICENSE ao seu repositório no GitHub. É importante destacar que a inclusão de uma licença clara e apropriada é essencial para garantir a proteção de seu código e direitos autorais, bem como para ajudar a promover a colaboração e o compartilhamento de código em comunidades de desenvolvimento de software. Então, vamos começar!

Vamos exemplificar esse tutorial, criando um arquivo LICENSE para um projeto em Python:

A integração de um arquivo de LICENSE em um projeto Python é bastante simples. Siga os seguintes passos:

1. Crie um novo arquivo com a extensão `.txt` ou `.md` na raiz do seu projeto com o nome "LICENSE".
2. Abra o arquivo e adicione o texto da licença que deseja utilizar. Existem várias licenças populares disponíveis, como a licença MIT, a licença Apache e a licença GPL, entre outras.
3. Adicione o arquivo de LICENSE ao seu repositório local:![1675501385154](image/README/1675501385154.png)
4. Faça um commit das alterações:![1675501554840](image/README/1675501554840.png)
5. Envie as alterações para o seu repositório remoto:![1675501616124](image/README/1675501616124.png)

Observe que neste exemplo, estamos enviando as alterações para a branch `main`. Se você deseja enviar as alterações para outra branch, basta substituir `main` pelo nome da branch desejada.

As licenças MIT, Apache e GPL são três das licenças de software mais populares e amplamente utilizadas em projetos de código aberto. A seguir, apresentamos o texto de cada uma dessas licenças:

**Licença MIT**:

```vbnet
The MIT License (MIT)

Copyright (c) [ano] [nome do autor]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

**Licença Apache**:

```vbnet
Apache License
Version 2.0, January 2004
http://www.apache.org/licenses/

TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

1. Definitions.

"License" shall mean the terms and conditions for use, reproduction, and distribution as defined by Sections 1 through 9 of this document.

"Licensor" shall mean the copyright owner or entity authorized by the copyright owner that is granting the License.

"Legal Entity" shall mean the union of the acting entity and all other entities that control, are controlled by, or are under common control with that entity. For the purposes of this definition, "control" means (i) the power, direct or indirect, to cause the direction or management of such entity, whether by contract or otherwise, or (ii) ownership of fifty percent (50%) or more of the outstanding shares, or (iii) beneficial ownership of such entity.

"You" (or "Your") shall mean an individual or Legal Entity exercising permissions granted by this License.

"Source" form shall mean the preferred form for making modifications, including but not limited to software source code, documentation source, and configuration files.

"Object" form shall mean any form resulting from mechanical transformation or translation of a Source form, including but not limited to compiled object code, generated documentation, and conversions to other media types.

"Work" shall mean the work of authorship, whether in Source or Object form, made available under the License, as indicated by a copyright notice that is included in or attached to the work (an example is provided in the Appendix below).

"Derivative Works" shall mean any work, whether in Source or Object form, that is based on (or derived from) the Work and for which the editorial revisions, annotations
```

A **licença GPL (GNU General Public License)** é uma licença de código aberto, que permite que o código seja distribuído e modificado, desde que as modificações também sejam disponibilizadas como código aberto. A GPL é amplamente utilizada para garantir que software livre e de código aberto continue sendo livre e de código aberto.

O texto de licença da GPL pode ser encontrado em vários sites na internet, incluindo o site da Free Software Foundation (FSF). Além disso, existe a versão 3 da licença, que é amplamente utilizada. O texto completo da licença pode ser encontrado em: [https://www.gnu.org/licenses/gpl-3.0.pt-br.html](https://www.gnu.org/licenses/gpl-3.0.pt-br.html).

Para incluir a licença GPL em um projeto, basta criar um arquivo chamado LICENSE no diretório raiz do projeto e copiar o texto da licença para dentro desse arquivo. Depois, você pode adicionar e fazer o commit do arquivo LICENSE para o seu repositório Git e fazer o push para o Github.

### **Qual o tipo de licença mais comum para aplicativos open source nas seguintes versões: Python, C++ e HTML/CSS/JavaScript?**

A licença mais comum para aplicativos open source em Python é a MIT License. É uma licença permissiva e de código aberto que permite a utilização do software para qualquer finalidade, incluindo comercial, sem a necessidade de fornecer código-fonte ou de reconhecer a contribuição do autor original.

Para aplicativos open source em C++, a licença mais comum é a GNU General Public License (GPL). É uma licença copyleft que exige que todas as modificações e distribuições subsequentes do código sejam disponibilizadas como código aberto.

Para aplicativos open source em HTML/CSS/JavaScript, a licença mais comum é a MIT License ou a Apache License. Ambas são licenças permissivas que permitem a utilização do software para qualquer finalidade, incluindo comercial, sem a necessidade de fornecer código-fonte ou reconhecer a contribuição do autor original.

### É necessário colocar .md ou .txt no arquivo LICENSE?

Não há necessidade de colocar .md ou .txt no arquivo LICENSE. A extensão .txt é a mais comum, pois é fácil de ser lida por qualquer editor de texto, enquanto que a extensão .md é usada para arquivos markdown. A escolha da extensão dependerá da convenção adotada pelo projeto, mas ambas as extensões são aceitas e funcionam para arquivos LICENSE.

*É uma prática comum não colocar a extensão no arquivo LICENSE*. A maioria dos projetos não inclui a extensão e simplesmente o nomeia como LICENSE, **o que é uma boa prática**. Isso ajuda a manter a clareza e a simplicidade na organização dos arquivos do projeto, além de ser fácil de identificar e localizar para outros desenvolvedores. Além disso, a extensão não é realmente necessária, já que o conteúdo do arquivo é o mais importante, não a sua extensão.
