# Building change detection TinyCD

# Installation and Requirements
<pre>
<code>
!git clone https://github.com/Woojin0118/TinyCD.git
</code>
</pre>

# Dataset

You can find the original datasets at these two links:

LEVIR-CD: https://justchenhao.github.io/LEVIR/

WHU-CD: https://study.rsgis.whu.edu.cn/pages/download/building_dataset.html

Then, for each dataset, you have to organise the data in the following way:

A: images of t1 phase;

B: images of t2 phase;

label: label maps;

list: contains train.txt, val.txt and test.txt, each file records the image names (XXX.png) in the change detection dataset.

If you prefer, you can download the pre-processed dataset using the following:


LEVIR-CD

<pre>
<code>
wget https://www.dropbox.com/s/h9jl2ygznsaeg5d/LEVIR-CD-256.zip
</code>
</pre>

WHU-CD

<pre>
<code>
wget https://www.dropbox.com/s/r76a00jcxp5d3hl/WHU-CD-256.zip
</code>
</pre>

# References

https://github.com/AndreaCodegoni/Tiny_model_4_CD
