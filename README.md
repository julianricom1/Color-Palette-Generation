# Color Palette Generation from Images

## Description

A color palette is a set of hues used together to create a harmonious, coherent, and visually appealing effect in visual representations (graphic design, film, photography, painting, etc.), as well as to convey specific messages and generate emotions according to the author's intent.

In a context of high demand for tools that can assist graphic designers, art directors, painters, and content creators in quickly and appropriately selecting the right colors for their works, an application for configuring color palettes from images would be highly beneficial.

The central problem lies in developing an automated method that can generate a coherent and aesthetically pleasing palette based on the colors identified in an image. This involves not only recognizing dominant hues but also understanding the relationships within the employed color range to create visually appealing and functional combinations. Addressing this problem would lead to several advantages:

- **Efficiency in the creative process:** by freeing up time that authors could spend on other strategic aspects of their projects.
- **Internal consistency in designs:** by maintaining a constant visual identity across different applications and projects.
- **Ease of use:** serving as a learning resource for individuals with less design experience, fostering creativity across various fields.
- **Optimization of quality:** and the impact of visual communication.

One way to achieve such a tool is to use unsupervised machine learning techniques on images to visualize the distribution of colors present in them and automatically generate color palette models. In this initial approach, the method will allow the identification of colors in an image to build a sample based on pixel similarity, which can be very useful for marketing, psychology, medicine, art, environment studies, among others. For example, colors could be extracted from different surfaces of the Earth in a satellite image to study the distribution of vegetation or pollution.

## Objective

Develop a method, based on clustering techniques, that allows the extraction of hues from an image and generates a sample of the colors present in it.

## Dataset

The data is associated with images of artworks. They can be downloaded from this link: https://www.kaggle.com/datasets/steubk/wikiart

## Activities Performed

1. **Image Collection from the Repository:** The idea is to select a diverse set of samples in different artistic styles.
2. **Preparation of Images for Model Training and Testing:** For this step, construct a pipeline that integrates the appropriate transformations.
3. **Development of the Clustering Model:** to identify the colors present in the images.
4. **Creation of a Model that Transforms the Identified Color Groups into a Representative Sample:** Additionally, the color distribution of the image should be shown in a two-dimensional space.

TODO: Translate Python code to English. (It was originally done in spanish)
