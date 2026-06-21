<br>
<div align="center">
    <a href="https://github.com/itsmeSamrat" target="_blank">
        <img src="https://github.com/itsmeSamrat/Face-Recognition-System-for-Student-Attendance/blob/main/misc/app.png?raw=true" 
        alt="Logo" width="500" height="350">
    </a>
</div>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=1500&pause=200&center=true&vCenter=true&multiline=true&width=435&height=100&lines=Face+Recognition+System+;for+Student+Attendance">
</div>

<h2 align="center"> Effortlessly track student attendance with reliable Face Recognition System. </h2>

## Description

Hello, everyone. This is our central repository for the Robotic Science Club (RCS Club), housing our core projects involving Arduino firmware, Flask web dashboards, and Gemini AI integrations. We have tried to keep all the resources, circuit diagrams, and code modules in place and organized correctly, as per our knowledge. It was challenging to figure out every hardware component and make them work seamlessly together with software, but looking into Stackoverflow, GitHub, and technical documentation, our team was able to piece them all together. We have provided links to some amazing tutorials and open-source documentation, which helped us get these club projects done in the acknowledgement section.

Also, one limitation of our current setup is the real-time data sync with hardware via Flask routes is not fully encrypted, meaning sensor streams could theoretically be intercepted locally. We tried different approaches like implementing WebSocket authentication and trying lightweight cryptography on Arduino, but being our first integrated club project, there was not good initial architecture planning. In the upcoming robotics and IoT projects, we will keep that in mind. And if anybody can help us out with this hardware-to-software security problem, please feel free to contact me in the email address below, would really appreciate it. Thank you.


[getting started](#getting-started)

## Getting Started

- Start by cloning the repository into your local machine. Use the following command in your terminal:

```bash
```

- Next, install all the necessary modules and dependencies listed in the requirement.txt file. Keep in mind that some modules might be missing, which could result in an error.
- Proceed to set up your Firebase database. Download the required credentials from Firebase and save them as **serviceAccountKey.json** .
- Locate the **initial_database.py** file in the misc directory. Open it and find the designated section to paste your database URL. If your setup and credentials are correct, the script will add the data to the database.
- Once you've created the database, run the **initial_encoding.py** Python file. Ensure that you've placed the image file in the **static/Files/Image** directory and named it with the corresponding user ID from the database. This allows us to associate user images with their unique identification numbers. Additionally, this encoding step will generate a pickle file used for the face recognition model.
- With the previous steps completed, execute the **webapp.py** script. If all the credentials and dependencies are correctly set up, the web application should start running. You can refer to the for a visual representation.
- Lastly, show your support by giving the repository a star! 🙂😁

Thank you. ✌✌

## License

This project is under MIT License - see the [License.txt](https://github.com/itsmeSamrat/Face-Recognition-System-for-Student-Attendance/blob/main/license.txt) file for more details.

## Feedback

- If you notice any mistake or can make it better. Feel free to open a pull request and correct it or email me on the below email id.

## Contact Me 📨

Email : [mahodibilla106@gmail.com](mailto:mahodibilla106@gmail.com)

<!-- Back to the top -->

[Return Back to Top ⬆️](#getting-started)
