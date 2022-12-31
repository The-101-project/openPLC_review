[![](https://img.shields.io/badge/organization-The--101--project-blue.svg)](https://github.com/The-101-project) 
[![](https://img.shields.io/badge/remote-openPLC__review-green.svg)](https://github.com/The-101-project/openPLC_review) 
[![](https://img.shields.io/badge/local-F:\prj__soft\openPLC__review-orange.svg)]()

[back to top](README.md)


# log


## 30/12/2022

* l1. While checking Elektor shop I saw the book `PLC Programming with the Raspberry Pi and the OpenPLC Project`
* l2. I googled the Elektor book title and found it available at Amazon UK
* l3. The book focus, seems to be on R-Pi and ESP8266
* l4. I also checked other google findings on openPLC and R-Pi
* l5. openPLC can run in every hardware where its runtime can be installed
* l6. Plenty 8/32bit Arduino variations can be used
* l7. Also ESP32, ESP8266, R-Pi, RP2040, and more...
* l8. openPLC editor runs on Windows, Linux, Macos
* l9. I downloaded and installed the openPLC editor for Windows
* l10. In openPLC editor, I opened the BLINK example, which is a LADDER diagram
* l11. Then pressed the Arduino-symbol button: The ladder program compiled to C code and a dialogue box opened
* l12. I selected Arduino-Uno, No download, only compilation (I had no board), ModBus RTU
* l13. Then pressed the COMPILE button. The proccess took long time, as it was installing various MCU support packages (not only for UNO), probably this happens only for the first compilation after openPLC editor was installed
* l14. A set of bin files was created to be uploaded to the Arduino-UNO board
* l15. A 2nd example (Traffic_light) is Arduino-compiled fast, no upload for support packages
* l16 the compiled binaries are overriding the previous comilation binaries, at `C:\Users\nikolaos.chalikias\OpenPLC_Editor\editor\arduino\examples\Baremetal\build\arduino.avr.uno`
* l17. ESP32-C3 compilation failed :x:
* l18. Update openPLC editor using File/Update
* l19. For compilation ESP32-C3 downloads support packages
* l20. ESP32-C3, 'trafic_light` compilation FAILED :x:
* l21. ESP32-C3, 'Blink` compilation FAILED :x:
* l22. STM32-F103 blue pill, 'Blink` compilation DONE! :heavy_check_mark:
* l23. STM32-F411 black pill, 'Blink` compilation DONE! :heavy_check_mark:
* l24. Nano RP2040 Connect, 'Blink` compilation DONE! :heavy_check_mark:
* l25. ESP32, 'Blink` compilation DONE! :heavy_check_mark:
* l26. nano 33 ioT, 'Blink` compilation DONE! :heavy_check_mark:
* l27. Raspberry Pico W, 'Blink` compilation DONE! :heavy_check_mark:
* l28. Arduino Mega, 'Blink` compilation DONE! :heavy_check_mark:
* l29. ESP32-S2, 'Blink` compilation DONE! :heavy_check_mark:
* l29. ESP32-DOIT-DEVKIT-V1, 'Blink` compilation FAILED :x:
* l30. Arduino Nano, 'Blink` compilation DONE! :heavy_check_mark:
* l31. Arduino Zero native USB port, 'Blink` compilation DONE! :heavy_check_mark:
* l31. ESP8266 NodeMCU, 'Blink` compilation DONE! :heavy_check_mark:
* l32. The `Upload to Arduino button' merges the runtime and the c-program in a single binary to upload to the selected Arduino board
* l33. Raspberry-pi is a Linux system, so the `runtime` is installed standalone
* l34. The `runtime` in Linux communicates and gets the code to run, via a webserver

## 31/12/2022

* l35. STM32-F103 blue pill, 'Traffic_light` compilation DONE! :heavy_check_mark:
* l36. STM32-F411 black pill, 'Traffic_light` compilation DONE! :heavy_check_mark:
* l37. Raspberry Pico W, 'Traffic_light` compilation  FAILED :x:
* l38. Nano RP2040 Connect, 'Traffic_light` compilation  FAILED :x:
* l39. ESP32, 'Traffic_light` compilation  FAILED :x: 
* l40. ESP32-S2, 'Traffic_light` compilation  FAILED :x:  
* l41. ESP32-C3, 'Traffic_light` compilation  FAILED :x: 
* l42. Arduino UNO, 'Traffic_light` compilation DONE! :heavy_check_mark:   
* l43. Arduino Mega, 'Traffic_light` compilation DONE! :heavy_check_mark:  
* l44. Arduino Nano, 'Traffic_light` compilation DONE! :heavy_check_mark:  
* l45. Nano 33 ioT, 'Traffic_light` compilation DONE! :heavy_check_mark:  
* l46. Portenta mchine Control H7, 'Traffic_light` compilation FAILED :x:  
* l47. ESP8266 NodeMCU, 'Traffic_light` compilation DONE! :heavy_check_mark: 
