
fun main() {

    println("Hello, Umar!")

}


fun main() {
    print("Enter your name: ")
    val name = readLine() ?: ""
    
    print("Enter your age: ")
    val age = readLine()?.toIntOrNull() ?: 0
    
    println("Hello $name, you are $age years old!")
}