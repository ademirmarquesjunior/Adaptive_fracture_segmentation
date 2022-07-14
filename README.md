# Adaptive_fracture_segmentation

**[Paper] Adaptive Segmentation for Discontinuity Detection on Karstified Carbonate Outcrop Images From UAV-SfM Acquisition and Detection Bias Analysis**


Authors:
 [Ademir Marques Junior<sup>1</sup>](https://www.researchgate.net/profile/Ademir_Junior),
 [Graciela dos Reis Racolte<sup>1</sup>](https://www.researchgate.net/profile/Graciela-Racolte),
 [Daniel Zanotta<sup>1</sup>](https://www.researchgate.net/profile/Daniel_Zanotta),
 [Eniuce Menezes<sup>2</sup>](),
 [Caroline Lessio Cazarin<sup>3</sup>](https://www.researchgate.net/profile/Caroline_Cazarin),	
 [Luiz Gonzaga Junior<sup>1</sup>](https://www.researchgate.net/profile/Luiz_Gonzaga_da_Silveira_Jr),
 [Maurício Roberto Veronez<sup>1</sup>](https://www.researchgate.net/profile/Mauricio_Veronez)
 
<sup>1</sup>[Vizlab | X-Reality and GeoInformatics Lab<sup>1</sup>](http://vizlab.unisinos.br/), 
<sup>2</sup>[Federal University of Pernambuco, Recife, Brazil<sup>2</sup>](https://www.ufpe.br/web/english/home),
<sup>3</sup>[CENPES-Petrobras<sup>3</sup>](https://petrobras.com.br/en/our-activities/technology-innovation/)  

The identification of fractures and discontinuities has great importance on the fluid flow estimation in hydrocarbon reservoirs since they influence the properties of porosity and permeability. Due to the inaccessibility and sparsity of reservoir data, the fracture characterization is generally assessed through the study of outcrop analogues using remote sensing or in situ observations by a specialist. Considering the remote sensing methods, the unmanned Aerial Vehicle (UAV) acquisition combined with Structure from Motion (SfM) photogrammetry is a low-cost way to generate products like orthorectified images, allowing manual and automated methods of fracture trace detection. Automatic approaches, commonly used to address this problem, present some known limitations and disadvantages due to the nature of the outcrops and weather conditions during UAV acquisitions. In this work, we focus on fracture detection over karstic regions that are highly fractured. For this, we evaluated a series of adaptive segmentation methods based on thresholding. The Sauvola local adaptive segmentation presented the best result when compared to a manually annotated ground truth. The segmentation results were further improved by the use of the binary denoising method Non-Local means. We also carried an evaluation of the influence of the sun position in the fracture detection, and to reduce this inherent bias we combined three UAV acquisitions done over the karstic carbonate outcrop, namely Rosário pavement in the Jandaíra formation northeast Brazil. With the proposed methodology we acquired more accurate fracture data over the study area, which follows the directional statistics of previous works carried out in the region.

[DOI: 10.1109/ACCESS.2022.3151897](https://doi.org/10.1109/ACCESS.2022.3151897)



## Installation

This Python script requires a Python 3 environment and the following installed libraries as seen in the file requirements.txt.

## Usage

Open the "ipnb" file in a Python notebook environment.

## Credits	
This work is credited to the [Vizlab | X-Reality and GeoInformatics Lab](http://vizlab.unisinos.br/) and the following developers:	[Ademir Marques Junior](https://www.researchgate.net/profile/Ademir_Junior).

## License

    CC by 4.0

## How to cite

If you find our work useful in your research please consider citing our papers:

```bash
@ARTICLE{9714365,
  author={Marques, Ademir and Racolte, Graciela and Zanotta, Daniel C. and Menezes, Eniuce and Cazarin, Caroline Lessio and Gonzaga, Luiz and Veronez, Maur&#x00ED;cio Roberto},
  journal={IEEE Access}, 
  title={Adaptive Segmentation for Discontinuity Detection on Karstified Carbonate Outcrop Images From UAV-SfM Acquisition and Detection Bias Analysis}, 
  year={2022},
  volume={10},
  number={},
  pages={20514-20526},
  doi={10.1109/ACCESS.2022.3151897}}
```
