## 👩‍🔬 Leveraging Physics for Better Lithographic Controls 🔬

⭐️⭐️⭐️ Please star this repo if you find it helpful, interesting, or useful! ⭐️⭐️⭐️

I've just completed a project where I utilized multiple beam interference to accurately measure the thickness of spincoated resist. I implemented the Brendel-Borman model in Python to determine permittivity of substrate:

![alt text](https://raw.githubusercontent.com/JohnyCoder238/FTIR_analysis/main/img/Dielectric.jpeg)

by fitting said model to Reflectance and Transmittance captured via FTIR.

![alt text](https://raw.githubusercontent.com/JohnyCoder238/FTIR_analysis/main/img/fit_reflx_sub.jpeg)

I then confirmed the results and conclusions previously reached by my colleagues regarding the thickness of spincoated photoresist and its relation to spincoating speed. Although they employed the robust technique of ellipsometry, my research demonstrated that similar precision can be achieved with FTIR, validating the same resist thickness measurements. Importantly, this work confirmed that the relationship between spin coater speed and resist thickness is not linear.

![alt text](https://raw.githubusercontent.com/JohnyCoder238/FTIR_analysis/main/img/thin_film3%20(3).jpeg)

This methodology further refines grating fabrication precision. It was crucial for optimizing spin coater speed during the lithographic process of creating blazed gratings for the second part of my diploma thesis.
