[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<br />
<div align="center">
  <a href="https://github.com/Rima119/segatlas/">
    <img src="images/logo.png" alt="Logo" width="300" height="300">
  </a>

  <h3 align="center">Track'N Goal</h3></h3>

  <p align="center">
    A goal tracking Web/Mobile (Andoid & iOS) application.
    <br />
    <br />
    <br />
    <a href="https://rima119.github.io/segatlas/">Landing Page</a>
    ·
    <a href="https://rimcode.medium.com/">Blog Article (soon)</a>
    .
    <a href="https://github.com/Rima119/segatlas/issues">Report Issues</a>
    ·
    <a href="https://github.com/Rima119/segatlas/issues">Request Feature</a>
  </p>
</div>


## Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Related projects](#related-projects)
- [Licensing](#licensing)


## Introduction
SegAtlas is a professional-grade tool designed for evaluating the quality and accuracy of object-centric image segmentation. It provides users with a comprehensive platform for assessing segmentation results, enabling precise analysis and evaluation based on various metrics.

Deployed Project link (soon): [Deployed Project]()

Final Project Blog Article (soon): [Blog Article]()

### Authors

Rim EL FILALI - [Github](https://github.com/Rima119) / [Linkedin](https://www.linkedin.com/in/rim-el-filali-0710a6269/)

### Built With

[![python][python]][python-url]
[![opencv][opencv]][opencv-url]
[![numpy][numpy]][numpy-url]
[![panda][panda]][panda-url]

### Features
- Object Segmentation Quality Assessment: Evaluate the quality of segmentation results by comparing ground truth and segmentation images using multiple metrics.
- Comprehensive Instance Segmentation Quality Assessment: Assess segmentation quality across entire COCO datasets or specific subsets using supported metrics.
- Solidity Assessment: Analyze solidity ratios and visualize convex hulls to gain deeper insights into segmentation quality.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python libraries: tkinter, PIL (Python Imaging Library), OpenCV, NumPy, pandas

### Installation

1. Clone this repository to your local machine
        
        git clone https://github.com/Rima119/segatlas.git
        

2. Navigate to the repository directory in a terminal

        cd segatlas
        

4. Install required Python libraries

        pip install -r requirements.txt
        

5. Run the SegAtlas app

        python segatlas.py
        

## Usage
The app provides the following features:
### -Object Segmentation Quality
SegAtlas offers users a comprehensive platform to assess the quality and accuracy of object segmentation results. 
This functionality is referred to as "Image Evaluation" in the GUI.


### -Comprehensive Instance Segmentation Quality
This section in SegAtlas provides users with a robust framework to assess instance segmentation quality across entire COCO datasets or specific subsets of any segmentation method. 
Named as "Dataset Evaluation" within the GUI, this feature streamlines the evaluation process, allowing users to swiftly access and analyze segmentation quality based on comprehensive datasets.


### -Solidity assessment
Solidity assessment is a pivotal feature accessible from the menu of SegAtlas. It offers users a robust toolkit for evaluating the solidity of segmentation masks and exploring mask characteristics.


### -User experience management
User experience management is a critical aspect of the SegAtlas. It aims to ensure a seamless and intuitive interaction for users, enhancing their overall satisfaction and efficiency while utilizing the GUI. 



## Contributing
If you have issues, questions or create a pull request.

</br>
For suggestions follow these steps:

1. Fork this repository
2. Create your feature branch (git checkout -b feature/fooBar)
3. Commit your changes (git commit -am 'Add some fooBar')
4. Push to the branch (git push origin feature/fooBar)
5. Create a new Pull Request
</br>
Please ensure your pull request adheres to the following guidelines:

- Alphabetize your entry.
- Search previous suggestions before making a new one, as yours may be a duplicate.
- Suggested READMEs should be beautiful or stand out in some way.
- Make an individual pull request for each suggestion.
- New categories, or improvements to the existing categorization are welcome.
- Keep descriptions short and simple, but descriptive.
- Start the description with a capital and end with a full stop/period.
- Check your spelling and grammar.
- Make sure your text editor is set to remove trailing whitespace.
- Use the `#readme` anchor for GitHub READMEs to link them directly

Thank you for your suggestions!


## Licensing
This project is licensed under the [MIT License](https://github.com/Rima119/segatlas/blob/main/LICENSE.txt) - see the LICENSE.txt file for details.



[contributors-shield]: https://img.shields.io/github/contributors/Rima119/segatlas.svg?style=for-the-badge
[contributors-url]: https://github.com/Rima119/segatlas/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Rima119/segatlas.svg?style=for-the-badge
[forks-url]: https://github.com/Rima119/segatlas/forks
[stars-shield]: https://img.shields.io/github/stars/Rima119/segatlas.svg?style=for-the-badge
[stars-url]: https://github.com/Rima119/segatlas/stargazers
[issues-shield]: https://img.shields.io/github/issues/Rima119/segatlas.svg?style=for-the-badge
[issues-url]: https://github.com/Rima119/segatlas/issues
[license-shield]: https://img.shields.io/github/license/Rima119/segatlas.svg?style=for-the-badge
[license-url]: https://github.com/Rima119/segatlas/blob/main/LICENSE.txt

[python]: https://www.vectorlogo.zone/logos/python/python-icon.svg
[python-url]: https://python.org
[opencv]: https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg
[opencv-url]: https://opencv.org
[numpy]: https://www.vectorlogo.zone/logos/numpy/numpy-icon.svg
[numpy-url]: https://numpy.org/
[panda]: https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg
[panda-url]: https://pandas.pydata.org/
