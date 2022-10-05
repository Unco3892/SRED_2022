# Improving Real Estate Rental Estimations with Visual Data
[![DOI:10.3390/bdcc6030096](http://img.shields.io/badge/DOI-10.3390/bdcc6030096-<4C1>.svg)](https://doi.org/10.3390/bdcc6030096) [:page_with_curl:](https://www.mdpi.com/2504-2289/6/3/96):point_left:

[Ilia Azizi](https://iliaazizi.com), [Iegor Rudnytskyi](https://irudnyts.github.io/)

**Abstract:**
> Multi-modal data are widely available for online real estate listings. Announcements can contain various forms of data, including visual data and unstructured textual descriptions. Nonetheless, many traditional real estate pricing models rely solely on well-structured tabular features. This work investigates whether it is possible to improve the performance of the pricing model using additional unstructured data, namely images of the property and satellite images. We compare four models based on the type of input data they use: (1) tabular data only, (2) tabular data and property images, (3) tabular data and satellite images, and (4) tabular data and a combination of property and satellite images. In a supervised context, the branches of dedicated neural networks for each data type are fused (concatenated) to predict log rental prices. The novel dataset devised for the study (SRED) consists of 11,105 flat rentals advertised over the internet in Switzerland. The results reveal that using all three sources of data generally outperforms machine learning models built on only tabular information. The findings pave the way for further research on integrating other non-structured inputs, for instance, the textual descriptions of properties.

## Data
The link to the Swiss Real Estate Dataset (SRED) can be found [here](https://drive.switch.ch/index.php/s/R3mhYgtahI5i3YC). [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

## License
This dataset is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

**Note**: while we tried to identify images that are licensed under a Creative Commons Attribution license, we make no representations or warranties regarding the license status of each image and you should verify the license for each image yourself.

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Code
For reproduciblity, you can access the logs of the runs on tensorboard and view the results as well the model architecture (graphs). Currently, there are no plans to share the code on Github; however, if you're interested, you can open an issue, and we're happy to share with you the version we have and you can integrate the changes via a pull request.
```
tensorboard --logdir logs
```

## Citation
```bibtex
@Article{bdcc6030096,
AUTHOR = {Azizi, Ilia and Rudnytskyi, Iegor},
TITLE = {Improving Real Estate Rental Estimations with Visual Data},
JOURNAL = {Big Data and Cognitive Computing},
VOLUME = {6},
YEAR = {2022},
NUMBER = {3},
ARTICLE-NUMBER = {96},
URL = {https://www.mdpi.com/2504-2289/6/3/96},
ISSN = {2504-2289},
DOI = {10.3390/bdcc6030096}
}
```
