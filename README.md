# AstroVLM Dataset
This dataset contains a collection of astrophotography images. Each image file (e.g., `.jpg`) is accompanied by a `.json` file that provides detailed imaging conditions and expert analysis.

## Dataset Content
Each JSON file corresponds to one astrophotography image and contains the following key-value pairs:

- `input_text`: A `string` describing the imaging conditions, including the target celestial object, location, and all equipment used (e.g., telescope, mount, camera, filters).

- `expert_answer`: A `string` containing a detailed analysis from an expert. This includes feedback on the image's strengths and specific, actionable suggestions for improvement.

- `path`: A `string` that specifies the relative path to the associated image file.

## PS

The current repository only contains a simplified part of dataset, for example only. After the paper is accepted, all the dataset will be opensourced.
