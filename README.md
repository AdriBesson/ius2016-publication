# A compressed beamforming framework for ultrafast ultrasound imaging
[Ecole Polytechnique Fédérale de Lausanne (EPFL)]: http://www.epfl.ch/
[Signal Processing Laboratory (LTS5)]: http://lts5www.epfl.ch
[CREATIS]:https://www.creatis.insa-lyon.fr/site7/fr
[IEEE International Ultrasonics Symposium (IUS 2016)]: http://sites.ieee.org/ius-2016/
[Institute of Sensors, Signals and Systems]: https://www.hw.ac.uk/schools/engineering-physical-sciences/institutes/sensors-signals-systems/basp.htm
[Heriot-Watt University]:https://www.hw.ac.uk/


Adrien Besson<sup>1</sup>, Rafael E. Carrillo<sup>1</sup>, Dimitris Perdios<sup>1</sup>, Marcel Arditi<sup>1</sup>, Olivier Bernard<sup>2</sup>, Yves Wiaux<sup>3</sup> and Jean-Philippe Thiran<sup>1, 4</sup>

<sup>1</sup>[Signal Processing Laboratory (LTS5)], [Ecole Polytechnique Fédérale de Lausanne (EPFL)], Switzerland

<sup>2</sup>[CREATIS], INSA-Lyon, France

<sup>3</sup>[Institute of Sensors, Signals and Systems], [Heriot-Watt University] , UK

<sup>4</sup>Department of Radiology, University Hospital Center (CHUV), Switzerland

Manuscript accepted to the [IEEE International Ultrasonics Symposium (IUS 2016)].

## Abstract
Classical beamforming methods, based on Delay-And-Sum (DAS) require an extensive number of samples and
delay calculations to obtain high-quality images. Compressed Beamforming (CB) proposes an alternative to DAS, based on compressed sensing, which aims at reducing the data rate. However, proposed CB approaches induce a computationally heavy measurement model that hampers their attractiveness for iterative image reconstruction. In this paper, a CB framework, applicable to either radio-frequency or in-phase quadrature data and for both plane wave and diverging wave compounding, is described. The proposed framework exploits a computationally light measurement model which leads to tractable reconstruction. It solves a convex problem and assumes sparsity in a wavelet-based model to achieve high-quality image reconstruction from measurements acquired with only few transducer elements.
