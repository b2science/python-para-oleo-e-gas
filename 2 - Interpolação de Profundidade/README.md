Este notebook tem como objetivo demonstrar como aplicar interpolação em dados de profundidade, permitindo a geração de novas amostras a partir de pontos já conhecidos. Inicialmente, é utilizada a trajetória de um poço direcional com 79 pontos conhecidos de profundidade medida (MD) e profundidade vertical verdadeira (TVD). A partir desses pontos, é criado um eixo contínuo de MD e aplicada interpolação linear utilizando o interp1d, da biblioteca SciPy, para gerar um perfil MD–TVD completo.



Na sequência, o interpolador é utilizado para estimar as profundidades verticais (TVD) de amostras de pressão que originalmente possuem apenas a profundidade medida (MD). O objetivo final é mostrar como a interpolação pode ser utilizada para integrar dados de diferentes fontes e referências de profundidade em aplicações reais de Óleo \& Gás.

