# Dicee
ios Application based on dicee game. programmatically change the  2 image views and i use arrays to make functions.and i use 6 image in Assets File. i use Array String type for the 6 image in class ViewController
 arrayImageName = ["ball1","ball2","ball3","ball4","ball5"] . and i have a button in View whene button pressed it give me a random image by useing  randomBallNumber = Int(arc4random_uniform(6))
        imageView.image = UIImage(named: arrayImageName[randomBallNumber])
        
 
