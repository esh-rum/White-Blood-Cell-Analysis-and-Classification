# White-Blood-Cell-Analysis-and-Classification
## Introduction

Blood is a vital fluid responsible for transporting oxygen and nutrients to cells while removing carbon dioxide and waste products. It contains various types of cells suspended in plasma, each playing a crucial role in sustaining life:

* **Red Blood Cells (RBCs)** – Carry oxygen.
* **White Blood Cells (WBCs)** – Defend against infections and support immune response.
* **Platelets** – Help in blood clotting.

### Types of White Blood Cells (WBCs)

WBCs are classified based on the presence or absence of granules in their cytoplasm:

* **Granulocytes** (contain visible granules):

  * **Neutrophils**
  * **Eosinophils**
  * **Basophils**
* **Agranulocytes** (lack granules):

  * **Lymphocytes**
  * **Monocytes**

In this Problem-Based Learning (PBL) project, we focus on classifying the following WBCs:

* **Neutrophils**
* **Lymphocytes**
* **Monocytes**

Classification is based on features such as **nucleus shape**, **size**, and **cytoplasmic characteristics**.

---

## Dataset Structure

The dataset is divided into two main folders: `Train` and `Test`.

### Train Folder

Contains **five subfolders** with **100 images each**, all captured at **100x magnification**:

* `Neutrophil`
* `Monocyte`
* `Lymphocyte`
* `Eosinophil`
* `Basophil`

### Test Folder

Also contains the same **five subfolders** with **50 images each**.
Used for **model evaluation and performance testing**.

---

## Objective

Build a model to **classify Neutrophils, Lymphocytes, and Monocytes** based on image data, leveraging shape, size, and cytoplasm features.
