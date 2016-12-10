
//: Playground - noun: a place where people can play

import UIKit


var rango = 0...100

for i in 0 ..< rango.count{
    
    var divisible = i % 5
    
    if divisible == 0 {
        
        print("\(i)\t\("Bingo!!!")")
    }
    var par = i % 2
    
    if par == 0 {
        
        print("\(i)\t\("es par!!!")")
        
    } else {
        
        print("\(i)\t\("es impar!!!")")
        
    }
    
    switch i {
        
    case 30 ... 40: print("\(i)\t\("Viva Swift!!!")")
    default: ()
        
        
    }
    
}
