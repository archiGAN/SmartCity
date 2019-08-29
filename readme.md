AI will soon massively empower architects in their day-to-day practice. This potential is around the corner and my work provides a proof of concept. The framework used in my work offers a springboard for discussion, inviting architects to start engaging with AI, and data scientists to consider Architecture as a field of investigation. In this post, I summarize a part of my thesis, submitted at Harvard in May 2019, where Generative Adversarial Neural Networks (or GANs) get leveraged to design floor plans, and entire buildings.

I believe a statistical approach to design conception will shape AI’s potential for Architecture. This approach is less deterministic and more holistic in character. Rather than using machines to optimize a set of variables, relying on them to extract significant qualities and mimicking them all along the design process represents a paradigm shift.

Let’s unpack floor plan design into 3 distinct steps:

(I) building footprint massing
(II) program repartition
(III) furniture layout
Each step corresponds to a Pix2Pix GAN-model trained to perform one of the 3 tasks above. By nesting these models one after the other, I create an entire apartment building “generation stack” while allowing for user input at each step. Additionally, by tackling multi-apartment processing, this project scales beyond the simplicity of single-family houses.

Beyond the mere development of a generation pipeline, this attempt aims at demonstrating the potential of GANs for any design process, whereby nesting GAN models, and allowing user input between them, I try to achieve a back and forth between humans and machines, between disciplinarian intuition and technical innovation.
