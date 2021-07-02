# sanjeev_projects
warning in jupiter notebook: C:\Users\sanje\anaconda3\lib\site-packages\PIL\Image.py:962: UserWarning: Palette images with Transparency expressed in bytes should be converted to RGBA images
  warnings.warn(         
  
  
  
  error in pycharm:        
  File "C:\Users\sanje\PycharmProjects\facemaskdetection\mask_detect_train.py", line 34, in <module>
    image = img_to_array(image)
  File "C:\Users\sanje\PycharmProjects\facemaskdetection\venv\lib\site-packages\tensorflow\python\keras\preprocessing\image.py", line 228, in img_to_array
    return image.img_to_array(img, data_format=data_format, **kwargs)
  File "C:\Users\sanje\PycharmProjects\facemaskdetection\venv\lib\site-packages\keras_preprocessing\image\utils.py", line 309, in img_to_array
    x = np.asarray(img, dtype=dtype)
  File "C:\Users\sanje\PycharmProjects\facemaskdetection\venv\lib\site-packages\numpy\core\_asarray.py", line 83, in asarray
    return array(a, dtype, copy=False, order=order)
TypeError: __array__() takes 1 positional argument but 2 were given
Process finished with exit code 1
