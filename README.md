# gradle-composite-module-multi-repository
Gradle example multiple module in different repository

## Example a composite buld

Start this example downloading next repositoires:
    
#### Clone using git
    
    git clone https://github.com/angel-94/gradle-core
    git clone https://github.com/angel-94/gradle-models

#### Build project

    cd gradle-core
    gradle build
    gradle bootRun

#### For quickly start, after you clone all repositoires you can run the next command in the directory  *gradle-composite-core-models*

    gradle bootRun

#### Test the App
> http://localhost:8080/v1/core/person

> http://localhost:8080/v1/core/animal


## References
- [Gradle Composite](https://docs.gradle.org/current/userguide/composite_builds.html#defining_composite_builds)

- [Issue Composite Build Fixed](https://discuss.gradle.org/t/composite-build/29684)