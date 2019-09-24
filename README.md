# Trigger-word-detection
In this project, we will construct a speech dataset and implement an algorithm for trigger word detection (sometimes also called keyword detection, or wakeword detection). Trigger word detection is the technology that allows devices like Amazon Alexa, Google Home, Apple Siri, and Baidu DuerOS to wake up upon hearing a certain word.

For this notebook, our trigger word will be "Activate." Every time it hears we say "activate," it will make a "chiming" sound. By the end of this project, we will be able to record a clip of ourself talking, and have the algorithm trigger a chime when it detects us saying "activate."

After completing this project, perhaps we can also extend it to run on our laptop so that every time we say "activate" it starts up our favorite app, or turns on a network connected lamp in our house, or triggers some other event?
In this assignment we will learn to:

1.)	Structure a speech recognition project

2.)	Synthesize and process audio recordings to create train/dev datasets

3.)	Train a trigger word detection model and make predictions
