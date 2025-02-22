# **Projet d'Extraction du Montant Total des Reçus**  

Ce projet a pour objectif de détecter et d'extraire automatiquement le montant total (TTC) à partir de documents de reçus en utilisant un modèle d'apprentissage profond. Il met en œuvre **LayoutLMv3**, un modèle basé sur les Transformers, spécialement conçu pour le traitement des documents scannés, et s’appuie sur **PyTorch** pour l'entraînement et l'inférence.

Deux ensembles de données ont été utilisés :
1. **ExpressExpense Receipt Dataset** : 200 images de reçus de restaurants.
2. **CORD Dataset** : Ensemble de reçus annotés pour les tâches d’OCR.

Le projet est structuré pour :  
✅ Analyser les caractéristiques des jeux de données.  
✅ Préparer et fine-tuner un modèle **LayoutLMv3**.  
✅ Utiliser des techniques d’OCR pour générer des annotations.  
✅ Évaluer et visualiser les performances du modèle.  


## **Technologies utilisées**  
🚀 **Machine Learning** : PyTorch, Transformers (Hugging Face)  
📄 **OCR** : Tesseract OCR  
🖼 **Traitement d’image** : PIL, OpenCV  
📊 **Visualisation** : Matplotlib  
