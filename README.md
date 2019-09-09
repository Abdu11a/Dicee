# Dicee
ios Application based on dicee game. programmatically change the  2 image views and i use arrays to make functions.and i use 6 image in Assets File. i use Array String type for the 6 image in class ViewController
diceArray = ["dice1","dice2","dice3","dice4","dice5","dice6"]. and i have a button in View whene button pressed it give me a random image by useing   randomDiceIndex1 = Int(arc4random_uniform(6))
        randomDiceIndex2 = Int(arc4random_uniform(6))
        diceImageView1.image = UIImage(named:diceArray[randomDiceIndex1])
        diceImageView2.image = UIImage(named: diceArray[
