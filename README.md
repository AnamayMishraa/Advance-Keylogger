## Invisilogger:Advance Keylogger

<b>Disclaimer: This keylogger script is intended for educational purposes only and should not be used for any malicious or unauthorized activities.</b>

This tool is a keylogger script written in Python, designed for educational purposes and cybersecurity research. A keylogger, or keystroke logger, is a type of software or hardware device that records every keystroke made on a keyboard. While keyloggers can be used for legitimate purposes such as monitoring employee activity or gathering input data for user interface improvements, they are often associated with malicious activities.

Keyloggers are commonly used by hackers to capture sensitive information such as usernames, passwords, and credit card details. Once installed on a victim's computer, a keylogger operates silently in the background, recording keystrokes and transmitting the data to the attacker. This type of attack can lead to severe privacy breaches and financial losses. It is crucial to understand how keyloggers work to develop effective countermeasures and enhance cybersecurity defenses..


### Built With<br> [![My Skills](https://skillicons.dev/icons?i=py)](https://skillicons.dev)
This keylogger script is developed using Python, a versatile and widely-used programming language known for its simplicity and readability. 

Several Python libraries are utilized to implement the keylogging functionality and handle other essential tasks:
<ul>
<li><b>pynput:</b> This library is used to capture and monitor keyboard inputs. It provides a convenient way to listen to and record keystrokes.</li>
<li><b>email:</b> This library is used to construct and send email messages. It enables the keylogger to send captured keystroke data to a specified email address.</li>
<li><b>threading:</b> This library is used to manage multiple threads, allowing the keylogger to perform tasks such as logging keystrokes and sending emails concurrently.</li>
<li><b>os:</b> This library provides a way to interact with the operating system, enabling functionalities like file handling and system operations.</li>
<li><b>time:</b> This library is used to manage timing operations, such as scheduling when to send logged data.</li>
<li><b>MIME </b>(Multipurpose Internet Mail Extensions): This is a standard that extends the format of email to support text in character sets other than ASCII, as well as attachments of audio, video, images, and application programs. It is used to format the email content properly when sending logs.</li>
</ul>

## Getting Started

This section will guide you through using the keylogger script for educational and research purposes. Follow the instructions below to get started with both the Python script and the executable version.

<b>A. Using the Python Script</b><br>
<ul>
<li><b>Download the Script:</b> Download the main.py file to your local machine. You can clone the repository or download the file directly from your source.<br></li>
 <i>https://github.com/AnamayMishraa/Advance-Keylogger</i>
<li><b>Install Python:</b> Ensure you have Python installed on your system. You can download Python from https://www.python.org.<br></li>
<li><b>Install Required Libraries:</b> Open a terminal or command prompt and navigate to the directory where <i>main.py</i> is located.Install the necessary libraries using pip:<br></li>
  <ul>
    <li>pip install pynput</li>
    <li>pip install email</li>
    <li>pip install threading</li>
    <li>pip install os</li>
    <li>pip install time</li>
  </ul>
</ul>

<b>B. Using the Executable Version
</b><br>
<ul>
<li><b>Download the keylogger.rar:</b> Unzip and you will find the executable file in the dist directory. The executable file is typically named main.exe.<br></li>
<li><b>Run the Executable:</b>Simply double-click the main.exe file to run it.<br>
<b>
 The keystrokes will be stored in a .txt file named : <i>keyx.txt</i><br>
 The keylogger will start running in the background without opening a console window.</b>

</ul>




<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!




<!-- LICENSE
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.
!-->



<!-- CONTACT -->
## Contact

Linkedin - [Anamay Mishra](https://www.linkedin.com/in/anamay-mishra/) <br>
Email - anamaymishra26@gmail.com

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [CyberAcademy](https://cybercademy.org/build-advanced-keylogger-in-python-project-overview/)
* [Grant Collins/Youtube](https://www.youtube.com/watch?v=25um032xgrw)



