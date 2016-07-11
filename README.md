import UIKit

var numeros = 0...100


var b = "Bingo!!!"

var v = "Viva Swift!!!"

var p = "par!!!"

var i = "impar!!!"

var n = "nulo"

for m in numeros{

    switch m {

    case 0:

        print("\(m)\t\(n)")

    case 30,31,32,33,34,35,36,37,38,39,40:

        print("\(m)\t\(v)")

    case 5,10,15,20,25,30,35,40,45,50,55,60,65,70,75,80,85,90,95,100:

        print("\(m)\t\(b)")

    case 2,4,6,8,10,12,14,16,18,20,22,24,26,28,30,32,34,36,38,40,42,44,46,48,50,52,54,56,58,60,62,64,66,68,70,72,74,76,78,80,82,84,86,88,90,92,94,96,98,100:

        print("\(m)\t\(p)")

    default:

        print("\(m)\t\(i)")

    }

}
