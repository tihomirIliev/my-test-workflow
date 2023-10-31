##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0

##### SIMUALTE CHANGE SO A PULL REQUEST CAN BE POSSIBLE
    Increase value of the counter with 1
    Counter 1
    
