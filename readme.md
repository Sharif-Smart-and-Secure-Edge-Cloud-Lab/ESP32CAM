# Tasks:
> **NOTE:** [Your feedback will be greatly appreciated.]
<p>
<img src="./images/Module 1.jpeg" alt="Select extension mode" width="950">
</p>

1. Set up the ESP-IDF and build/flash a test app for the module. 
https://docs.espressif.com/projects/esp-idf/en/latest/esp32/

	* Click on Get Started: https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/index.html
	
	* Click on VSCode Extension: https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/vscode-setup.html
	
	* Click on Quick Installation Guide: https://github.com/espressif/vscode-esp-idf-extension/blob/master/docs/tutorial/install.md
	
	Follow the steps:
	
		* In Step 1, Click on Download and install Visual Studio Code: https://code.visualstudio.com/, It takes 15 minutes.
		
		* The rest of steps take a total of 30 minutes.
		
	* Click on basic use: https://github.com/espressif/vscode-esp-idf-extension/blob/master/docs/tutorial/basic_use.md
	
	Follow the steps:
	
		* In Step 8 you will get stuck, because the explanations is not enough. Thus we give some explanations below:
		
		* If in the Get Started page, click on <Start a Project on Windows>, in the appearing page you see the topic "Connect Your Device", in this topic click on <Establish Serial Connection with ESP32>, then you will see a page that says you need either CP210x of FTDI. We bought CP2102. In order for the laptop to recognize CP2102 board, we need to download and install a proper driver. In this page, there is a link <CP210x USB to UART Bridge VCP Drivers> to download the driver but in Windows 7 it doesn't work. So I downloaded the proper driver from https://www.pololu.com/docs/0J7/all by following its instructions.
		
		* Note: after installing the driver, when you enter <ESP-IDF: Select port to use> command in Command Palette in Visual studio, the connected com-port automatically appears in the textbox above, just must click on it do.
		

2. Example:
https://github.com/espressif/vscode-esp-idf-extension/blob/master/docs/tutorial/basic_use.md
--------------------------------------------------------------------------------------------------------------
3. Set up the WiFi Station interface and HTTP client.
https://github.com/espressif/esp-idf/tree/master/examples/wifi/getting_started
--------------------------------------------------------------------------------------------------------------
4. Run esp-dl with face detection and face recognition model.
https://github.com/espressif/esp-dl
--------------------------------------------------------------------------------------------------------------
5. Send detected face and identity vector to the server via rest API.
--------------------------------------------------------------------------------------------------------------
6. Set up the Edge Impulse framework 
https://docs.edgeimpulse.com/docs/development-platforms/officially-supported-mcu-targets/espressif-esp32
