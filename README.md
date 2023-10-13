FaceSwap Images using Insightface implemented in Jupyter notebook

1. Create an empty directory and cd into the directory
2. Create a Python environment for this specific project
Example:
```sh
cd Desktop/Insightface
python -m venv insightface
.\insightface\Scripts\activate
pip install ipykernel
python -m ipykernel install --name=insightface
```
4. If you want to uninstall the environment
```
jupyter kernelspec uninstall insightface
```
5. Install insightface in this environment
```
pip install insightface
```
6. Execute the cells in Faceswap.ipynb file using any image to detect the source and target faces


Results of this project:
1. India Cricket Team players' faces swapped with Lewis Hamilton's face
   
   Before
   ![Before1](https://github.com/arijitbhowal/FaceSwap-with-Insightface/assets/88677587/f0d0848c-874a-4fee-b883-7730c8607c6a)
   After
   ![After1](https://github.com/arijitbhowal/FaceSwap-with-Insightface/assets/88677587/54733f82-8f9b-4326-a3d5-855ad47ac823)

3. Imran Tahir's face swapped with Rohit Sharma's face

   ![Target](https://github.com/arijitbhowal/FaceSwap-with-Insightface/assets/88677587/97364265-97e0-42fc-926a-5463cbd3617a)
   ![Source](https://github.com/arijitbhowal/FaceSwap-with-Insightface/assets/88677587/34fe08ea-15f8-4132-ac3f-08f0e9324ccd)
   ![Result](https://github.com/arijitbhowal/FaceSwap-with-Insightface/assets/88677587/641c313a-29ce-4eb3-9f7b-ce5425740daf)

   

