# Processo seletivo - Visão Computacional - Pesquisador I
Prova prática parte do processo seletivo para a vaga de pesquisador I em visão computacional.

Para resolver o problema proposto utilizei a API para detecção de objetos do tensorflow2. Este texto descreve de forma breve os passos seguidos para completar a tarefa.
O problema consiste em fazer a detecção de cachos de uva em imagens. O conjunte de imagens rotuladas foi disponibilizado pela banca avaliadora.

Este repositório contém:
- *xml_to_csv.py* - para gerar arquivos csv para as imagens de treino e teste.
- *generate_tfrecord.py* - para criar arquivos tfrecord para as imagens de treino e teste.
- *generate_labelmap.py* - para criar o arquivo labelmap para o detector de objetos.
- *test_labels.csv* - arquivo csv gerado com as imagens de teste.
- *train_labels.csv* - arquivo csv gerado com as imagens treino.
- *labelmap.pbtxt* - arquivo labelmap gerado.
- *test.record* - arquivo tfrecord gerado (teste).
- *train.record* - arquivo tfrecord gerado (treino).
- *faster_rcnn_resnet152_v1_1024x1024_coco17_tpu-8.config* - arquivo config do modelo utilizado com os parâmetros setados para o problema proposto.
- *training_Tf2_Object_detection_model.ipynb* - notebook para treinar o modelo no google colab.
- *evaluating_Tf2_Object_detection_model.ipynb* - notebook para avaliar o modelo no goole colab.
- *object_detection_grape_inferene.ipynb* - notebook para fazer inferência em imagens de teste com o modelo treinado.

