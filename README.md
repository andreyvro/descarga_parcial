# Modelos para detecção de descargas parciais em redes elétricas
## Deteção de anomialias

### Definição do problema  

Linhas de tensão percorrem centenas de quilômetros para fornecer energia às cidades. Essas 
grandes distâncias tornam o trabalho de inspecionar manualmente as linhas em busca de 
danos uma tarefa complexa e cara. Esses danos levam a um fenômeno conhecido como 
descarga parcial - descargas parciais são descargas elétricas que ocorrem em defeitos no 
isolamento de cabos, também podem ocorrer nas suas interfaces (isolante e semicondutora), 
ou em emendas e terminais. Entre suas causas estão o envelhecimento dos componentes, 
contaminação do material isolante, falha de instalação, entre outras.  As descargas parciais 
danificam gradativamente as linhas de tensão, portanto, se não forem reparadas, podem levar 
a uma queda de energia, danificar equipamentos ou provocar desastres ambientais. 

Esse repositório apresenta testes de modelagem preditiva para identificar 
padrões nos sinais de linhas elétricas e com isso, detectar a ocorrência ou não de descargas 
parciais.

### Descrição dos dados 
A base de dados está disponível em https://drive.google.com/file/d/17LPP_ZZprHIG3R2f0Vhg5CyfFZOMvlia/view?usp=sharing. Nela está contida 501 medições de sinais, cada sinal contendo 800.000 medições da tensão de uma linha de energia (representado pelas colunas). A própria rede opera em um esquema de energia trifásico (0,1,2) e todas as três fases são medidas simultaneamente. As últimas 3 colunas da base de dados representam respectivamente o ID do sinal, fase, e o target representando ausência (0) ou presença de descarga parcial (1).
