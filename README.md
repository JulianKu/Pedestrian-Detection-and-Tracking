# Pedestrian Detection & Tracking

Universitat Politècnica de Catalunya (UPC), Barcelona
Faculty of Informatics (FIB),
Cognitive Interaction with Robots (MAI-CIR),
Final Course Project
WS 2018/2019


## Description
This is an integration of YOLO object detection with SORT tracking algorithm modified for pedestrian detection and tracking applied to the JAAD dataset.
<object data="Functional_Architecture.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://drive.google.com/viewerng/
viewer?embedded=true&url=https://github.com/JulianKu/Pedestrian-Detection-and-Tracking/blob/master/Functional_Architecture.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://github.com/JulianKu/Pedestrian-Detection-and-Tracking/blob/master/Functional_Architecture.pdf">Download PDF</a>.</p>
    </embed>
</object>


For more detail on the project and references, please have a look into the [final report](Final_Report.pdf)


## How to
The project is split into several subtasks with a self-contained [`Google Colab`](https://colab.research.google.com) Jupyter Notebook.
1) Run the [JAAD Dataset Preprocessing](JAAD%20Dataset%20Preprocessing/JAAD.ipynb) Notebook
2) Run the [YOLO Pedestrian Detection](YOLO%20Pedestrian%20Detection/YOLO_PedDetection.ipynb) Notebook to train the neural network
    - you will probably exceed the Google Colab runtime limit so you can use the [Save Checkpoints](YOLO%20Pedestrian%20Detection/SaveCheckpoints.ipynb) Notebook to create checkpoints to restart training from
3) Run the [SORT Tracking](SORT%20Object%20tracker/SORT.ipynb) on your detection results
