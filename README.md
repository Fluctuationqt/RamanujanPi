# CalculatePi
A Java console application that calculates the number Pi using Ramanujan's formula with multi-threading for the sum calculation.

The formula used in this application is Ramanujan (2) from [here](https://keisan.casio.com/exec/system/1355104874 "Ramanujan Calculator")

## Running the application
1. Download .jar file from out/artifacts/CalculatePi_jar

2. Run command: ```java -jar CalculatePi.jar -p <precision> -t <threads> [-o <output>] [-q <quiet>]```
    * ```-p <precision>``` Indicates the number of members for the calculation.
    * ```-t <threads>``` Indicates the number of threads to use for the calculation.
    * ```-o <output>``` Indicates where the calculation will be output.
    * ```-q <quiet>``` Run program in "quiet" mode
