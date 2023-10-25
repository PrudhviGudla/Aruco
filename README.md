# Aruco

Introduction to Aruco tags
https://www.youtube.com/watch?v=_gvvK6h-wxg&list=WL&index=25&t=4s

To generate aruco tags run this command
```
python aruco_gen.py --id 1000 --type DICT_5X5_50 --output <dir>

```
To detect the aruco tag, mark centre and calculate orientation
```
python detect_aruco.py --image <dir> --type DICT_6X6_1000
```
![image](https://github.com/PrudhviGudla/Aruco/assets/106007058/9f0a5828-b042-4c64-ac16-0ef8dbef63ea)

To find out the types of aruco tags present in a image
```
python guess_aruco.py --image <dir>
```
## Important point
Axes in opencv:
![image](https://github.com/PrudhviGudla/Aruco/assets/106007058/06ccbcbf-c81c-459b-be08-6f4afd0543c4)

## Code explanation
https://pyimagesearch.com/2020/12/14/generating-aruco-markers-with-opencv-and-python/
https://pyimagesearch.com/2020/12/21/detecting-aruco-markers-with-opencv-and-python/
https://pyimagesearch.com/2020/12/28/determining-aruco-marker-type-with-opencv-and-python/
