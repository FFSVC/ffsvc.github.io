---
layout: about
title: about-prime
permalink: /
# description: <a href="#">Affiliations</a>. Address. Contacts. Moto. Etc.

# profile:
#   align: right
#   image: prof_pic.jpg
#   address: >
#     <p>555 your office number</p>
#     <p>123 your address street</p>
#     <p>Your City, State 12345</p>

news: true  # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% responsive_image path: assets/img/logo_1.jpg title: "example image" class: "img-fluid rounded z-depth-1" %}
    </div>
</div>

<p> </p>
<p> Welcome to FFSVC 2022! The success of FFSVC2020 indicates that more and more researchers are paying attention to the far-field speaker verification task. In this year, the challenge still focuses on the far-field speaker verification task and provides a new far-field development and test set collected by real speakers in complex environments under multiple conditions, e.g., text-dependent, text-independent, cross-channel enroll/test, etc. In addition, in-domain training speech data may be unlabeled, which is difficult to fine-tune the pre-trained model. Therefore, a new focus of this year is cross-language self-supervised / semi-supervised learning, where participants are allowed to use the unlabeled train and dev set of the in-domain FFSVC2020 dataset (in Mandarin) and the labeled out-of-domain VoxCeleb 1&2 dataset (mostly in English) to build the model.</p>

<h3>Task Description</h3>
<p>This year we focus on the far-field <b>single-channel</b> scenarios. TThere are two tasks in this challenge; both tasks are to determine whether two speech samples are from the same speaker:</p>

<ul>
    <li> <a href="codalab task 1">Task 1. Fully supervised far-field speaker verification</a>. </li>
    <li> <a href="codalab task 2">Task 2. Semi-supervised far-field speaker verification</a>. </li>
</ul>


We define the task 1&2 as fixed training conditions that the participants can only use a fixed training set to build the speaker verification system. The fixed training set consists of the following two databases:
<ul>
    <li> <a href="https://www.robots.ox.ac.uk/~vgg/data/voxceleb/">VoxCeleb 1&2</a>.</li> 
    <li> <a href="http://2020.ffsvc.org/">FFSVC2020 dataset (Train and dev set)</a>.</li> 
</ul> 

<p><b>Note:</b> Please refer to this <a href="https://www.robots.ox.ac.uk/~vgg/data/voxceleb/">website</a> to download VoxCeleb 1&2 dataset and this <a href="dataset">website</a>to download FFSVC 2020 dataset  if you do not have these two datasets.<p>


<p>In task 1, participants can use both VoxCeleb1&2 and FFSVC20 datasets with speaker labels to train a far-field speaker verification system.</p>

<p>For task 2, in contrast to task1, <b>participants cannot use the speaker labels of the FFSVC2020 dataset</b>. In task 2, we encourage the participants to adopt self-supervised or semi-supervised methods to utilize the in-domain unlabeled data.<p>

<p>Using other speech datasets to train the system is forbidden, while participants are allowed to use public open-source non-speech dataset to perform data augmentation. The self-supervised pre-trained models, such as Wav2Vec and WavLM, cannot be used in this challenge.</p>

<h3>Schedule</h3>
<ul>
    <li>April 1<sup>st</sup>, 2022: Releasing the FFSVC 2022 evaluation plan and starting the registration.</li>
    <li>April 15<sup>th</sup>, 2022: Releasing the development and test set.</li>
    <li>May 1<sup>st</sup>, 2022: Opening the submission system on the Codalab platform.</li>
    <li>July 15<sup>th</sup>, 2022: Registration is closed.</li>
    <li>July 31<sup>th</sup>, 2022: Deadline for results submission.</li>
    <li>Aug 10<sup>th</sup>, 2022: Deadline for system description submission</li>
    <li>Sep 17<sup>th</sup>, 2022 (tentative): Interspeech 2022 Satellite Workshop</li>
</ul>


<h3>List of organisers</h3>
<p>Ming Li, Duke Kunshan University, China</p>
<p>Haizhou Li, National University of Singapore, Singapore</p>
<p>Shrikanth Narayanan, University of Southern California, USA</p>
<p>Hui Bu, AI Shell Foundation,China</p>
<p>Xiaoyi Qin, Duke Kunshan University, China</p>
<p>Yao Shi, Duke Kunshan University, China</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% responsive_image path: assets/img/DKU.png title: "DKU logo" class: "img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% responsive_image path: assets/img/USC.png title: "USC logo" class: "img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% responsive_image path: assets/img/NUS.png title: "NUS logo" class: "img-fluid rounded" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% responsive_image path: assets/img/AISHELL.png title: "AISHELL logo" class: "img-fluid rounded" %}
    </div>
</div>
