# Maven-Phases


Three phases /Tasks :
1. clean
2. build (default)
3. site

If we specify any goal, maven will execute all the previous goals under same phase. (check the arrow option in the below image)

plugin:goal

examples : maven build .. > specify goals : 



clean --> delete all the files under target folder from previous build
compile  --> it will execute goal compile : compile that will compile only src/main.java files
site --> mainly used for documentation and websites 

m1 : clean test 
m1 : clean package site

<img src="https://cgunturme.files.wordpress.com/2020/05/mavenlifecycles.png" />
