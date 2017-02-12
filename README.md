# Anagram_Finder_Map_Reduce_GAE

Anagram Finder is a web application that uses Google App Engine Map Reduce to find anagrams in multiple large text files. 
It has a python backend (webapp2 framework) and utilizes GAE map, shuffle, reduce mechanism to find and retrieve anagrams.
An archive consisting of more than hundred thousand words in different text files was used as sample input.

To build the library and the demo application, run the provided build script as follows from within the python sub-directory of the source tree:

./build.sh build_demo

To run the demo from your local computer:

./build.sh run_demo. .
then go to: http://localhost:8080/_ah/login
check the box that says "Sign in as Administrator" and click login.
Then if you go to: http://localhost:8080 you can interact with the  application.

Snapshots:

![screen shot 2017-02-11 at 3 45 27 pm](https://cloud.githubusercontent.com/assets/14020237/22866730/f2fafd74-f12f-11e6-9295-747bc1b2f085.png)

![screen shot 2017-02-11 at 3 47 23 pm](https://cloud.githubusercontent.com/assets/14020237/22866731/fac359e8-f12f-11e6-9575-b3dce78a9cc2.png)


![screen shot 2017-02-11 at 3 50 04 pm](https://cloud.githubusercontent.com/assets/14020237/22866733/ffcaf432-f12f-11e6-9846-4a29ac54a7bb.png)

![screen shot 2017-02-11 at 3 47 49 pm](https://cloud.githubusercontent.com/assets/14020237/22866739/0ad131de-f130-11e6-8c53-b489839f27f3.png)
