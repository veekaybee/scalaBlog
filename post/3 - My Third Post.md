And sometimes you want to include code

````scala
// Simple Map example 

val donuts1: Seq[String] = Seq("Plain", "Strawberry", "Glazed")
val donuts2: Seq[String] = donuts1.map(_ + " Donut")

println(s"Elements of donuts2 = $donuts2")

val dogs: Seq[String] = Seq("beagle","Collie")
val dogs2: Seq[String] = dogs.map(_*2)
val dogs3: Seq[String] = dogs.map{p => p*2}

println(s"Elements of dogs = $dogs2")

```