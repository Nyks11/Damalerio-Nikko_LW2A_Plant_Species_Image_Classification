# Damalerio-Nikko_LW2A_Plant_Species_Image_Classification

## A. Project Overview

### ● Brief Description of the Project

This project involves building an image classification model using a collection of unique tree and plant species. All images were gathered manually and organized into folders to create a clean dataset. The model is trained using Teachable Machine to identify and distinguish between the different plant types.  

The main goal is to explore how machine learning models interpret visual data, how they learn to differentiate species, and how dataset quality impacts classification performance.

### ● Purpose of the Image Classification Model

The purpose of this model is:

- To accurately classify a variety of tree and plant species from images  
- To study how AI recognizes visual features and patterns  
- To gain hands-on experience in preparing datasets, training models, and evaluating predictions using Teachable Machine

## B. Plant Species Overview

Below are the 20 plant species used in this image classification project. Each species includes one representative image and a short description.

---

### 1. Kauri Tree

![Kauri Tree](plant_images/Kauri_Tree_Agathis_australis_ch/00011_co_d7ba21f19d2a.jpg)

- Common Name: Kauri Tree  
- Scientific Name: *Agathis australis*  
- Description: Kauri trees are massive, long-living conifers native to New Zealand. They are known for their straight trunks, thick bark, and highly durable wood.  

---

### 2. Japanese Yew

![Japanese Yew](plant_images/Japanese_Yew_Taxus_cuspidata_ch/00054_britannica_329cbd3901dc.jpg)

- Common Name: Japanese Yew  
- Scientific Name: *Taxus cuspidata*  
- Description: The Japanese Yew is an evergreen conifer native to Japan, prized for its dense foliage and used in ornamental landscaping and bonsai cultivation.  

---

### 3. Hainan Yellowwood

![Hainan Yellowwood](plant_images/Hainan_Yellowwood_Dalbergia_odorifera_ch/00004_fpcn_2ab6c6beed64.jpg)

- Common Name: Hainan Yellowwood  
- Scientific Name: *Dalbergia odorifera*  
- Description: A tropical tree known for its fragrant wood and durable timber, native to Hainan Island in China.  

---

### 4. Ghost Gum

![Ghost Gum](plant_images/Ghost_Gum_Corymbia_aparrerinja_ch/00011_amazonaws_3aff4110e92c.jpg)

- Common Name: Ghost Gum  
- Scientific Name: *Corymbia aparrerinja*  
- Description: Native to central Australia, Ghost Gum is a smooth-barked tree with white trunks and delicate green leaves, often seen in arid regions.  

---

### 5. Western Silvery Oak

![Western Silvery Oak](plant_images/Western_Silvery_Oak_Grevillea_robusta_ch/00002_etsystatic_9b7d38bd8342.jpg)

- Common Name: Western Silvery Oak  
- Scientific Name: *Grevillea robusta*  
- Description: Also called the Silk Oak, this fast-growing tree from Australia is known for its feathery leaves and bright orange flowers.  

---

### 6. Sumatran Rafflesia

![Sumatran Rafflesia](plant_images/Sumatran_Rafflesia_Rafflesia_arnoldii_ch/00006_muffingraphi_6084ee569ce8.jpg)

- Common Name: Sumatran Rafflesia  
- Scientific Name: *Rafflesia arnoldii*  
- Description: Known for producing the largest flowers in the world, this parasitic plant from Sumatra has a distinctive odor and unique red-orange blooms.  

---

### 7. Sierra Magnolia

![Sierra Magnolia](plant_images/Sierra_Magnolia_Magnolia_campbellii_ch/00003_treesandshru_12b992d8423d.jpg)

- Common Name: Sierra Magnolia  
- Scientific Name: *Magnolia campbellii*  
- Description: A striking magnolia species from the Himalayas, notable for its large, pink to red flowers that bloom early in spring.  

---

### 8. Borneo Camphor Tree

![Borneo Camphor Tree](plant_images/Borneo_Camphor_Tree_Dryobalanops_aromatica_ch/00010_ufl_0ae8533ba0d5.jpg)

- Common Name: Borneo Camphor Tree  
- Scientific Name: *Dryobalanops aromatica*  
- Description: This tall tropical tree from Borneo produces fragrant camphor and is valued for its hard, durable timber.  

---

### 9. Cork Oak

![Cork Oak](plant_images/Cork_Oak_Quercus_suber_ch/00020_stockfood_79f01fd05c3a.jpg)

- Common Name: Cork Oak  
- Scientific Name: *Quercus suber*  
- Description: Native to southwestern Europe and North Africa, the Cork Oak is known for its thick, cork-producing bark and evergreen leaves.  

---

### 10. Himalayan Cedar

![Himalayan Cedar](plant_images/Himalayan_Cedar_Cedrus_deodara_ch/00003_bigcommerce_4e7f2c4d37df.jpg)

- Common Name: Himalayan Cedar  
- Scientific Name: *Cedrus deodara*  
- Description: An evergreen conifer native to the western Himalayas, valued for its aromatic wood and ornamental uses.  

---

### 11. Dove Tree

![Dove Tree](plant_images/Dove_Tree_Davidia_involucrata_ch/00005_gardenia_9ac25be44af4.jpg)

- Common Name: Dove Tree  
- Scientific Name: *Davidia involucrata*  
- Description: Known for its distinctive white bracts resembling doves, this deciduous tree is native to China and widely planted as an ornamental species.  

---

### 12. Macadamia Nut Tree

![Macadamia Nut Tree](plant_images/Macadamia_Nut_Tree_Macadamia_integrifolia_ch/00005_gardenia_6af0669a1edd.jpg)

- Common Name: Macadamia Nut Tree  
- Scientific Name: *Macadamia integrifolia*  
- Description: Native to Australia, this evergreen tree produces edible nuts and has glossy green foliage.  

---

### 13. Florida Torreya

![Florida Torreya](plant_images/Florida_Torreya_Torreya_taxifolia_ch/00001_torreyaguard_9f04ac733b31.jpg)

- Common Name: Florida Torreya  
- Scientific Name: *Torreya taxifolia*  
- Description: A critically endangered conifer native to Florida, known for its slender, pyramidal shape and dark green needles.  

---

### 14. Tamarind Tree

![Tamarind Tree](plant_images/Tamarind_Tree_Tamarindus_indica_ch/00002_quintadosour_449541f94d92.jpg)

- Common Name: Tamarind Tree  
- Scientific Name: *Tamarindus indica*  
- Description: A tropical tree producing edible, tangy-sweet pods; widely cultivated in Asia, Africa, and the Americas.  

---

### 15. Palo Verde

![Palo Verde](plant_images/Palo_Verde_Parkinsonia_florida_ch/00001_gardenia_fc821d3047d5.jpg)

- Common Name: Palo Verde  
- Scientific Name: *Parkinsonia florida*  
- Description: Known as the "green stick" tree, this desert species from North America has green bark and yellow flowers.  

---

### 16. Giant Sequoia

![Giant Sequoia](plant_images/Giant_Sequoia_Sequoiadendron_giganteum_ch/00002_redd_3d04eb866e1b.jpg)

- Common Name: Giant Sequoia  
- Scientific Name: *Sequoiadendron giganteum*  
- Description: One of the largest tree species on Earth, native to California, with massive trunks and reddish-brown bark.  

---

### 17. Norfolk Island Pine

![Norfolk Island Pine](plant_images/Norfolk_Island_Pine_Araucaria_heterophylla_ch/00005_com_78ed383d8c4e.jpg)

- Common Name: Norfolk Island Pine  
- Scientific Name: *Araucaria heterophylla*  
- Description: A tall, evergreen conifer native to Norfolk Island, characterized by its straight trunk, dense pyramidal shape, and horizontal branching pattern. Often cultivated as an ornamental houseplant.  

---

### 18. Dwarf Cypress

![Dwarf Cypress](plant_images/Dwarf_Cypress_Chamaecyparis_obtusa_Nana_ch/00041_com_1a48fdb9598a.jpg)

- Common Name: Dwarf Cypress  
- Scientific Name: *Chamaecyparis obtusa ‘Nana’*  
- Description: A slow-growing, compact conifer used in bonsai and landscaping; has dense, dark green foliage.  

---

### 19. Living Stone Tree

![Living Stone Tree](plant_images/Living_Stone_Tree_Euphorbia_tirucalli_ch/00002_bigcommerce_4c006c66f791.jpg)

- Common Name: Living Stone Tree  
- Scientific Name: *Euphorbia tirucalli*  
- Description: A succulent tree with cylindrical, stick-like branches, commonly called Pencil Cactus or Milk Bush; adapted to arid environments.  

---

### 20. Bottlebrush Tree

![Bottlebrush Tree](plant_images/Bottlebrush_Tree_Callistemon_citrinus_ch/00003_moonvalleynu_ff22b3af7db1.jpg)

- Common Name: Bottlebrush Tree  
- Scientific Name: *Callistemon*  
- Description: Known for its bright red, brush-like flowers, this tree is native to Australia and commonly used in ornamental landscaping.

---

## C. Model Training Details

### ● Epochs
150

### ● Batch Size
160

### ● Learning Rate
0.001

### ● Number of Images Per Class
250-300 (unbalanced distribution across classes)

![Model Training Details](model_training_details/model_training.png)  

---

## D. Model Evaluation

---

### 1. Confusion Matrix

![Confusion Matrix](model_evaluation/confusion_matrix.png)

---

### 2. Accuracy per Class

![Accuracy per Class](model_evaluation/accuracy_per_class.png)

---

### 3. Overall Model Accuracy

![Overall Accuracy](model_evaluation/accuracy_and_loss_epoch.png)

---

## E. Model Testing

### Test 1
![Test 1](test_images/test01.png)

### Test 2
![Test 2](test_images/test02.png)

### Test 3
![Test 3](test_images/test03.png)

### Test 4
![Test 4](test_images/test04.png)

### Test 5
![Test 5](test_images/test05.png)

### Test 6
![Test 6](test_images/test06.png)

### Test 7
![Test 7](test_images/test07.png)

### Test 8
![Test 8](test_images/test08.png)

### Test 9
![Test 9](test_images/test09.png)

### Test 10
![Test 10](test_images/test10.png)

---

## Reflection Questions

### 1. How did the number of images per class affect your model's accuracy?

Answer: The classes with more examples were usually recognized more confidently, while classes with fewer or more varied samples had weaker consistency. Since my dataset is not perfectly balanced, some categories likely became easier for the model to memorize. This showed me that class balance is just as important as total dataset size.

---

### 2. Which plant species were most commonly misclassified and why?

Answer: Misclassification happened more often between species with close visual traits, especially plants with similar leaf textures, branch structure, or green-dominant color tones. In some test images, background clutter also distracted the model from the plant itself. This suggests the model may rely on broad shape and color cues before finer botanical details.

---

### 3. How did changing the epochs, batch size, or learning rate affect the training results?

Answer:
- Epochs: More epochs improved training metrics at first, but after a point the gains became small, which can be a sign that the model is nearing overfitting.
- Batch size: A larger batch size made training smoother and faster per step, but it can reduce the model's ability to generalize if too large.
- Learning rate: Keeping 0.001 gave stable convergence; when tuning around this value, I noticed that too high became unstable while too low slowed progress significantly.

These adjustments helped me understand that better accuracy comes from balanced tuning, not from maximizing a single parameter.

---

### 4. What challenges did you encounter during dataset collection and labeling?

Answer:
- Gathering enough clean images per species took the most time.
- Some classes had inconsistent framing, distance, and lighting, which increased variation.
- Similar-looking species made manual labeling more error-prone.

Because of these issues, I learned that careful folder organization and repeated label checking are essential before training.

---

### 5. If you were to improve your model, what specific changes would you make and why?

Answer:
- Rebalance the dataset so each class has a similar image count.
- Add stronger preprocessing and augmentation (crop consistency, brightness normalization, rotation, and slight zoom).
- Collect more hard examples for confusing class pairs.
- Run multiple training trials with different epoch and batch-size combinations, then compare validation behavior.
- Test a transfer-learning workflow to improve feature extraction for visually similar species.

These changes would likely improve both class-level precision and overall robustness on unseen images.

---

## Submission Checklist

- [x] **20 related plant species proposed**  
	See [Section B: Plant Species Overview](#b-plant-species-overview) for details.

- [x] **Minimum 250 images per species**  
	Images are stored in the [plant_images/](plant_images/) folder.

- [x] **Model trained using Teachable Machine**  
	Training details are in [Section C: Model Training Details](#c-model-training-details).

- [x] **Under-the-hood evaluation screenshots**  
	Confusion matrix, per-class accuracy, and overall accuracy are in [Section D: Model Evaluation](#d-model-evaluation).

- [x] **10 preview testing screenshots**  
	See [Section E: Model Testing](#e-model-testing) for all screenshots.

- [x] **Model exported and saved**  
	Exported model files are in the [models/](models/) folder.

- [x] **GitHub repository with complete README.md**  
	You are currently viewing it here.

- [x] **All files and screenshots uploaded and documented**  
	Check [plant_images/](plant_images/), [models/](models/), [model_training_details/](model_training_details/), [model_evaluation/](model_evaluation/), and [test_images/](test_images/) folders for completeness.
