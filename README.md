# neural-network

## Idee

Eine Idee wäre es, die einzelnen Farbringe mittels RCNN / object detection zu erkennen und dann (mit einem zweiten neuronalen Netz) aus den Positionen und den Farben den Widerstandswert zu berechnen. 

Schritt 1 wäre jedenfalls, die Fläche mit den Ringen zu erkennen. 

→ Ein Problem bei der Farbringerkennung mit RCNN ist, dass über verdrehte Farbringe keine verdrehten Objekt-Bounding-Boxes gezogen werden, weil die immer so wie das Bild ausgerichtet sind.

→ Das [Projekt &bdquo;Fast and Robust Multiple ColorChecker Detectionusing Deep Convolutional Neural Networks&ldquo;](https://arxiv.org/pdf/1810.08639.pdf) macht etwas ganz Ähnliches und ihr neuronales Netz kann anscheinend auch verdrehte ColorChecker erkennen. 

## Recherche

- https://ieeexplore.ieee.org/document/5946088
- &bdquo;Fast and Robust Multiple ColorChecker Detection&ldquo; (Erkennen von 'ColorCherckern' zum Farbabgleich in der Fotografie)
  - [Paper](https://arxiv.org/pdf/1810.08639.pdf)
  - [Github-Repo](https://github.com/pedrodiamel/colorchecker-detection)
- https://www.researchgate.net/publication/252016436_An_efficient_color_detection_in_RGB_space_using_hierarchical_neural_network_structure (Farberkennung in RGB mit neuronalen Netzwerken)
- https://towardsdatascience.com/r-cnn-fast-r-cnn-faster-r-cnn-yolo-object-detection-algorithms-36d53571365e (RCNN)
- https://medium.com/towards-artificial-intelligence/how-r-cnn-works-on-object-detection-443679b0187c (RCNN / object detection)
- https://medium.com/datadriveninvestor/object-detection-with-convolutional-neural-networks-dde190eb7180 (CNN vs RCNN)
- https://cv-tricks.com/tensorflow-tutorial/training-convolutional-neural-network-for-image-classification/ (CNN / image classification)
- https://towardsdatascience.com/building-a-convolutional-neural-network-for-image-classification-with-tensorflow-f1f2f56bd83b (CNN)
- https://towardsdatascience.com/boost-your-cnn-image-classifier-performance-with-progressive-resizing-in-keras-a7d96da06e20 (CNN)