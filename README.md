# Convert .py to .apk

This program will convert .py file to .apk file.

### Steps to follow :-

There are some steps you need to folllow to execute your programme - 

* Open <a href="https://colab.research.google.com/">Google Colab</a>.

* Execute the <a href="./code.ipynb">code.ipnyb</a> code as given.

* After run the line -
  ```py
  !buildozer init
  ```
  in <a href="https://colab.research.google.com/">Google Colab</a>, there will be generate the <a href="./buildozer.spec">buildozer.spec</a> file.

* At `line no. 40` paste the following - 
  ```py
  requirements = python3,kivy==2.0.0,kivymd,pillow
  ```

* After run the line -
  ```py
  !buildozer - v android debug
  ```
  in the `bin` folder of <a href="https://colab.research.google.com/">Google Colab</a>, there will be generate the <a href="./myapp-0.1-arm64-v8a_armeabi-v7a-debug.apk">myapp-0.1-arm64-v8a_armeabi-v7a-debug.apk</a> file.

* After download it in your local machine and install it, you will be able to run the application in your mobile.

DISCLAMER :- Your programme may take some time to execute.

Made with by ❤️ & ☕ by ***Debargha Mitra Roy***