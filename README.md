## Content of my master thesis in Applied Mathematics @ EMAp FGV
#### A method to estimate the Macroscopic Fundamental Diagram using Bus GPS Data

The objective of this project is to present a method for obtaining a network MFD using bus GPS data and a data structure developed by Uber H3 (Uber’s Hexagonal Hierarchical Spatial Index). We use a raw data collection of latitude and longitude data points of buses in Rio de Janeiro, Brazil, from January 2018 to December 2018. It is worth mentioning that the resulting MFD of the proposed method serves as a basis to support the development of public transportation management systems, which is able to make accurate traffic state predictions. The findings confirm the usefulness of bus GPS data in finding a Macroscopic Fundamental Diagram, and future research directions are addressed.

## Structure

```bash
.
├── code # Folder containing all thesis codes
│   ├── cache
│   ├── MapMatcher.ipynb
│   ├── map_matching_OSMNX.ipynb
│   ├── QuadTree.ipynb
│   ├── Tratamento.ipynb # main code
│   ├── Untitled1.ipynb
│   └── Untitled.ipynb
├── LICENSE # MIT license 
├── plots_images # Folder containing all images of the thesis
│   ├── dens_vel_15Min_hex12.png
│   ├── dens_vel_5Min_hex11.png
│   ├── h3.jpg
│   ├── hexag_depict.jpg
│   ├── hexagons_plot_data.html
│   ├── hex_depict.jpg
│   ├── map_hex_tijuca.jpg
│   ├── map.html
│   ├── maps_gps.jpg
│   ├── plot_data.html
│   ├── quadtree_circle.JPG
│   └── TableofCellAreas_H3.png
└── README.md

3 directories, 20 files

```

## License
[MIT](https://choosealicense.com/licenses/mit/)
