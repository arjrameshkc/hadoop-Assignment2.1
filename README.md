# hadoop-Assignment2.1

 hadoop fs -ls
 hadoop fs -test -d /user/acadgild/hadoop
 hadoop fs -mkdir  -f /user/acadgild/hadoop/Word-count.txt
echo "1,ramesh,software,2500" | hadoop fs -appendToFile - /user/acadgild/hadoop/Word-count.txt
