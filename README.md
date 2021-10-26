Description
-----------
This repository contains video datasets that can be used for training coarse to fine-grained (phase, step and action) temporal classification tasks.

Thank you to my colleague Luis C. Garcia-Peraza-Herrera for initiating the content and repo structure.

Surgical video datasets
-------------------

<table align="center">
  
  <tr>
    <td align="center">Dataset</td> <td align="center">Task</td> <td align="center">Annotations</td> <td align="center">Procedures</td> <td align="center">Paper</td>
  </tr>
  
  <!-- CholecT50 -->
  <tr>
    <td align="center">
      <a href="https://cholectriplet2021.grand-challenge.org/">CholecT50</a>
    </td>
    <td align="center">
      Every frame is annotated with labels from the triplet: instrument, verb and target for the recognition of instrument-tissue interaction in laparoscopic cholecystectomies. This novel challenge investigates the state-of-the-art on surgical fine-grained activity recognition.
    </td>
    <td align="center">action, tools, tissue</td>
    <td align="center">50</td>
    <td align="center">
      N/A
    </td>
  </tr>
  
  <!-- Hei-Chole -->
  <tr>
    <td align="center">
      <a href="https://www.synapse.org/#!Synapse:syn18824884/files/">Hei-Chole</a>
    </td>
    <td align="center">
      A dataset with 33 laparoscopic cholecystectomy videos from three surgical centers with a total operation time of 22 hours was created. Labels included annotation of seven surgical phases with 250 phase transitions, 5514 occurences of four surgical actions, 6980 occurences of 21 surgical instruments from seven instrument categories and 495 skill classifications in five skill dimensions. The dataset was used in the 2019 Endoscopic Vision challenge, sub-challenge for surgical workflow and skill analysis.
    </td>
    <td align="center">phase, action, tools, skills</td>
    <td align="center">24 (33 test not released)</td>
    <td align="center">
      <a href="https://arxiv.org/abs/2109.14956">Lena Maier-Hein et al. 2021</a>
    </td>
  </tr>
  
  <!-- DAISI -->
  <tr>
    <td align="center">
      <a href="https://arxiv.org/abs/2004.02809">DAISI</a>
    </td>
    <td align="center">
      DAISI leverages on images and instructions to provide step-by-step demonstrations of how to perform procedures from various medical disciplines. The dataset was acquired from real surgical procedures and data from academic textbooks.
    </td>
    <td align="center">captions</td>
    <td align="center">13k images</td>
    <td align="center">
      <a href="https://arxiv.org/abs/2004.02809">Edgar Rojas-Munoz et al. 2020</a>
    </td>
  </tr>
  
  <!-- Cholec80 -->
  <tr>
    <td align="center">
      <a href="http://camma.u-strasbg.fr/datasets">Cholec80</a>
    </td>
    <td align="center">
      80 videos of cholecystectomy surgeries performed by 13 surgeons. The videos are captured at 25 fps. The dataset is labeled with the phase (at 25 fps) and tool presence annotations (at 1 fps). A tool is defind as present in an image if at least half of the tool tip is visible.
    </td>
    <td align="center">phases, tools</td>
    <td align="center">80</td>
    <td align="center">
      <a href="https://arxiv.org/abs/1602.03012">Twinanda et al. 2016</a>
    </td>
  </tr>
  
  <!-- CATARACTS -->
  <tr>
    <td align="center">
      <a href="https://ieee-dataport.org/open-access/cataracts">CATARACTS</a>
    </td>
    <td align="center">
      This dataset consists of 50 cataract surgery. It was annotated for two main tasks: surgical tool presence detection and surgical activity recognition. It was divided into two sets (train, test) for the surgical tool presence detection task and 3 sets (train, dev, test) for the activity recognition task.
    </td>
    <td align="center">phases, steps</td>
    <td align="center">101</td>
    <td align="center">
      <a href="">N/A</a>
    </td>
  </tr>
  
  <!-- PETRAW -->
  <tr>
    <td align="center">
      <a href="https://www.synapse.org/#!Synapse:syn25147789/wiki/608848">PETRAW</a>
    </td>
    <td align="center">
      Recognize all levels of granularity of the surgical workflow (phases, steps, and action verb) with different modalities configurations.
    </td>
    <td align="center">phases, steps, actions</td>
    <td align="center">100</td>
    <td align="center">
      <a href="">N/A</a>
    </td>
  </tr>
  
  <!-- MISAW -->
  <tr>
    <td align="center">
      <a href="https://www.synapse.org/#!Synapse:syn21776936/wiki/601700">MISAW</a>
    </td>
    <td align="center">
      The “MIcro-Surgical Anastomose Workflow recognition on training sessions” (MISAW) sub-challenge as a part of the MICCAI 2020. Multi-Granularity recognition: One model to recognize phases, steps and activities. Information: stereoscopic video, kinematic data, workflow annotation at 3 levels of granularity (phases, steps, and activities).
    </td>
    <td align="center">phases, steps, activities, actions</td>
    <td align="center">27</td>
    <td align="center">
      <a href="https://arxiv.org/abs/2103.13111">Huaulmé et al. MICCAI 2021</a>
    </td>
  </tr>
  
</table>

Private datasets
--------------------------------------
* ByPass40 - Strasbourg University
* MitiSW - MITI group at the Klinikum rechts der Isar in Munich


Non-medical video datasets
-------------------

<table align="center">
  
  <tr>
    <td align="center">Dataset</td> <td align="center">Task</td> <td align="center">Annotations</td> <td align="center">Procedures</td> <td align="center">Paper</td>
  </tr>
  
  <!-- Kinetics -->
  <tr>
    <td align="center">
      <a href="https://computervisiononline.com/dataset/1105138631">Kinetics</a>
    </td>
    <td align="center">
      A collection of large-scale, high-quality datasets of URL links of up to 650,000 video clips that cover 400/600/700 human action classes, depending on the dataset version. Each clip is human annotated with a single action class and lasts around 10 seconds.
    </td>
    <td align="center">action</td>
    <td align="center">700/400</td>
    <td align="center">
      <a href="https://arxiv.org/abs/2010.10864">Lucas Smaira (DeepMind) 2020</a>
    </td>
  </tr>
  
  <!-- Breakfast -->
  <tr>
    <td align="center">
      <a href="https://serre-lab.clps.brown.edu/resource/breakfast-actions-dataset/">Breakfast</a>
    </td>
    <td align="center">
      The Breakfast Actions Dataset comprises of 10 actions related to breakfast preparation, performed by 52 different individuals in 18 different kitchens.
    </td>
    <td align="center">action</td>
    <td align="center">77 hours</td>
    <td align="center">
      <a href="">H. Kuehne CVPR 2014</a>
    </td>
  </tr>
  
  <!-- 50 Salads -->
  <tr>
    <td align="center">
      <a href="https://computervisiononline.com/dataset/1105138631">50 Salads</a>
    </td>
    <td align="center">
      Activity recognition research has shifted focus from distinguishing full-body motion patterns to recognizing complex interactions of multiple entities.
    </td>
    <td align="center">action, step</td>
    <td align="center">50</td>
    <td align="center">
      N/A
    </td>
  </tr>
  
  <!-- Epic-Kitchens-100 -->
  <tr>
    <td align="center">
      <a href="https://epic-kitchens.github.io/2021">Epic-Kitchens-100</a>
    </td>
    <td align="center">
      Largest dataset in first-person (egocentric) vision; multi-faceted, audio-visual, non-scripted recordings in native environments - i.e. the wearers' homes, capturing all daily activities in the kitchen over multiple days.
    </td>
    <td align="center">action, verb and noun</td>
    <td align="center">100</td>
    <td align="center">
      <a href=""></a>
    </td>
  </tr>
  
  <!-- FineGym -->
  <tr>
    <td align="center">
      <a href="https://sdolivia.github.io/FineGym/#download">FineGym</a>
    </td>
    <td align="center">
      FineGym, a new dataset built on top of gymnasium videos. It provides temporal annotations at both action and sub-action levels with a three-level semantic hierarchy.
    </td>
    <td align="center">temporal action, sub-action and semantic three</td>
    <td align="center">99</td>
    <td align="center">
      <a href="">N/A</a>
    </td>
  </tr>
  
  
</table>

Action bounding box detection
----------------------------

<table align="center">
  
  <tr>
    <td align="center">Dataset</td> <td align="center">Brief description</td> <td align="center">Images</td> <td align="center">Procedures</td> <td align="center">Paper</td>
  </tr>
  
  <!-- SARAS-MESAD2021 -->
  <tr>
    <td align="center">
      <a href="https://saras-mesad.grand-challenge.org">SARAS-MESAD2021</a>
    </td>
    <td align="center">
      Dataset contains monocular digital recordings from da Vinci Xi robotic system. Two sub-datasets: MESAD-Real and MESAD-Phantom. MESAD-Real represents the prostatectomy procedures recorded on human patients. It contains four sessions of complete prostatectomy procedure performed by expert surgeons on real patients. MESAD-Phantom is also designed for surgeon action detection during prostatectomy, but is composed of videos captured during procedures on phantoms used for the training of surgeons. MESAD-Real comprises 21 action classes and MESAD-Phantom contemplates a smaller list of 14 action classes. Both the datasets share 11 action classes.
    </td>
    <td align="center">N/A</td>
    <td align="center">9</td>
    <td align="center">
      N/A
    </td>
  </tr>
  
</table>

Skill assessment and workflow recognition
-----------------------------------------

<table align="center">
  <tr>
    <td align="center">Dataset</td> <td align="center">Brief description</td> <td align="center">Images</td> <td align="center">Procedures</td> <td align="center">Paper</td>
  </tr>
  
  <!-- JIGSAWS -->
  <tr>
    <td align="center">
      <a href="https://cirl.lcsr.jhu.edu/research/hmm/datasets/jigsaws_release/">JIGSAWS</a>
    </td>
    <td align="center">
      The JIGSAWS dataset consists of three components: kinematic data (Cartesian positions, orientations, velocities, angular velocities and gripper angle describing the motion of the manipulators), video data (stereo video captured from the endoscopic camera), and manual annotations of gestures (atomic surgical activity segment labels) and skill (global rating score using modified objective structured assessments of technical skills).
    </td>
    <td align="center">N/A</td>
    <td align="center">N/A</td>
    <td align="center">
      <a href="https://cirl.lcsr.jhu.edu/wp-content/uploads/2015/11/JIGSAWS.pdf">Gao et al. 2014</a>
    </td>
  </tr>
  
  <!-- Cataract-101 -->
  <tr>
    <td align="center">
      <a href="https://zenodo.org/record/1220951#.YK_TxmZKg7Y">Cataract-101</a>
    </td>
    <td align="center">
      This dataset contains 101 videos of cataract surgeries annotated with two kinds of information: Anonymous ID and experience level of operating surgeon, and starting points of quasi-standardized operation phases in videos.
    </td>
    <td align="center">1.3M</td>
    <td align="center">101</td>
    <td align="center">
      <a href="https://dl.acm.org/doi/10.1145/3204949.3208137">Schoeffmann et al. 2018</a>
    </td>
  </tr>
  
  <!-- HeiCo -->
  <tr>
    <td align="center">
      <a href="https://www.synapse.org/#!Synapse:syn21903917/wiki/601992">HeiCo</a>
    </td>
    <td align="center">
      The data set contains of data from the ROBUST-MIS 2019 challenge and the Surgical Workflow Challenges from EndoVis 2017 and 2018.
    </td>
    <td align="center">10K</td>
    <td align="center">30</td>
    <td align="center">
      <a href="https://arxiv.org/abs/2005.03501">Maier-Hein et al. 2020</a>
    </td>
  </tr>
  
  <!-- PETRAW -->
  <tr>
    <td align="center">
      <a href="https://www.synapse.org/#!Synapse:syn25147789/wiki/608848">PETRAW</a>
    </td>
    <td align="center">
      Dataset for online automatic recognition of surgical workflow by using both kinematic and stereoscopic video information on a micro-anastomosis training task.
    </td>
    <td align="center">N/A</td>
    <td align="center">100</td>
    <td align="center">
      N/A
    </td>
  </tr>
</table>


Repositories holding multiple datasets
--------------------------------------
* https://endovis.grand-challenge.org
* https://opencas.webarchiv.kit.edu
* http://camma.u-strasbg.fr/datasets
* http://hamlyn.doc.ic.ac.uk/vision
* https://sites.google.com/site/sznitr/code-and-datasets
* https://datasets.simula.no/index.html
