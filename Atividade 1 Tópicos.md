**Importância dos testes automatizados**

Testes automatizados tem como objetivo minimizar os problemas da abordagem manual, uso de ferramentas para controlar a execução de testes de software, por meio da aplicação de estratégias.

A automação permite que o teste seja repetido várias vezes, sendo mais fácil encontrar novos erros através da repetição e da simulação de cenários específicos.

O foco da entrega contínua é entregar novos lançamentos de código o mais rápido possível para os clientes. O teste automatizado é fundamental para isso.

**Vantagens nos testes automatizados**

**1.** A automação dos testes vai reduzir a chance de termos erros nos testes;

**2.** Reduz a quantidade de esforços que seria realizado em testes manuais;

**3.** Testes automatizados são reutilizados poupam recursos humanos pois você não precisará da várias pessoas para realizar um teste manual;

**4.** Volume: testes automatizados permitem testar o software nos mais diversos dispositivos e cenários o que seria bem mais difícil de ser feito manualmente;

**5.** Redução de custos, ganho na qualidade gerando maior retorno em relação ao investimento realizado.

**O que são testes automatizados**

Testes automatizados se fundamentam no uso de ferramentas para controlar a execução de testes de software. Através da aplicação de estratégias, o objetivo é basicamente escrever um software que testará seu programa por você. No final o resultado esperado é um software com maior qualidade com a redução mínima possíveis de bugs da abordagem manual, saindo barato o seu custo final.

**O que são testes unitários**

Também conhecido como teste de unidade, testes unitários aferem a qualidade do código em sua menor fração. Eles também podem ser identificados como testes de algoritmos e, por isso, não dependem do uso de recursos externos.

São os testes mais baratos da pirâmide de testes. No entanto, geram menos valor para empresa, visto que sozinhos eles não garantem a corretude do código. Os testes unitários são os mais usados em qualquer projeto.

Teste unitário em poucas palavras é o teste da menor parte testável de um programa. Assim como teste automatizado não servem principalmente para verificar se uma função específica está funcionando, mas sim para garantir que sua aplicação continue funcionando após alguma alteração em sua base de código.

Teste unitário é toda a aplicação de teste nas assinaturas de entrada e saída de um sistema. Consiste em validade dados válidos e inválidos via I/O sendo aplicado por desenvolvedores ou analistas de teste.

**Algumas vantagens do teste unitário**

1. Eles não servem apenas para verificar se uma função está funcionando, mas sim para garantir que a função se mantenha em funcionamento após alguma alteração base do código;
2. prevenir problemas futuros;
3. garantir um software de qualidade;
4. aumentar a produtividade da pessoa desenvolvedora;
5. aumentar a velocidade do código;
6. garantir a eficiência do escopo escolhido.

**Pirâmide de teste**

**Unidade**: criado o teste de unidade eles são muito rápidos de executar enormes quantidades de testes em menor tempo. Por isso ele é tão barato e um dos mais utilizáveis, por executar grande quantidade de testes simultaneamente em pouquíssimo tempo, sendo um dos motivos de ser o preferido nas escolhas de testes. Uma outra característica é que o teste de unidade testa as pequenas partes de um sistema. Ele é um teste rápido, barato, economizando tempo e dinheiro que em programação são bem valiosos.

**Integração**: conforme subimos na pirâmide, os testes vão ficando mais caros e mais lentos de serem executados. Neste teste de integração temos teste de serviços, testes de API e etc. Quando iniciamos esse teste as unidades ja estão interagindo entre si, ja não são mais testes isolados. Não é necessário abrir uma tela, normalmente só verificamos se um componente de unidade está interagindo corretamente com o outro e se a integração entre elas estão funcionando corretamente. Por ser um teste de integração, API e que não precisa abrir a tela, acaba sendo mais rápido que testes que é necessário abrir a tela propriamente dito.

**E2E**: no teste E2E é o teste do topo da pirâmide, é o que vemos primeiro em relação a automação. Abrimos a tela e executamos como se fosse um usuário final, utilizando este sistema. Apesar desse teste ser o primeiro que vemos quando falamos de automação, ele é o mais caro possível. Ele depende de tudo funcionando perfeitamente. Ele verifica tudo de ponta a ponta e verifica se no final o resultado é o esperado, por isso que é o mais demorado e consequentemente o mais caro.
