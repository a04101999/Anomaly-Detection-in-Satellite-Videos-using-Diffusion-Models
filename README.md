# Anomaly-Detection-in-Satellite-Videos-using-Diffusion-Models


Timely identification of extreme events such as
wildfires, cyclones, or floods using satellite data is paramount
for effective disaster management. While various earth-observing
satellites furnish data on disasters, those in geostationary orbit
offer information at intervals as frequent as every minute,
essentially crafting a space-based video feed. Our central focus
is the detection of anomalies, specifically wildfires and smoke, in
these satellite videos. In contrast to prior endeavors in anomaly
detection within surveillance videos, this study introduces
a system tailored for high-frequency satellite videos, placing
particular emphasis on two anomalies. Unlike the majority of
existing CNN-based methods for wildfire detection that rely on
labeled images or videos, our unsupervised approach addresses
the challenges posed by high-frequency satellite videos with a high
intensity of clouds. These CNN-based methods can only identify
fires once they have reached a certain size and are susceptible
to false positives. We frame the challenge of wildfire detection
as a general anomaly detection problem. Introducing an inno-
vative unsupervised approach involving diffusion models, which
are state-of-the-art generative models for anomaly detection in
satellite videos, we adopt a ”generating-to-detecting” strategy.
The diffusion model is trained to generate normal videos without
anomalies, and when tested on abnormal videos containing
anomalies like fire or smoke, it encounters difficulty generat-
ing corresponding frames. Performance evaluation, measured
through AUC-ROC, underscores the superior efficacy of the
diffusion model over CNN and GAN-based methods in detecting
anomalies in these high-frequency satellite videos characterized
by a high intensity of clouds.


# Dataset 
The dataset utilized in our paper can be accessed through the link below. It comprises extracted normal clips from day scenes, and we have generated 500 normal clips, each containing 14 frames, using the provided clips.

https://drive.google.com/drive/folders/14q9irXkDozr-HMUtRj2NZVQOl2Q9sdNT?usp=share_link

We also offer the extracted clips specifically captured during night scenes with low light conditions.

https://drive.google.com/drive/folders/1-WsjM-1OCY_kxBT5Ehv-3ljTer2BhSta?usp=share_link



