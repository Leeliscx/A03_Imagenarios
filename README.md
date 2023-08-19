<h1 align="center">Aplicação de Visão Computacional no Reconhecimento de Sinais da Língua Americana de Sinais (ASL)</h1>

<table>
  <tbody>
    <tr>
      <td><p>1st Francieli Moreira de Carvalho</p>   <p><em>Instituto de Informática</em></p> <p><em>Universidade Federal de Goiás</em></p> <p>Goiânia, Brasil</p> <p>francielimoreira@discente.ufg.br</p></td>
      <td><p>2nd Jamil Soares da Silva Júnior</p><p><em>Instituto de Informática</em></p> <p><em>Universidade Federal de Goiás</em></p> <p>Goiânia, Brasil</p> <p>jamiljunior@discente.ufg.br</p></td>
      <td><p>3rd Letícia de Cerqueira Xavier </p><p><em>Instituto de Informática</em></p> <p><em>Universidade Federal de Goiás</em></p> <p>Goiânia, Brasil</p> <p>cerqueiraleticia@discente.ufg.br</p></td>
    </tr>
    <tr><td><p>4th Victor Guerreiro Pimenta</p><p><em>Instituto de Informática</em></p> <p><em>Universidade Federal de Goiás</em></p><p>Goiânia, Brasil</p> <p>victorguerreiro@discente.ufg.br</p></td></tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td width="50%" >
          <p><strong><em>Abstract - </em>Este projeto de visão computacional tem como objetivo aprimorar a comunicação entre pessoas surdas e ouvintes, focalizando na identificação e reconhecimento da                 Língua Americana de Sinais (ASL). Inicialmente, concentra-se na identificação dos gestos e sinais correspondentes às letras do alfabeto, abrangendo de A a Z. Isso possibilitará aos usuários               uma comunicação mais eficiente em atividades básicas de escrita e leitura, promovendo inclusão e acessibilidade. Embora a aplicação inicial não contemple a identificação imediata de outros                gestos e palavras da ASL, o principal objetivo é facilitar a compreensão e uso do alfabeto na língua.</strong></p>
          <p><strong><em>Index Terms - </em> ASL, reconhecimento, sistema, alfabeto, acessibilidade.</strong></p>
          <h3 align="center">I . Introdução</h3>
          <p>A tarefa de classificação desempenha um papel fundamental em diversos aspectos da vida cotidiana, permitindo a categorização eficaz de objetos com base em suas características distintas (SILVA, 2019). A capacidade de desenvolver algoritmos que possam discernir e agrupar objetos tem um impacto significativo, sendo um exemplo notável a identificação de placas de veículos, onde um algoritmo analisa as letras e as associa ao alfabeto, assemelhando-se ao reconhecimento de símbolos.</p>

<p>Além disso, a habilidade de criar algoritmos para identificar símbolos de linguagens também abre portas para aplicações de tradução. Contudo, é essencial compreender a complexidade da classificação da linguagem de sinais, que muitas vezes é desafiadora mesmo para indivíduos proficientes na Língua de Sinais Americana (ASL, do inglês American Sign Language).</p>

<p>Atualmente, há aplicativos que auxiliam na tradução da língua inglesa para ASL por meio de animações 3D de intérpretes. No entanto, existe uma lacuna no que diz respeito a soluções que possam realizar o processo inverso, ou seja, reconhecer o significado dos gestos por meio de câmeras e traduzi-los.</p>

<p>Este desafio é ainda mais complexo devido à diversidade dos movimentos das mãos, que exige uma distinção precisa das configurações das mãos e dedos. Isso acrescenta complexidade ao reconhecimento do significado do sinal.</p>

<p>Dado que a comunicação é essencial para a socialização, é imperativo explorar abordagens que facilitem a interação entre usuários de ASL e aqueles menos familiarizados com essa língua, a fim de promover a inclusão social. O uso de Redes Neurais Artificiais (RNA) para desenvolver sistemas inteligentes capazes de realizar tais traduções emerge como uma estratégia para aproximar a comunidade surda, que se comunica por meio de ASL, daqueles que não dominam a linguagem.</p>
          <h3 align="center">II . Fundamentos Teóricos</h3>     
          <p>Este capítulo tem como objetivo realizar uma contextualização de todos os temas necessários para o desenvolvimento deste trabalho. Para tal, esse capítulo se estrutura em seis tópicos, a saber: Língua de Sinais Americana; Visão Computacional; Aprendizado de Máquina; Redes Neurais Artificiais; Aprendizado Profundo e Redes Neurais Convolucionais.</p>
          <h4 align="center">2.1 Língua de Sinais Americana (ASL)</h4>
          <p>Língua de Sinais Americana (ASL): A Língua de Sinais Americana (ASL) é uma forma de comunicação visual-gestual vital para a comunidade surda nos Estados Unidos e Canadá. Originada no século XIX, a ASL possui uma estrutura gramatical única e desempenha um papel cultural significativo. Diferente das línguas orais, a ASL utiliza gestos, expressões faciais e posturas corporais para transmitir significado. Sua complexidade vai além da comunicação, refletindo a identidade e herança cultural dos surdos, além de desempenhar um papel fundamental na promoção da inclusão. Este estudo contribui para a identificação precisa dos gestos da ASL, especialmente nas letras do alfabeto, facilitando a comunicação e a compreensão.</p>
          <h4 align="center">2.2 Aprendizado de Máquina</h4>
         <p>O Aprendizado de Máquina envolve algoritmos que permitem a máquina aprender a partir de dados e melhorar seu desempenho em tarefas específicas. É uma ferramenta essencial para explorar padrões e tomar decisões inteligentes.</p>
     </td>
     <td width="50%">
        <h4 align="center">2.3 Aprendizado Profundo</h4>
        <p> O Aprendizado Profundo é uma vertente do Aprendizado de Máquina que utiliza Redes Neurais Artificiais (RNAs) para modelar tarefas complexas. As RNAs, inspiradas em neurônios biológicos, aprendem a partir dos dados, capturando padrões sutis.</p>
        
<h4 align="center">2.4 Redes Neurais Artificiais (RNAs)</h4>

<p>As RNAs são estruturas computacionais inspiradas no sistema nervoso biológico. Elas processam informações por meio de neurônios interconectados e são empregadas para resolver problemas complexos de classificação e regressão.</p>
<h3 align="center">III . Metodologia</h3>
<p>A metodologia adotada neste projeto visa desenvolver um modelo de aprendizado profundo capaz de classificar imagens em 29 categorias diferentes, correspondentes aos símbolos da Língua de Sinais Americana (ASL). Utilizamos a técnica de transferência de aprendizagem, empregando a arquitetura MobileNet, conhecida por sua eficiência em dispositivos móveis, como base para o nosso modelo.</p>
<h4 align="center">3.1 Modelo de Base</h4>
<p>A versão da MobileNet pré-treinada no conjunto de dados ImageNet foi selecionada como nosso modelo base. A eficiência e precisão dessa arquitetura a tornaram uma escolha apropriada para classificar os símbolos da ASL.</p>
<h4 align="center">3.2 Personalização do Modelo</h4>
<p>O modelo foi adaptado à nossa tarefa específica de classificação dos símbolos da ASL adicionando três camadas densas. As duas primeiras, com 128 unidades e função de ativação ReLU, foram projetadas para extrair características relevantes dos símbolos. A camada de saída, com 29 unidades e ativação softmax, foi configurada para classificar as imagens nas 29 categorias da ASL.</p>
<h4 align="center">3.3 Compilação e Treinamento</h4>
<p>O modelo foi compilado com o otimizador Adam e uma taxa de aprendizado de 0.001. Utilizamos a entropia cruzada categórica como função de perda e a acurácia como métrica de avaliação. O treinamento foi conduzido usando um conjunto específico de imagens representando os símbolos da ASL, seguido de validação e teste.
</p>
<h4 align="center">3.4 Aumento de Dados (Data Augmentation)</h4>
<p>No desenvolvimento do modelo, foram empregadas técnicas de aumento de dados para aprimorar a capacidade de generalização e robustez. Durante o pré-processamento das imagens, foram aplicadas rotações aleatórias, distorções de cisalhamento, deslocamentos horizontais e verticais, ajustes de zoom e espelhamento horizontal. Essas transformações foram aplicadas de forma aleatória e controlada, visando criar um conjunto de treinamento mais diversificado e representativo. A utilização dessas técnicas contribuiu significativamente para aprimorar a performance e a capacidade de generalização do modelo final.</p>

<h3 align="center">IV . Resultados</h3>
<p>Após a aplicação das técnicas de aumento de dados e o treinamento da arquitetura escolhida com pesos pré-treinados, constatou-se que a MobileNet alcançou um desempenho superior para o conjunto de dados.</p>

<p>Diante dos resultados obtidos, a MobileNet emergiu como a arquitetura selecionada para o reconhecimento de caracteres ASL, devido à sua performance com uma acurácia notável de 99.54% no conjunto de testes. Este estudo não apenas validou a eficácia do modelo escolhido, mas também confirmou visualmente sua capacidade de tradução, por meio da análise de exemplos específicos.</p>

<h3 align="center">V . Conclusão</h3>
<p>Em síntese, o desenvolvimento desse sistema de reconhecimento de caracteres ASL por meio de técnicas avançadas de aprendizado profundo e aumento de dados contribui substancialmente para a promoção da inclusão social, permitindo uma comunicação mais eficaz entre a comunidade surda e aqueles que não dominam a língua de sinais. Esse avanço representa um passo significativo em direção a um ambiente mais inclusivo e acessível para todos.</p>
     </td>
</tr>
<tr>
    <td> 
      <h3 align="center">VI . Referências</h3>
        <p>SILVA, G. F. d. Tecnologias assistiva e a deep learning: aplicativo com reconhecimento
de imagem no auxílio a deficientes visuais. 2019.</p>
        <p>LOCA, A.; RAUBER, T. Uso de uma rede neural convolucional unidimensional para
detecção de falhas em processos industriais. In: SBC. Anais da XIX Escola Regional de
Computação Bahia, Alagoas e Sergipe. [S.l.], 2019</p>
        <p>BALLARD, D. H. Ballard d. and brown cm 1982 computer vision. Image, 1982.</p>
        <p>DAVIES, E. R. Computer and machine vision: theory, algorithms, practicalities. [S.l.]:
Academic Press, 2012.</p>
        <p>CONCI, A.; AZEVEDO, E.; LETA, F. R. Computação gráfica. [S.l.]: Elsevier, 2008.</p>
        <p>FARIA, A. C. B. Classificação de estilos visuais utilizando aprendizado profundo. 2017.</p>
        <p>MITCHELL, R.; MICHALSKI, J.; CARBONELL, T. An artificial intelligence approach.
[S.l.]: Springer, 2013</p>
        <p>MCCULLOCH, W. S.; PITTS, W. A logical calculus of the ideas immanent in nervous
activity. The bulletin of mathematical biophysics, Springer, v. 5.</p>
        <p>MARTINS, V. E. Aplicação de deep learning para detecção de veias em carne suína.
2018.</p>
        <p>CARVALHO, H. M. Aprendizado de máquina voltado para mineração de dados: árvores
de decisão. 2014.</p>
        <p>TEIXEIRA, J. de F. Inteligência artificial. [S.l.]: Pia Sociedade de São Paulo-Editora
Paulus, 2014.</p>
        <p>LENT, D. M. B.; JR, M. L. P. Detecç ao de anomalias utilizando redes neurais
convolucionais. 2018</p>
        <p>PONTI, M. A.; COSTA, G. B. P. D. Como funciona o deep learning. arXiv preprint
arXiv:1806.07908, 2018.</p>
        <p>LECUN, Y. et al. Comparison of learning algorithms for handwritten digit recognition.
In: PERTH, AUSTRALIA. International conference on artificial neural networks. [S.l.],
1995. v. 60</p>
        <p>ARGAS, A. C. G.; PAES, A.; VASCONCELOS, C. N. Um estudo sobre redes neurais
convolucionais e sua aplicação em detecção de pedestres. In: SN. Proceedings of the xxix
conference on graphics, patterns and images. [S.l.], 2016.</p>
    </td>
</tr>
  </tbody>
</table>
