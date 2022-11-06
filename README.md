# GAN2000

![img](https://github.com/whria78/gan2000/blob/main/SAMPLES/256/seed0000.jpg?raw=true)
![img](https://github.com/whria78/gan2000/blob/main/SAMPLES/256/seed0001.jpg?raw=true)
![img](https://github.com/whria78/gan2000/blob/main/SAMPLES/256/seed0002.jpg?raw=true)
![img](https://github.com/whria78/gan2000/blob/main/SAMPLES/256/seed0003.jpg?raw=true)
![img](https://github.com/whria78/gan2000/blob/main/SAMPLES/256/seed0004.jpg?raw=true)
![img](https://github.com/whria78/gan2000/blob/main/SAMPLES/256/seed0005.jpg?raw=true)
![img](https://github.com/whria78/gan2000/blob/main/SAMPLES/256/seed0006.jpg?raw=true)
![img](https://github.com/whria78/gan2000/blob/main/SAMPLES/256/seed0007.jpg?raw=true)
![img](https://github.com/whria78/gan2000/blob/main/SAMPLES/256/seed0008.jpg?raw=true)
![img](https://github.com/whria78/gan2000/blob/main/SAMPLES/256/seed0009.jpg?raw=true)

 
## Model Weights

Download - https://doi.org/10.6084/m9.figshare.21507189

256x256 resolution; melanocyticnevus - network-snapshot-000800.pkl

512x512 resolution; melanocyticnevus - network-snapshot-000200.pkl


## Result Images

Download - https://doi.org/10.6084/m9.figshare.21507189

256x256 resolution; melanocyticnevus

<pre><code>python gen_images.py --network=network-snapshot-000800.pkl --seeds=0-9999 --outdir=./WHRIA/RESULT/256
</code></pre>

512x512 resolution; melanocyticnevus

<pre><code>python gen_images.py --network=network-snapshot-000200.pkl --seeds=0-999 --outdir=./WHRIA/RESULT/512
</code></pre>

## /DATASET

malignant melanoma - 908 images

melanocytic nevus - 1098 images


all.csv - image source (url) & crop information

<pre><code>python download.py all.csv
</code></pre>
