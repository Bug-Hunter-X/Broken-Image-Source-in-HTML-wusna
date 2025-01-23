# Broken Image Source in HTML
This repository demonstrates a common yet often overlooked HTML error: using an incorrect or broken image source path within the `<img>` tag.  This leads to the image failing to load, potentially degrading the user experience.
The `bug.html` file contains the erroneous code, and the `bugSolution.html` file provides the corrected version.
The problem lies in the use of `broken-image.jpg` as the image source. This file likely does not exist in the same directory as the HTML file.
The solution involves providing a valid and accessible path to the image resource.