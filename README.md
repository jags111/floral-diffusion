# floral-diffusion
Floral Diffusion is a custom diffusion model trained by jags using a DD 5.6 version


Floral Diffusion V1 Floral diffusion is a trained model set of 10 K floral sets of 512 kb size images that have been trained on 256 x 256 diffusion model.


<p align=center>
<a href="https://github.com/jags111/floral-diffusion/blob/main/Floral_Diffusion_V1_DD_v5_6.ipynb"><img src="https://img.shields.io/badge/Open-in%20Colab-brightgreen?logo=google-colab&style=flat-square" alt="Open in Google Colab"/></a>
<br>
<img src = "https://github.com/jags111/floral-diffusion/blob/main/images/collage001.jpg" width = "50%">
</p>

<sub><sup><a id="example-application">[*]</a> 
Disco Diffusion is a Google Colab Notebook that leverages CLIP-Guided Diffusion to allow one to create compelling and beautiful images from text prompts.
</sup></sub>

🩸 **Available to all**: fully optimized for Google Colab

## Get Started

<a href="https://github.com/jags111/floral-diffusion/blob/main/Floral_Diffusion_V1_DD_v5_6.ipynb"><img src="https://img.shields.io/badge/Open-in%20Colab-brightgreen?logo=google-colab&style=flat-square" alt="Open in Google Colab"/></a>

Note, GPU is required.

display_rate: 
this is so you can see the progress on your image. By default it’s set to 20, which means you’ll see the image progress every 20 steps.

You can just leave it to 20 or set it to something less if you’d like. 
If you’ve got a Tesla T4 GPU and default other settings, with 20 you’ll probably see the image progressing every 1-2 minutes.

n_batches: 
These are the number of images you want Disco Diffusion to create. If you leave 50, it will continue generating variations of your prompt.

As you can see I’ve changed it to 1, so it generates one image and it stops, so you can change the prompt and run it again, and so on. 
I recommend you change it to 1 for your first run.

### Create artworks
We won’t tweak the available settings for this run – you can learn about the various settings from links. 
This way you can see how to run it, and see what it does, as fast as possible. 
That should break the ice in case you’re intimidated at first.

You can also generate videos with Disco Diffusion. 

### Visualize results
They’re located in your Google Drive. 
When you connected Google Drive earlier, the Disco Diffusion Colab notebook set up some folders in your Drive.
You should a folder called AI in your Drive. In it you have everything Disco Diffusion set up.

Our images, in our case, are located in AI > Disco_Diffusion > images_out > Floral_xxxx. 

Floral_xxx is the batch_name that we didn’t configure. You can change that later, as it helps with categorizing experiments.

## What's next?
The community is still growing and experimenting with machine learning generated images.

💡 **If you are already a DD user**: you are ready to go! There is no extra learning,Floral Diffusion respects the same parameter semantics as DD5.6. So just unleash your creativity!

Tools and Resources for AI Art – Constantly updated, extremely useful and fun list of tools and resources to create AI art. 
Maintained by @pharmapsychotic, they regularly test AI art tools, post amazing results on Twitter and update the list with a link to the tool and a short description. 
Highly recommend it!

<!-- start support-pitch -->
## Support
If you create a fun image with this model, please show your result and message us on twitter at @jags111 or @NeuralismAI .

You can join the <a href="https://discord.gg/vNVqT82W" alt="Neuralism Discord"> NEURALISM AI DISCORD </a> or <a href="https://discord.gg/UmSd4qyh" alt =Jags AI Discord > JAGS AI DISCORD </a> 
Share your work created with this model. Exchange experiences and parameters. And see more interesting custom models.

Support us in Patreon for more future models and new versions of AI notebooks.
- tip me on <a href="https://www.patreon.com/jags111"> [patreon]</a> 

Thank you for being awesome!

<!-- end support-pitch -->
