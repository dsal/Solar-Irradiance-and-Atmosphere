# Solar-Irradiance-and-Atmosphere
Interpreting optical measurements requires a comprehensive understanding of weather and illumination conditions, as these factors significantly influence the spectral and temporal variations in surface reflectance. Weather conditions, such as cloud cover and atmospheric pressure, play a crucial role in determining interation of light with surfaces.

The direction of illumination significantly influences the broadband albedo, which represents the surface albedo over a specific wavelength range. This effect is primarily due to the anisotropic property. To accurately measure and analyze the broadband albedo under various illumination conditions, such as side-scattering, backward-scattering, and forward-scattering, the Solar Zenith Angle (SZA) and Solar Azimuth Angle are critical parameters. These angles are derived using a Python package developed by Samuel Bear Powell, which requires latitude, longitude, and time as input variables. The SZA exhibits a sinusoidal pattern, with its amplitude domain shifting upwards due to the Earth's axial rotation and axial tilt. An increase in SZA indicates that the sun is approaching the horizon, thereby providing optimal conditions for measuring surface broadband albedo under backward- and forward-scattering situations.

Solar radiation is critical for HSI analysis. Spectral and temporal variations in relative reflectance are directly influenced by weather conditions and the interaction of incoming solar irradiance with surfaces. For instance, absorption of radiance takes place by atmospheric oxygen molecules (Oxygen A band). It begins at approximately 760 nm and extends to around 770 nm that is clearly identifiable in HSI datasets due to the high spectral resolution of the instruments used. In the MOSAiC expedition of Arctic research, the albedo of the sea ice was measured by the radiation stations 2020R11 and 2020R14. These stations were equipped with radiometric sensors capable of capturing full-spectral-resolution data, which were subsequently interpolated to 1.0 nm across a broad wavelength range of 320-950 nm. The albedo measurements were further complemented by concurrent observations of incoming solar irradiance, enabling a comprehensive analysis of the energy balance at the sea ice surface.

Three highly sensitive hyperspectral radiometers were installed to measure the spectral irradiance, transmittance, and reflectance of sea ice. In the following figure, the left image, A, includes two sensors (an upward-looking sensor to measure decreasing irradiance and a downward-looking sensor to measure the reflected irradiance) and the right image, B, includes an under-ice sensor positioned approximately 0.5 meters below the ice that measures the transmitted irradiance.

![Sensors](https://github.com/user-attachments/assets/ed9a0970-1a24-467f-97c3-24c4ebe698a3)
Figure 1: The figure illustrates the setup of the above-ice (A) and below-ice sensors (B).


![Down](https://github.com/user-attachments/assets/e42a0d31-8762-452f-bff1-6d08ef0a9248)
Figure 2: Incident irradiance [320-950 nm] at 1 meter above sea ice (radiation station 2020R11 in June and July 2020).


![Reflected](https://github.com/user-attachments/assets/ea396892-f19e-4a36-a6c1-60264683f942)
Figure 3: Reflected irradiance [320-950 nm] from sea ice (radiation station 2020R11 in June and July 2020).
