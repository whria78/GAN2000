# GAN2000
 
## /WHRIA/MODEL

Download Model Weights - https://doi.org/10.6084/m9.figshare.21507189

256x256 resolution; melanocyticnevus - network-snapshot-000800.pkl

512x512 resolution; melanocyticnevus - network-snapshot-000200.pkl


## /WHRIA/RESULT

256x256 resolution; melanocyticnevus

<pre><code>python gen_images.py --network=network-snapshot-000800.pkl --seeds=0-9999 --outdir=./WHRIA/RESULT/256
</code></pre>

512x512 resolution; melanocyticnevus

<pre><code>python gen_images.py --network=network-snapshot-000200.pkl --seeds=0-999 --outdir=./WHRIA/RESULT/512
</code></pre>

## /WHRIA/DATASET

malignant melanoma - 908 images
melanocytic nevus - 1098 images
all.csv - image source (url) & crop information

