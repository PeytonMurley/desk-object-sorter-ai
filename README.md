# AI Desk Object Sorter

## Project Description
This project uses Google’s Teachable Machine to train an image classification model that can recognize three types of objects: pencils, pens, and markers/highlighters. 
The goal was to explore how machine learning models learn from image samples and how accuracy improves through iteration.

## Classes Identified
List the objects your model was trained to identify:
* Class 1 Pencils
* Class 2 Pens
* Class 3 Marker/Highlighter

## Discussion & Reflection
*(Please answer the following questions thoughtfully)*

1.  **Model Performance & Iteration:**
    My first trained model was moderately accurate, but I noticed misclassifications when objects had similar colors or were poorly lit.

    I improved the model by adding more images per class from different angles and lighting conditions.

    These changes increased the confidence scores and reduced confusion between pens and markers.

2.  **Challenges & Observations:**
    Easiest: Pencils — They have a very distinct shape and color, making them easy for the model to learn.

    Most challenging: Pens vs. markers — Some pens looked similar to markers in size and color, causing the model to occasionally mix them up.

    When I showed an object the model wasn’t trained on (like a screwdriver), the confidence scores were very low and spread out, showing uncertainty.

3.  **Bias in AI:**
    If all pencil images were the same yellow pencil, the model would struggle with pencils of other colors or shapes — this shows how bias can come from limited training data.

    If all training images are taken in bright lighting, the model may fail in dim environments.
    AI models depend heavily on diverse examples to prevent biased or inconsistent predictions.

4.  **Model Limitations & Usefulness:**
    The model may misclassify objects that have similar shapes or colors (e.g., a thick pen vs. a thin marker).

    Background clutter or shadows can reduce accuracy.

    Downloading the model files (model.json, weights.bin, metadata.json) is useful because they allow you to embed the classifier into a website or application and run the prediction in a browser.

5.  **Real-World Applications & Ethics:**
    Possible real-world uses:
       Sorting office supplies automatically
       Inventory tracking for classrooms
       Assisting visually impaired users by identifying objects through a camera

    Ethical consideration:
      Developers must ensure the model isn’t biased toward lighting, color, or specific object styles. A poorly trained model could mislead users if it confidently gives wrong identifications.

## (Optional) Challenges Faced / Interesting Discoveries
  I learned that even small changes in lighting made a big difference.

  Adding more diverse samples dramatically improved the model’s performance.

  I also discovered the model struggles the most when objects are overlapping or rotated in unusual ways.

## (Optional) Screenshot
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/b4a87752-1a6c-4aad-9d3c-4c0e1e790ef8" />

