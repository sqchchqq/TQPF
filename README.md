TQPF Application Note

1.Whether Windows or Linux, make sure your computer is installed JRE (Java SE Runtime Environment) properly and configure the CLASSPATH environment variables successfully. (Download JRE: http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html )

2. For Windows version, in order to double-click to execute TQPF.jar, find the JAVA installed file like “C:\Program Files\Java\jre7\bin\javaw.exe”, and set javaw.exe as the default open app for TQPF. If can’t open with double-click now, the content of“HKEY_CLASSES_ROOT\Applications\javaw.exe\shell\open\command”in Registry Editor need to add the parameter “-jar”, like "C:\Program Files\Java\jre7\bin\javaw.exe" -jar "%1".

3. Download and Double click TQPF.jar, the following Frame in Fig 1 will show up. There are two Panels in TQPF, “Pattern Finder” and “CS scanner”. 

4. Using “CS scanner” for genome location information of target_Seq or off-target, reference base must be established like in the ReferenceBase_package.zip. Download site: https://pan.baidu.com/s/1i6WNRwT.

5. Widget AnnotationThe long blank text field: must input the Capital Letters representing nucleotides.The short blank text field: must input the positive Integer.Be attention to two kinds of selection button, file selection and file directory selection.
“Question mark”：Key tips will display when the cursor lingers over this component. "hexagon": This tag will turn from red to green when File or File Directory is selected successfully. And green will turn back to red when selection is failed.The “Loading parameters!” tag will turn to “Running…” when the “Get Result” is executing, and will turn to the Location of the result when the job is done.

6. For the Linux version, TQPF has divided to three modules: "PatternFinder", "CSscanner", "OneStepAnalysis". Each module has a head file named: PatternFinder.java, CS_scanner.java, and OneStepAnalysis.java. When using it, all parameters and file path need to fill in the head file correctly. Then compile and execute the head file, like "javac PatternFinder.java" and then "java PatternFinder".
