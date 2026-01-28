# Fabric-Diffused LED Light Distribution Table (LDT)  

This repository provides a **Light Distribution Table (LDT)** file generated from experimental measurements of a fabric-diffused RGB LED strip intended for wearable Optical Camera Communication (OCC) systems. The LDT captures the angular radiation characteristics of the LED transmitter when covered by a cotton fabric diffuser, and can be used for optical simulations, ray tracing, and system-level performance evaluation.  

## Description

- **Purpose:**  
  The LDT file represents the experimentally measured angular emission of a textile-covered LED. It quantifies how the fabric diffuser redistributes the emitted optical power across angles, allowing researchers and engineers to model wearable LED transmitters in OCC systems.

- **Content:**  
  The file contains angular-resolved intensity values for the combined RGB channels of the LED. Each entry corresponds to a specific horizontal angle in the range, with intensity normalized to the maximum measured value.  

- **Format:**  
  - Standard LDT format compatible with lighting simulation and ray-tracing tools.  
  - Angles are specified in degrees relative to the LED surface normal.  
  - Intensities are provided in arbitrary units normalized to 1.  

- **Usage:**  
  1. Import the LDT file into optical simulation tools to define the radiation pattern of the wearable LED source.  
  2. Use it to simulate camera-based OCC links, estimate received optical power, or evaluate angular coverage.  
  3. Can be combined with garment CAD models to assess system performance in wearable scenarios.  

- **Notes:**  
  - Measurements were conducted under dark-room conditions with the LED strip positioned behind a stretched cotton fabric diffuser.  
  - The LDT file corresponds to the horizontal-plane angular distribution. Vertical-plane variation is assumed negligible due to the extended geometry of the LED strip.  
