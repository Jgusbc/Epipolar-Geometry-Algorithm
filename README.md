# Epipolar-Geometry-Algorithm

En caso que no te deje correrlo por problemas de SIFT prueba descargando una version diferente de OpenCV con estos comandos:
pip install opencv-python==3.4.2.16

pip install opencv-contrib-python==3.4.2.16

en caso de que no funcione
la linea 8 sift = cv2.xfeatures2d.SIFT_create() cambialo por: sift = cv2.SIFT_create()
