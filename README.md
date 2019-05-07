This aims to provide the deaf with an affordable solution for their day-to-day communication activities while on the move.

Being an advocate of participating in inclusive initiatives as a completely blind person myself — This project can assist the deaf when they need to talk to persons who are not deaf and do not know how to use sign language.

This video shows the target objectives of this project:  https://www.youtube.com/tv#/watch?v=ZKyBpG97Y-0

A wearable form factor will provide the deaf with optimum convenience while walking around and communicating with non-deaf individuals.
-  This is a more convenient solution, as opposed to deaf persons regularly taking out their smartphones while walking around just to know what others are saying;
-  This is also a much safer solution because they won't be required to take out their smartphones each time they need to ask questions or talk to random strangers, especially in certain neighborhoods here in Metro Manila where violent crooks are out to steal expensive smartphones from random passersby (my blindness was caused by an incident of senseless violence); and
-  I also don't want them to hand over their smartphones to complete strangers just so the non-deaf can type what they want to say.

Right now, this translates voice input into sign language, which is shown to the user through the virtual display of a semi-transparent OLED lens.
-  More non-deaf individuals will feel comfortable talking to deaf persons when they speak and listen the way they ordinarily do;
-  My research and the experience of lots of deaf individuals indicate that many of the non-deaf can't be bothered to read and write text just to talk to the deaf while they're walking around and doing their day-to-day activities indoors and outdoors;
-  Also, many deaf persons are uncomfortable reading voluminous text during lengthy conversations with the non-deaf;
-  So instead, lots of them prefer sign language over reading text; and
-  But they are quite familiar in writing text when communicating with non-deaf persons.

I used the Microsoft CIS Speech API for speech-to-text conversion; and
-  Meanwhile, I used a custom script to convert text into finger-spelled ASL (American Sign Language).

Though of course, many deaf persons still prefer using sign language to converse with others (including the non-deaf).
-  And this is why I'm still working on offline ASL gesture detection and recognition;
-  This will use the camera of these eyeglasses to detect, recognize and convert the user's ASL gestures into spoken audio for the other person to hear;
-  So I'll continue to fine-tune a Mask RCNN model for this;
-  I'll further optimize the hardware components and software features of my project;
-  I also aim to support other sign languages aside from ASL; and
-  Remote manual interpreting assistance through professional interpreters, volunteers and the deaf person's own peers, anywhere in the world, will be done through Skype's video calling feature.

Also, this live video demo shows a very raw, very preliminary prototype:  https://www.youtube.com/tv#/watch?v=dZ9ARrobKMs
-  The first part of the live video demo is a custom voice-cloning Tagalog (Filipino text-to-speech AI model;
-  Using just 5 minutes worth of raw audio recordings taken from Youtube as training data, this AI model learned to synthesize previously unseen text inputs as the voice of Ted Failon, a popular TV news broadcaster here in the Philippines; and
-  The latter part of this live video demo shows a fine-tuned object recognition AI model trained on ASL finger-spelled alphabet gestures.
