# TransHTC

### Abstract

Facial expression recognition (FER) plays a vital role in areas such as human-robot interaction, education and healthcare. Howerver, FER encounters several challenges, including occlusions, lighting conditions, low-resolution, and arbitrary orientations of faces. To tackle these challenges, we propose TransHTC, which exploits three key anatomical cues from facial images: (i) facial muscle coupling field, (ii) regional coding of muscle interactions, and (iii) textural changes resulting from muscle movements. In this paper, we formulate a novel FER method based on Transformer architecture that includes three specialized modules: Dual Channel Discriminant Feature Fusion (DDF), Cross Muscle Relation Mining (CRM), and Superficial Skin Texture Token Selection (STTS). The DDF scheme integrates CNN and Transformer to extract discriminative facial features, improving the relational learning capacity of model. The proposed CRM module explores the relationships between horizontal and vertical directions within facial patches, capturing the intricate dependencies between different facial regions. Finally, the STTS module selects skin texture tokens from facial coupling tokens, allowing the model to learn fine-grained texture features that are critical for accurate expression recognition. Experiments on the RAF-DB and KDEF datasets show the significant improvements of our proposed TransHTC framework over state-of-the-art FER methods.  

---
### The code of TransHTC will be avaliable soon
