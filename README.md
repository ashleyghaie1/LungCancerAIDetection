# LungCancerAIDetection

For this project, I used a deep learning model called ResNet101 to help detect lung cancer from medical images. I trained and tested the model on three different image datasets that include pictures of both cancerous and normal lung tissue.

The model did pretty well on the dataset it was trained on, reaching around 83% accuracy. But when I tested it on other datasets it hadn’t seen before, the accuracy dropped a lot. In most cases, the model would just predict everything as cancer, which shows it's not great at telling the difference between classes in new data yet.

Even though the model isn’t perfect, it has a lot of potential. If I improve it by:

- Using pretrained weights,

- Training for more than 1 epoch,

- Adding data balancing and augmentation,

then the accuracy and generalization should improve a lot. This project is a strong starting point for building AI tools that can help doctors detect cancer faster and more accurately in the future.

