
Description
-----------


Tool classification
-------------------

<table align="center">
  <tr>
    <td align="center">Dataset</td> <td align="center">Brief description</td> <td align="center">Images</td> <td align="center">Procedures</td> <td align="center">Paper</td>
  </tr>
  
  <!-- Cholec80 -->
  <tr>
    <td align="center">
      <a href="http://camma.u-strasbg.fr/datasets">Cholec80</a>
    </td>
    <td align="center">
      80 videos of cholecystectomy surgeries performed by 13 surgeons. The videos are captured at 25 fps. The dataset is labeled with the phase (at 25 fps) and tool presence annotations (at 1 fps). A tool is defind as present in an image if at least half of the tool tip is visible.
    </td>
    <td align="center">86K</td>
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
    <td align="center">900K</td>
    <td align="center">50</td>
    <td align="center">
      <a href="https://www.sciencedirect.com/science/article/abs/pii/S136184151830865X">Al Hajj et al. 2019</a>
    </td>
  </tr>
  
</table>


Tool-tissue action detection
----------------------------

<table align="center">
  <tr>
    <td align="center">Dataset</td> <td align="center">Brief description</td> <td align="center">Images</td> <td align="center">Procedures</td> <td align="center">Paper</td>
  </tr>
  
  <!-- CholecT50 -->
  <tr>
    <td align="center">
      <a href="https://cholectriplet2021.grand-challenge.org/">CholecT50</a>
    </td>
    <td align="center">
      Every frame is annotated with labels from the triplet: instrument, verb and target.
    </td>
    <td align="center">N/A</td>
    <td align="center">N/A</td>
    <td align="center">
      N/A
    </td>
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
    <td align="center">4</td>
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
  
  <!-- MISAW -->
  <tr>
    <td align="center">
      <a href="https://www.synapse.org/#!Synapse:syn21776936/wiki/601700">MISAW</a>
    </td>
    <td align="center">
      The data-set contains 27 micro-anastomosis training sequences and is composed of the following information: stereoscopic video, kinematic data, workflow annotation at 3 levels of granularity (phases, steps, and activities).
    </td>
    <td align="center">N/A</td>
    <td align="center">27</td>
    <td align="center">
      <a href="https://arxiv.org/abs/2103.13111">Huaulmé et al. 2021</a>
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


Please open an issue if you see a relevant open dataset which is missing or if you find inacurate information.