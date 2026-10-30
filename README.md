# FirstMile

Source code and instances for **first-mile parcel pickup: vehicle routing with packing constraints under disruption**.

This repository accompanies the article:

> Giménez-Palacios, I., Parreño, F., Álvarez-Valdés, R., Paquay, C., Brito Oliveira, B., Carravilla, M. A., & Oliveira, J. F. (2022).
> First-mile logistics parcel pickup: Vehicle routing with packing constraints under disruption.
> *Transportation Research Part E: Logistics and Transportation Review*, 164, 102812.
> https://doi.org/10.1016/j.tre.2022.102812

Open-access version (RODERIC, Universitat de València): https://hdl.handle.net/10550/129004

## Problem

The article studies first-mile parcel pickup as a vehicle routing problem with time windows and three-dimensional loading constraints. It considers a static version and a dynamic version in which disruptions and demand changes occur during operation. Three reactive strategies are proposed depending on fleet availability.

## Contents

| File | Description |
|---|---|
| `Source Code.rar` | Source code of the algorithms for the static and dynamic versions of the problem |
| `MO2Instances.rar` | Instances used in the computational study |
| `MODisruptions.rar` | Instances with disruptions used in the computational study |
| `CeschiaDisruptions.rar` | Disruption instances built from the Ceschia et al. benchmark |

The instance sets are also available with a persistent identifier on Mendeley Data:
https://doi.org/10.17632/fffg27yx9m.1

## Citation

If you use this code or these instances, please cite the article:

```bibtex
@article{GimenezPalacios2022FirstMile,
  title   = {First-mile logistics parcel pickup: Vehicle routing with packing constraints under disruption},
  author  = {Gim{\'e}nez-Palacios, Iv{\'a}n and Parre{\~n}o, Francisco and {\'A}lvarez-Vald{\'e}s, Ram{\'o}n and Paquay, C{\'e}lia and Brito Oliveira, Beatriz and Carravilla, Maria Antónia and Oliveira, Jos{\'e} Fernando},
  journal = {Transportation Research Part E: Logistics and Transportation Review},
  volume  = {164},
  pages   = {102812},
  year    = {2022},
  doi     = {10.1016/j.tre.2022.102812}
}
```

## Funding

This work was supported by the projects RTI2018-094940-B-I00 (OPTEP, Spain), SBPLY/17/180501/000282 (Junta de Comunidades de Castilla-La Mancha, Spain) and POCI-01-0145-FEDER-029609 (Portugal).

## License

The source code is released under the [MIT License](LICENSE).
