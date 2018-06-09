# deep-emotion-recognition
Emotion Recognition using Transfer Learning and Ensembling on Static Face Images

SIU
Trained model weights can be found under checkpoints folders. Models files are splitted and compressed. They should be extracted before usage. Confusion matrices, training charts, training configuration and results are also provided.
- VGG16
- VGGFACE
- Inception
- ResNet50
- MLPStacked Experts (MLP 1024+512) : VGGFace + Expert-Sad + Expert-Fear

Thesis
Thesis module relies on models from siu module.
-VGGFace
-Simplified VGGFace
-Stacked Base Models : Simplified VGGFace + VGG16+ ResNet50
-Stacked Experts (MLP 1024+512) : Simplified VGGFace + Fear-Expert + Sad-Expert
