
# Trying out JRuby JAR

Just a simple test. Trying to prove that using JRuby can actually excecute Java code. 

This repository holds a simple Java app with some mysterious features 👻

## How to build the .jar file

On IntelliJ go to:

	File > Project Structure... > Project Settings > Artifacts > + > JAR > From modules with dependencies > ...

and then choose the class that you want to set as the main class.

The go to:

	Build > Build Artifacts > ...

and then _build_ the jar you want to create. The created .jar file will be stored on the `/out/artifacts` directory.
