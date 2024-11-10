## HUNTING EXOPLANETS IN SPACE 🛰️ 

### Author: Samriddhi Bisht
### Language: Python

### ⭐ Project Overview: Detection of Exoplanets using Kepler Telescope Data 

1. **Exoplanets**:
   - Exoplanets are planets located outside our solar system, orbiting stars other than the Sun.
   - The significance of the study of exoplanets is that it helps us understand the diversity of planetary systems in the universe and the potential for finding life beyond Earth. 
2. **Galactic Context**:
   - A star is defined as a celestial body that emits its own light.
   - The Universe comprises billions of galaxies, each containing millions of stars. Our solar system resides in the Milky Way galaxy, revolving around the star known as the Sun. The solar system consists of 8 planets orbiting the Sun, which has its own light.
   - Analogous Systems: Similar to our solar systems, other galaxies may host stars with orbiting planets and understanding the characteristics and behaviour of stars in other galaxies helps in the detection of exoplanets.

  <img src='https://student-datasets-bucket.s3.ap-south-1.amazonaws.com/whitehat-ds-datasets/kepler-exoplanets-dataset/kepler-space-telescope.jpg' width="600"> 
  
  *Image credits: http://kepler.nasa.gov/Mission/discoveries/discoverygraphics/*

  3. **Kepler Telescope**:
  - NASA deployed the Kepler Telescope to measure the brightness of stars in distant galaxies to detect exoplanets by observing variations in a star's brightness.
  - **Transit Method**: When an exoplanet transits in front of its star (from our perspective), the brightness recorded by Kepler decreases. Conversely, when the exoplanet moves behind the star, the brightness level increases.
  - Detection: This method identifies exoplanets by detecting periodic dips in the star's brightness, forming a wave-like pattern on a brightness-time graph.

  <img src = 'https://student-datasets-bucket.s3.ap-south-1.amazonaws.com/whitehat-ds-datasets/kepler-exoplanets-dataset/transit-method-gif.gif' width='600'> 
  
  *Image credits: https://imgur.com/r/SpaceGifs/43f17Ke*

  <img src = 'https://student-datasets-bucket.s3.ap-south-1.amazonaws.com/whitehat-ds-datasets/kepler-exoplanets-dataset/transit-method.jpg' width='600'> 
  
  *Image credits: http://kepler.nasa.gov/Mission/discoveries/discoverygraphics/*

  4. **Dip Characteristics**:
  - A larger planet causes a deeper dip in the brightness level, while a longer orbital period results in a broader dip width.
  
  5. **About the dataset**:
  - ROWS: All the 5087 rows denote the stars for which the flux values (brightness levels and dips) are recorded.
  - COLUMNS: Except for the first column, 'LABEL', the remaining columns store the flux values for the corresponding stars.The LABEL column has two classes: 1 implies the star doesn't have an exoplanet, and 2 implies the star has an exoplanet.
  
   
