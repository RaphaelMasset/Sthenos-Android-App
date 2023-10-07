# Random abs workout
#### Video Demo:  https://www.youtube.com/watch?v=l74-zjqiff8
#### Description:

## App functionning

This app display a new randomized abs exercise picture each time you click on the NEXT button.
    Click on the “NEXT” button to begin.
    Try to do as many reps/hold time as possible.
    After trying hard for 40s take 20s rest (the timer turn green).
    Click on Next as much as you want (It is advised to do at least 5 exercices).                             

Click on Tools to display some tools
    The first graph display the corresponding rep and set for each intensity range.
    The second graph show what range of set develop what physical characteristics.
    The last tool give your theorical maximal weight limit with 5% bodyfat, using your height in centimeter.

## File content
In android studio most of the project file are generated automatically at the start of a new project and some of them are updated automatically too.

.gradle: the build system that make all the files runnable, this folder don't have to be modified.
.idea: this folder store settings about the created app and my android studio setting. Same as before a developper don't have to touch this file.
.app: this folder is the important one, it is the android app module, it contain all code and the ressources.
    build: app building files, contain results of the build. In the apk>debug folder you have the build apk app ready to be deployed.
    libs: for private dependencies
    src: contain all the sourcecode.
        androidTest: where you write instrumentation test code to test user interface.
        main: all the sources codes and ressources
            **java: Contains the Kotlin application source code files, separated by package names.**
                com.exemple.sthenos:
                    ui.theme:
                        MainActivity.kt: Contain most of my work. Here is the code for the main activity of the app. It contain the code for the randomized abs exercises.
                        SecondActivity.kt: Contain the second activity of my app, the second page with the graphs and the little calculation tool.
            **res: ressources folder, contains all non-code resources, such as XML layouts, UI strings, and bitmap images, divided into corresponding subdirectories. Here is the string I use in my app, the abs exercices in format png, the background and the app icon**
            AndroidManifest.XML: this a link between the developper and the system. It let the devlopper define what the app is gonna do, what activity it has, what permission it should have. 
        test [unitTest: where you can run our unit test code to test main folder code.
    .gitignore: version control system to go back in time. It track changes of files over time for the module level.
    build.gradle: module level/app level build gradle. It contain build configuration for when the build system come to that module.
    proguard-rules.pro: this fi contain rules for ProGuard software. It make app smaller and faster.
gradle: another gradle folder but different. Store the gradle whapper.jar. A developper should rarely touch his content.
.gitignore: version control system to go back in time. It track changes of files over time.
build.gradle: another build.gradle than the one in the app folder. It contain build configuration that are inherited in the others modules.
gradle.properties: the properties of the java process that build the project.
gradlew: a script, contain how every gradle task should be run.
gradlew.bat: windows runnable version of the gradlew.
local.properties:where you configure local environment properties on your build system.
settings.gradle: this file tales gradle which module should be included in the build. Here it tell the .app should be included.



