# ydm-landuse

## Related repositories

- [longavailable/ydm](https://github.com/longavailable/ydm)

	- [longavailable/ydm-lucc]
	
	- [longavailable/ydm-climate](https://github.com/longavailable/ydm-climate)
	
		- [longavailable/ydm-rainfall](https://github.com/longavailable/ydm-rainfall)
		
			- [longavailable/ydm-gcm-downscaling](https://github.com/longavailable/ydm-gcm-downscaling)
			
			- [longavailable/ydm-rainfall-analysis](https://github.com/longavailable/ydm-rainfall-analysis)

## Descriptions

| Foldername | Repository | Scripts | Resolution | Coordinate reference system (crs) |
|:----|:----|:----|:----|:----|
| esa-cci-lc-3hm | [longavailable/ydm-esa-landuse-images-3hm] | [ydm-esa-cci-lc-download-gee.py] | 300m | [EPSG:32650] |
| landuse-3hm | [longavailable/ydm-esa-landuse-images-3hm] | [ydm-esa-reclass-and-download-gee.py] | 300m | [EPSG:32650] |
| landuse-5k | [longavailable/ydm-landuse-images-5k] | [download-landuse-images-5k-gee.py] | 5000m | [EPSG:32650] |
| binarized-landuse-5k | [longavailable/ydm-binarized-landuse-images-5k] | [binarize-ydm-landuse.py] | 5000m | [EPSG:32650] |
| landuse-urban-vector-5k | [longavailable/ydm-landuse-urban-vector-5k] | [polygonize-yearly-urban-region.py] |  | [EPSG:32650] |
| simulated-5k | [longavailable/ydm-landuse-images-5k] | Mutiple scripts in [longavailable/ydm-lucc] | 300m | [EPSG:32650] |


[longavailable/ydm-lucc]: https://github.com/longavailable/ydm-lucc
[longavailable/ydm-esa-landuse-images-3hm]: https://github.com/longavailable/ydm-esa-landuse-images-3hm
[longavailable/ydm-landuse-images-5k]: https://github.com/longavailable/ydm-landuse-images-5k
[longavailable/ydm-binarized-landuse-images-5k]: https://github.com/longavailable/ydm-binarized-landuse-images-5k
[longavailable/ydm-landuse-urban-vector-5k]: https://github.com/longavailable/ydm-landuse-urban-vector-5k
[longavailable/ydm-landuse-images-simulated-3hm]: https://github.com/longavailable/ydm-landuse-images-simulated-3hm
[esacci_lc_processor.py]: https://github.com/longavailable/esa-cci-lc-downloader/blob/main/esacci_lc_processor.py
[ydm-esa-cci-lc-download-gee.py]: https://github.com/longavailable/ydm-lulc-gee-scripts/blob/main/001-ydm-esa-cci-lc-download-gee.py
[ydm-esa-reclass-and-download-gee.py]: https://github.com/longavailable/ydm-lulc-gee-scripts/blob/main/003-ydm-esa-reclass-and-download-gee.py
[download-landuse-images-5k-gee.py]: https://github.com/longavailable/ydm-lulc-gee-scripts/blob/main/004-download-landuse-images-5k-gee.py
[binarize-ydm-landuse.py]: https://github.com/longavailable/ydm-lulc-gee-scripts/blob/main/005-binarize-ydm-landuse.py
[polygonize-yearly-urban-region.py]: https://github.com/longavailable/ydm-lulc-gee-scripts/blob/main/006-polygonize-yearly-urban-region.py
[EPSG:32650]: https://epsg.io/32650
[EPSG:4326]: https://epsg.io/4326
