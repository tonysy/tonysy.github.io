+++
title = "Predicting Salient Face in Multiple-face Videos"
date = "2017-05-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Yufan Liu", "**Songyang Zhang**", "Mai Xu", "Xuming He"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *Computer Vision and Pattern Recognition(CVPR)*, IEEE."
publication_short = "In *CVPR*"

# Abstract and optional shortened version.
abstract = "Although the recent success of convolutional neural network (CNN) advances state-of-the-art saliency prediction in static images, few work has addressed the problem of predicting attention in videos. On the other hand, we find that the attention of different subjects consistently focuses on a single face in each frame of videos involving multiple faces. Therefore, we propose in this paper a novel deep learning (DL) based method to predict salient face in multiple-face videos, which is capable of learning features and transition of salient faces across video frames. In particular, we first learn a CNN for each frame to locate salient face. Taking CNN features as input, we develop a multiple-stream long short-term memory (M-LSTM) network to predict the temporal transition of salient faces in video sequences. To evaluate our DL-based method, we build a new eye-tracking database of multiple-face videos. The experimental results show that our method outperforms the prior state-of-the-art methods in predicting visual attention on faces in multiple face videos."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["deep-learning"]

# Links (optional).
url_pdf = "https://xmhe.bitbucket.io/papers/salientface_cvpr17.pdf"
url_preprint = ""
url_code = ""
url_dataset = "https://github.com/tonysy/salient-face-in-MUVFET"
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.