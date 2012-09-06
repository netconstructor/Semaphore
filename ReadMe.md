# Semafore : shallow semantic parser

Having Semafore running seems quite complicated; hence I'm explaing what I have done so far stepwise.
The first step is having the required files downloaded and untared:

   1- [Semafore V.2.1],(http://semafor-semantic-parser.googlecode.com/files/SEMAFOR-2.1.tgz)
   2- [stacked parser](http://semafor-semantic-parser.googlecode.com/files/stackedParserServer.tgz)
   3- [models](http://www.ark.cs.cmu.edu/SEMAFOR/SEMAFOR-2.1-models.tgz)
   
Once all these are pasted into 1 folder, there is one [file],(https://github.com/kimiaprojects/Semaphore/blob/master/semafor-semantic-parser/release/config) to be modified.
Environment variables must set manually such as *SEMAFOR_HOME*, *MST_PARSER_HOME*, *MST_MACHINE*, *JAVA_HOME_BIN*, *MODEL_DIR*.
