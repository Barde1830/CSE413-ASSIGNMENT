fun main() { 
val multiply: (Int, Int) -> Int = { a, b -> a * b }
    
    println("Product of 5 and 3: ${multiply(5, 3)}")

    println("Product of 10 and 20: ${multiply(10, 20)}")
}