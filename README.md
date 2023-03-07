fun main() {
    val limit = 100 // Change this to whatever limit you want
    var a = 0
    var b = 1
    
    println("Fibonacci sequence up to $limit:")
    
    while (a <= limit) {
        print("$a ")
        val sum = a + b
        a = b
        b = sum
    }
}
