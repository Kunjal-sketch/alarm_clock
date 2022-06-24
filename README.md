# alarm_clock
alarm clock using python 
1.For this project, we would be using the Playsound module. Playsound is a pure Python, cross-platform, single function module with no dependencies for playing sounds Playsound is not available by default in the Python Standard Library and has to be installed. To do this, we will use pip
**pip install playsound**
2. import the datetime module
3. we have obtained a point of time in the format of HH:MM: SS AM/PM. To compare this format of time with the system time in our computer, we need to extract the hours, minutes, seconds, and period from the above string. We achieve this using string slicing.
4. let's inform the user his alarm was set. by 
**print("Alarm Set!")**
5. The current time obtained is not in the string format. To obtain a string from a datetime object we make use of the strftime() method. Obtaining the hour, minute and seconds of current time
6. **print("Wake Up!")
playsound('/path/to/a/sound/file/you/want/to/play.mp3')**
