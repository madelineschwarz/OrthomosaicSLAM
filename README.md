# OrthomosaicSLAM
### Forked from: TextZip OrthomosaicSLAM: https://github.com/TextZip/OrthomosaicSLAM
 
Creating mosaic images from QUAKES-I imagery

Successfully mosaics images from the same camera, but mosaics lose georeferencing metadata

QUAKES-I 8 camera array (nadir port of aircraft)
![image](https://github.com/madelineschwarz/OrthomosaicSLAM/assets/60195170/3c62446c-3df5-4b8e-afc8-e3d30861ec2a)

Individual images from Camera 68 (4)
![image](https://github.com/madelineschwarz/OrthomosaicSLAM/assets/60195170/a5bfd5e9-ed27-424f-8c60-544ca473525d)

Mosaic from Camera 68 (4)
![image](https://github.com/madelineschwarz/OrthomosaicSLAM/assets/60195170/c2ffc0dd-592c-4248-b356-f9f428492be5)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Original:
To carry out drone-based aerial surveying for generating orthomosaic maps on the fly, this project explores the image processing stack required to achieve the same using the most economical hardware and software footprint. The project explores corner and blob-based feature extraction techniques followed by brute force and KNN based feature matching methods which are later used to generate a homography matrix for stitching images that are passed through a cascaded image mixer to generate orthomosaic maps of a given dataset.

Explanation and documentation: https://textzip.github.io/posts/Orthomosaic-SLAM/

## Results
### Input 1
![Image1](/images/city_input.jpg)
### Output 1
![Image1](/images/city_output.png)
### Input 2 
![Image1](/images/lake_nornal_input.jpg)
### Output 2
![Image1](/images/lake_normal_output.png)
### Input 3
![Image1](/images/extended_lake_input.jpg)
### Output 3
![Image1](/images/lake_extended_output.png)


## Usage
```bash
python3 main.py -i PATH_TO_IMAGES -o OUTPUT_PATH
```

## Paramters
Will be updated soon. 
