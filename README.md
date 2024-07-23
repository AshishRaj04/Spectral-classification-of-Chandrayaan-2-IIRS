# Spectral-classification-of-Chandrayaan-2-IIRS
The repo contains the visualization and spectral classification of Chandrayaan 2 IIRS Data.

# Imaging Infrared Spectrometer
Chandrayaan-2's Imaging Infrared Spectrometer (IIRS) is an advanced instrument designed to map the lunar surface in the infrared spectrum. It was a part of India's second lunar exploration mission, Chandrayaan-2, which was launched by the Indian Space Research Organisation (ISRO) on July 22, 2019. The IIRS is specifically **intended to analyze the mineral composition of the moon's surface** and to map its thermal characteristics.
* **Mineralogical Mapping**: IIRS helps in creating detailed maps of the moon's mineral composition, which can provide insights into its formation and evolution.
* **Water Molecule Detection**: It assists in detecting and mapping hydroxyl and water molecules on the lunar surface, which is vital for future lunar exploration and potential resource utilization.

# Step wise procedures for apporaching the problem
1. ## Categorizing Based on Spacecraft Geometry

     Group or categorize the data based on similar observation parameters (e.g., angle of observation, altitude, phase angle). This ensures that the comparisons and classifications are made on data that are geometrically similar, reducing the noise and errors introduced by geometric differences.

2. ## Hyperspectral Data Analysis Knowledge
   * Download the specific IIRS data from the mentioned website.
   * Familiarize yourself with the dataset by plotting and understanding the data.
   * Each pixel in the data should be associated with its coordinates (latitude and longitude).

3. ## Visualize Data 
   * Create visualizations of the data stripes.
   * Implement functionality to display spectral variations (reflectance vs. wavelength) when a specific point is clicked.

4. ## Data Cleaning:

    * Address the noise in the dataset.
    * Select two or three data stripes and focus on the reflectance values, 
      discarding any irrelevant or noisy data.
      


5. ## Spectral Data Classification
     
     * Preprocess Data: Dimensionality reduction with PCA.
     * Cluster Data: Use K-means clustering. Experiment with different numbers 
       of clusters (e.g., 2, 3, 4, up to 12 clusters).
     * Classify Data: Apply CNN on the cleaned data for 
        spectral classification. Also use Random Forest classification , SVM .

6. ## Comparison and Validation
    
    * Compare the clusters obtained with the general understanding of the Moon’s geological diversity.
    * Validate your classification results with available scientific data and previous mission data.
 

7. ## User-Friendly Interface (GUI)
   * Develop userfriendly interface so that user can know the Mineralogical diversity of the moon.
