## kt native  
`kotlinc-native test1.kt`  
`Measure-Command {.\program.exe 18}`
## jvm  
`kotlinc-jvm test1.kt -include-runtime -d test1.jar`  
`Measure-Command {java -jar test1.jar 18}`
