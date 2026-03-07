# 🌿 Plant Species Image Classification using Teachable Machine

## Project Overview

This project focuses on building an **image classification model** that can recognize **20 different plant species** using machine learning.

The model was developed using **Google Teachable Machine**, which allows users to train image classification models without advanced programming.

The goal of this project is to demonstrate how machine learning can be used to automatically identify plant species based on visual characteristics such as leaves, fruits, flowers, and plant structure.

Dataset size:

* **20 Plant Species**
* **250+ images per class**
* **5000+ images total**

---

# 🌱 Plant Species

Below are the plant species used in this project.

---

## 1. Papaya

**Common Name:** Papaya
**Scientific Name:** *Carica papaya*

Description:
Papaya is a tropical fruit-bearing plant widely grown in warm climates. It produces large green leaves and sweet orange fruit.

![Papaya](images/papaya.jpg)

---

## 2. Langka

**Common Name:** Jackfruit
**Scientific Name:** *Artocarpus heterophyllus*

Description:
Jackfruit is a large tropical fruit tree known for producing the biggest tree-borne fruit in the world.

![Langka](images/langka.jpg)

---

## 3. Rambutan

**Common Name:** Rambutan
**Scientific Name:** *Nephelium lappaceum*

Description:
Rambutan is a tropical fruit tree known for its hairy red fruit and sweet translucent flesh.

![Rambutan](images/rambutan.jpg)

---

## 4. Avocado

**Scientific Name:** *Persea americana*

Description:
Avocado trees produce nutrient-rich fruits widely used in food and cooking.

![Avocado](images/avocado.jpg)

---

## 5. Guava

**Scientific Name:** *Psidium guajava*

Description:
Guava is a tropical fruit tree known for its aromatic fruit and medicinal leaves.

![Guava](images/guava.jpg)

---

## 6. Cocoa

**Scientific Name:** *Theobroma cacao*

Description:
Cocoa trees produce cacao beans used to make chocolate.

![Cocoa](images/cocoa.jpg)

---

## 7. Eucalyptus

**Scientific Name:** *Eucalyptus globulus*

Description:
Eucalyptus is a fast-growing tree known for its aromatic leaves and medicinal oil.

![Eucalyptus](images/eucalyptus.jpg)

---

## 8. Baobab

**Scientific Name:** *Adansonia digitata*

Description:
Baobab trees are known for their massive trunks and ability to store large amounts of water.

![Baobab](images/baobab.jpg)

---

## 9. Cedar of Lebanon

**Scientific Name:** *Cedrus libani*

Description:
A large evergreen conifer tree historically valued for its durable wood.

![Cedar](images/cedar.jpg)

---

## 10. Monkey Pod Tree

**Scientific Name:** *Samanea saman*

Description:
A large shade tree commonly found in tropical regions.

![MonkeyPod](images/monkeypod.jpg)

---

## 11. Wollemi Pine

**Scientific Name:** *Wollemia nobilis*

Description:
A rare and ancient tree species discovered in Australia.

![Wollemi](images/wollemi.jpg)

---

## 12. Kapur Tree

**Scientific Name:** *Dryobalanops aromatica*

Description:
A tall tropical tree valued for its aromatic resin and timber.

![Kapur](images/kapur.jpg)

---

## 13. Kamias

**Scientific Name:** *Averrhoa bilimbi*

Description:
Kamias produces sour fruit commonly used in Filipino dishes.

![Kamias](images/kamias.jpg)

---

## 14. Duhat

**Scientific Name:** *Syzygium cumini*

Description:
Duhat trees produce dark purple fruits with a sweet and slightly sour flavor.

![Duhat](images/duhat.jpg)

---

## 15. Lanzones

**Scientific Name:** *Lansium parasiticum*

Description:
Lanzones is a tropical fruit tree known for its sweet translucent fruit.

![Lanzones](images/lanzones.jpg)

---

## 16. Aratiles

**Scientific Name:** *Muntingia calabura*

Description:
A small tropical tree that produces tiny sweet red fruits.

![Aratiles](images/aratiles.jpg)

---

## 17. Mangosteen

**Scientific Name:** *Garcinia mangostana*

Description:
Mangosteen is known as the "queen of fruits" because of its sweet and tangy flavor.

![Mangosteen](images/mangosteen.jpg)

---

## 18. Soursop

**Scientific Name:** *Annona muricata*

Description:
Soursop trees produce large green fruits with soft white pulp.

![Soursop](images/soursop.jpg)

---

## 19. Dragon Blood Tree

**Scientific Name:** *Dracaena cinnabari*

Description:
A unique tree known for its umbrella shape and red sap.

![DragonBlood](images/dragonblood.jpg)

---

## 20. Breadfruit

**Scientific Name:** *Artocarpus altilis*

Description:
Breadfruit is a tropical tree that produces starchy fruit used as food.

![Breadfruit](images/breadfruit.jpg)

---

# 🤖 Model Training Details

The model was trained using **Google Teachable Machine**.

Training Parameters:

* Epochs: 50
* Batch Size: 16
* Learning Rate: 0.001
* Images per class: 250+
* Total images: 5000+

### Training Settings Screenshot

![Training Settings](screenshots/training-settings.png)

---

# 📊 Model Evaluation

### Confusion Matrix

![Confusion Matrix](screenshots/confusion-matrix.png)

---

### Accuracy per Class

![Accuracy](screenshots/accuracy-per-class.png)

---

### Overall Model Accuracy

![Overall Accuracy](screenshots/overall-accuracy.png)

---

# 🧪 Model Testing (Preview)

Below are test predictions from the model.

### Test 1

![Test1](screenshots/test1.png)

### Test 2

![Test2](screenshots/test2.png)

### Test 3

![Test3](screenshots/test3.png)

### Test 4

![Test4](screenshots/test4.png)

### Test 5

![Test5](screenshots/test5.png)

### Test 6

![Test6](screenshots/test6.png)

### Test 7

![Test7](screenshots/test7.png)

### Test 8

![Test8](screenshots/test8.png)

### Test 9

![Test9](screenshots/test9.png)

### Test 10

![Test10](screenshots/test10.png)

---

# 📦 Exported Model

The trained model was exported from **Google Teachable Machine** in **TensorFlow.js format**.

Model files included in this repository:

* model/model.json
* model/metadata.json

These files contain the trained neural network used for plant classification.

---

# 📚 Reflection

### 1. How did the number of images affect accuracy?

Increasing the number of images per class helped the model learn more visual patterns and improved classification accuracy.

---

### 2. Which plants were misclassified?

Some species with similar leaf shapes were occasionally misclassified due to visual similarities.

---

### 3. How did epochs affect training?

Increasing the epochs allowed the model to learn better patterns but too many epochs could lead to overfitting.

---

### 4. Challenges during dataset collection

Collecting high-quality images without duplicates or watermarks was one of the biggest challenges.

---

### 5. Improvements

The model could be improved by collecting more images, adding different lighting conditions, and increasing dataset diversity.

---

# 📁 Repository Contents

```
Plant-Species-Image-Classification
│
├── model
│   ├── model.json
│   ├── metadata.json
│
├── screenshots
│
├── images
│
└── README.md
```
