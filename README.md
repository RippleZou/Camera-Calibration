This two cpp files are used to create a chess image and calibrate your camera through the image.

Reference compile process:
1.g++ Calibration_Picture.cpp -o Calibration_Picutre `pkg-config --cflags --libs opencv`
2.g++ Camera_Calibration.cpp -o Calibration `pkg-config --cflags --libs opencv`

