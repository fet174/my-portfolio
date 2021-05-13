# Issue
Not Collecting data from 4xx Errors, 5xx Errors and Disc Utilization.
# Symptoms
Not Collecting data from 4xx Errors, 5xx Errors and Disc Utilization.
![Error](https://user-images.githubusercontent.com/59581555/118171061-e0389d00-b3f8-11eb-8df5-0e2997aaf7dd.png)

# Resolution
1. Check configuration for Dashboard: (Setting >> Variables >> Show usages) ![Settings](https://user-images.githubusercontent.com/59581555/118171187-11b16880-b3f9-11eb-96aa-f3a759f650ed.png)
![Var](https://user-images.githubusercontent.com/59581555/118171200-170eb300-b3f9-11eb-9730-54459d6f6e2d.png)


2. Check what part of path is missing.![Path](https://user-images.githubusercontent.com/59581555/118171233-1fff8480-b3f9-11eb-84f2-11ab1bff6dbd.png)


3.1 Go to Edit.
3.2 Change configuration settings (can be copied from correct settings)
3.3 Press "Apply" after complete.
3.4 In case if Grafana running on the docker container, Export new configuration
    file for dashboard replace instead the old one.



