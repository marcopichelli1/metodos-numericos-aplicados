Métodos Iterativos -
São métodos que utilizam uma estimativa inicial e depois aplicam repetidamente uma fórmula para obter uma melhor aproximação da solução. Alguns exemplos de métodos iterativos são:

• Método Newton-Raphson - Este é um método para encontrar as raízes de uma equação não linear usando a derivada da função.

• Método Secante - Este é um método para encontrar as raízes de uma equação não linear usando uma linha secante que passa por dois pontos na função.

• Método de Iteração de Ponto Fixo - Este é um método para encontrar as raízes de uma equação não linear reescrevendo-a como x = g(x) e então iterando x = g(x) até a convergência.

• Eliminação de Gauss - Este é um método para resolver um sistema de equações lineares reduzindo a matriz a uma forma triangular superior usando operações elementares com linhas.

• Gauss-Seidel - Este é um método para resolver um sistema de equações lineares usando um esquema iterativo que atualiza cada variável por vez.

• Método da Bissecção - Este é um método para encontrar a raiz de uma função dentro de um determinado intervalo, dividindo repetidamente o intervalo pela metade e identificando o subintervalo em que a raiz se encontra, convergindo para a raiz através de refinamento iterativo.

Métodos de interpolação -
São métodos que estimam o valor de uma função em um determinado ponto usando valores conhecidos da função em outros pontos. Alguns exemplos de métodos de interpolação são:

• Interpolação direta de Newton - Este é um método para interpolar uma função usando uma tabela de diferenças diretas e um polinômio de grau n-1 que passa por n pontos dados.

• Interpolação inversa de Newton - Este é um método para interpolar uma função usando uma tabela de diferenças inversas e um polinômio de grau n-1 que passa por n pontos dados.

• Interpolação de Lagrange - Este é um método para interpolar uma função usando um polinômio de grau n-1 que passa por n pontos dados.

• Interpolação Inversa de Lagrange - Este é um método para encontrar o valor de uma variável x que corresponde a um determinado valor de uma função y usando um polinômio de grau n-1 que passa por n pontos dados (x_i, y_i).

Métodos Numéricos Diferenciais-Integrais -
Estes são os métodos utilizados para aproximar os valores de derivadas e integrais de funções matemáticas, utilizados quando é difícil ou impossível obter soluções analíticas exatas para problemas de diferenciação ou integração:

• Regra da Quadratura - Este é um método para aproximar a área sob uma curva avaliando a função em pontos específicos e usando pesos correspondentes.

• Regra trapezoidal - Este é um método para aproximar integrais definidas dividindo o intervalo de integração em trapézios menores e estimando a área sob a curva como a soma das áreas desses trapézios.

• Regra de Simpson - A regra de Simpson é um método para aproximar integrais definidas dividindo o intervalo de integração em intervalos menores e aproximando a área sob a curva usando polinômios quadráticos, fornecendo uma estimativa mais precisa em comparação com a regra trapezoidal.

• Regra de Romberg - Este é um método para melhorar a precisão da integração numérica, refinando e extrapolando iterativamente as estimativas obtidas a partir da regra trapezoidal.

Características:
• Cálculo de Raiz - Os programas podem calcular as raízes de equações não lineares usando vários métodos iterativos. Você pode escolher o método que melhor se adapta ao seu problema e ajustar os parâmetros como tolerância, iterações máximas, estimativa inicial, etc.

• Raízes Positivas ou Negativas - Os programas podem encontrar raízes positivas e negativas de equações não lineares. Você pode especificar o sinal da raiz desejada ou deixar o programa encontrar qualquer raiz disponível.

• Opção de valor X_Nought personalizado - Os programas permitem que você insira sua própria estimativa inicial para os métodos iterativos. Você pode usar esta opção para acelerar a convergência ou evitar mínimos ou máximos locais.

• Resolve equações contendo Logs, exponenciais, números de Euler, funções trigonométricas e, claro, divisão e multiplicação - Oss programas podem lidar com vários tipos de equações não lineares que envolvem diferentes funções e operações matemáticas. Você pode inserir sua equação usando a sintaxe Python e os programas irão avaliá-la corretamente.

• Fornece o valor de todas as iterações em formato tabular - Os programas podem mostrar o valor de cada iteração para os métodos iterativos. Você pode usar esse recurso para monitorar o progresso e a precisão da solução. Isso é mostrado em uma forma tabular que é fácil de seguir.

• Fornece o valor de ambas as raízes - Os programas podem encontrar as raízes positivas e negativas de uma equação quadrática usando a fórmula quadrática. Você pode inserir os coeficientes da equação e os programas calcularão e exibirão ambas as raízes.

• Visualiza cálculos matriciais - Os programas podem visualizar as operações matriciais envolvidas na resolução de um sistema de equações lineares usando métodos de eliminação de Gauss ou Gauss-Seidel. Você pode ver como a matriz é transformada em uma forma triangular superior ou como as variáveis ​​são atualizadas em cada iteração. Isso pode ajudá-lo a entender melhor os métodos e verificar se há erros.

• Iterações de saída em formato tabular - implementa funções tabulares sempre que possível para dar à saída dos programas uma boa legibilidade e uma aparência sofisticada.

Requisitos
• Pré-requisito = Módulo Sympy, Módulo Math, Módulo Numpy - Você precisa instalar esses módulos antes de executar. Você pode usar pip ou conda para instalá-los a partir da linha de comando. Por exemplo, para instalar o sympy usando pip, você pode digitar:

pip install sympy

• Copie o código

• Basta copiar e colar os programas do repositório em seu IDE e executá-los! -

• Para executar um programa, basta copiar e colar o código em seu IDE e depois executá-lo. Você verá algumas instruções e avisos sobre como usar o programa e inserir suas entradas
