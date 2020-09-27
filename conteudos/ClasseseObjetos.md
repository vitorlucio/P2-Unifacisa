# Classes e Objetos

Classes definem a especificação de entidades, trazendo consigo uma série de atributos e comportamentos (funções). Objetos são criados a partir de classes, e quando criados tipicamente assumem diferentes valores para atributos, e podem executar as funções.

Analogia:

Planta baixa seria uma classe, e a casa seria o objeto. Note que várias casas (objetos) com detalhes (valores de atributos) diferentes podem ser construídas a partir de uma planta baixa (classe).
Uma refeição pode ser representada em uma classe, e o almoço/jantar feito pronto seria o objeto. Note que várias almoços/jantares (objetos) com detalhes (valores de atributos) diferentes podem ser construídos a partir de uma especificação de refeição alterando alguns detalhes.

A palavra chave new permite a criação de novos objetos. No main, criamos um objeto de Refeição, que basicamente é um almoço. Poderíamos criar vários objetos almoços, iguais ou diferentes (em termos de comida), bem como também poderíamos criar outros tipos de refeição como jantar e café da manhã.
Quando acionamos new Refeicao(), estamos chamando o contrutor da classe Refeicao. Contrutores são métodos que permitem a criação de objetos, e são acionado pela palavra reservada new. Embora a classe Refeicao não apresente um contrutor de forma explícita, a JVM injeta o construtor padrão (ou default). Construtores padrões não têm argumento. De forma resumida, para a JVM, a classe Refeicao aparece da seguinte forma:
