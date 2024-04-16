pipeline
{
    agent any
    stages
    {
        stage("Mostrar numeros")
        {
            steps
            {
                script
                {
                    num1= 100
                    num2= 1000
                    println "El numero 1 es " + num1
                    println "El numero 2 es " + num2

                    mapa= [1: "Lunes", 2:"Martes", 3: "Miercoles", 4:"Jueves", 5:"Viernes", 6: "Sabado", 7:"Domingo"]
                    println "El dia actual es: " + mapa[dia]
                }
            }
        }
        stage("Suma")
        {
            steps
            {
                script
                {
                    num1= 100
                    num2= 1000
                    suma == num1 + num2
                    println "La suma es " + suma
                }
            }
        }
        stage("Resta")
        {
            steps
            {
                script
                {
                    resta == num1 + num2
                    println "La resta es " + resta
                }
            }
        }
        stage("Producto")
        {
            steps
            {
                script
                {
                    producto == num1 * num2
                    println "El producto es " + producto
                }
            }
        }
        stage("Division")
        {
            steps
            {
                script
                {
                    if(num2 != 0)
                    {
                        division = num1 / num2
                        prinln "La division es: " + division
                    }
                    else
                    {
                        prinln("no se puede dividir entre cero")
                    }
                    
                }
            }
        }
    }
}
