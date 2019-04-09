# Get a notification on Telegram when a person is present
Get a notification on Telegram when intruder is in a room, using Tensorflow/OpenCV/Raspberry Pi3/Telegram

![](telegramtensor.gif)

As soon as a person is identified in the neural-net, you'll get a notice on the Telegram app on your phone!


# For this to work you need to install the following:
- Tensorflow & OpenCV (Credits to https://github.com/EdjeElectronics/TensorFlow-Object-Detection-on-the-Raspberry-Pi) for making a great tutorial of how to properly set up Tensorflow on RPi!
- Telepot, pythonframework for Telegram bot API

You also need to setup a account on Telegram and create a bot, afterwards just insert your CHAT_ID in the script and you can easily send notifications to your Telegramapp if you have notifications activated :-)

The code uses ssdlite_mobilenet_v2_coco_2018_05_09, it extracts 'person' from the detections, and by using your bot_token and personal chat_id you can easily get a notification if a certain object is detected.

