# sessionNine-Assignment-1-


1. Implement an intersection of the below list
List ((1, "panda"), (2, "happy"))
List ((2, "pandas")
 
val inputA = sc.parallelize(List((1,”panda”),(2,”happy”)))

val inputB = sc.parallelize(List((2,”pandas”)))

val output = inputA.cogroup(inputB)

output.collect()

