# Installation

    python setup.py install

    Prereqs:

    * OpenCV 3 with python package (ironically still called `cv2`)
    * `tesseract` command-line program
    * Python packages:
        * fuzzywuzzy
        * numpy
        * scikit-learn

# Test

        georeg --year 1979 --state RI --images test/img.png --outdir . --pre-processed
