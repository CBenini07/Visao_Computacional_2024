# Visao_Computacional_2024
Esse é um repositório utilizado para estudar a matéria de Visão Computacional, ministrada pelo professor Prof. César Henrique Comin - UFSCar.
O repositório original pode ser encontrado em https://github.com/chcomin/curso-visao-computacional-2024

O curso é dividio em módulos (M01, M02, ...). Cada módulo possui notebooks Jupyter numerados apresentando conceitos sobre Visão Computacional. Também são disponibilizadas [notas de aula](<Notas de Aula.pdf>) sobre os conceitos teóricos.

## Principais tópicos abordados

1. Visão geral sobre modelagem probabilística e cálculo diferencial;
2. Regressão linear e logística;
3. Diferenciação automática
4. Redes neurais convolucionais;
5. Estabilização e regularização de redes modernas;
6. Classificação de imagens naturais;
7. Segmentação de imagens naturais;
8. Autoencoders para remoção de ruído;
9. Mecanismos de atenção (transformers);
10. Busca de imagens por linguagem natural;
11. Geração de imagens artificiais
12. Detecção e casamento de pontos salientes

## Configuração do ambiente

`conda install -c pytorch -c nvidia -c conda-forge python pytorch torchvision torchaudio pytorch-cuda=12.1 matplotlib notebook numpy scipy transformers diffusers accelerate python-graphviz ipympl scikit-learn timm plotly`

As bibliotecas python-graphviz, ipympl, scikit-learn, timm e plotly são opcionais e serão usadas apenas uma única vez em exemplos específicos. Você pode usar os arquivos requirements.txt ou requirements.yml para criar o ambiente. Note que o pacote `-c nvidia pytorch-cuda=12.1` só deve ser instalado se o ambiente tiver acesso a uma GPU.
