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
