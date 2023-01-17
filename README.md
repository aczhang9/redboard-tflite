## Create and run a new project with PlatformIO:
1. Clone this repo.
2. Follow QuickStart instructions here: https://github.com/nigelb/platform-apollo3blue#quick-start to install Sparkfun's Arduino framework for PlatformIO.  
*Note: This repo was compiled with V2.2.0 of Sparkfun's Apollo3 library.*
3. Initialize PlatformIO project.
```
cd redboard-tflite
platformio init --board SparkFun_RedBoard_Artemis
```
4. Add `upload_speed = 230400` to `platformio.ini` file.
5. Compile code: `platformio run -v`
6. Upload binary to board: `platformio run -t upload -v`

## Notes about this Arduino TFLite library
- Downloaded library here: https://www.ardu-badge.com/Arduino_TensorFlowLite/zip  
- Fixed comparisons.h file according to this post: https://forum.sparkfun.com/viewtopic.php?t=55301  
- Added library.json file to lib/ folder: https://github.com/maxgerhardt/pio-nano33ble-microspeech-example/blob/master/lib/Arduino_TensorFlowLite/library.json   
