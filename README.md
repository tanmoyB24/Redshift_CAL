# Redshift_CAL
# Determining Galaxy Redshift Using Spectral Line Fitting

## 🌌Overview
This project aims to determine the redshift (z) of a galaxy by analyzing its observed spectrum. By identifying spectral features (such as emission or absorption lines) and fitting a model to these features, we can compare their observed wavelengths to their known rest-frame wavelengths. This comparison allows us to calculate the redshift, which provides insights into the galaxy's velocity and distance due to the expansion of the universe.

## 📌 How It Works
1. **Load and Preprocess the Spectrum**  
   - Read observational spectral data.  

2. **Fit Spectral Features Using a Model**  
   - Apply **Gaussian fitting** to emission or absorption lines.  
   - Determine the precise peak positions of spectral features.  

3. **Calculate Redshift (\(z\))**  
   The redshift is computed using the formula:  
   \[
   z = \frac{\lambda_{\text{obs}} - \lambda_{\text{rest}}}{\lambda_{\text{rest}}}
   \]
   where:  
   - \( \lambda_{\text{obs}} \) = observed wavelength  
   - \( \lambda_{\text{rest}} \) = rest-frame wavelength  

