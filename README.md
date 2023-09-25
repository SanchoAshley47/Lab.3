+import java.until. Scanner

class Main{
public static void main[] args) { Strings

// Get the users input
Scannrt in = new scanner ( system in)
System out.print (Enter rock,papers , or scissors
String my Move= in.n nextLine():

//Verify that mymOVE is valid
if InMy.equals("rock") && ! myMove.equals("paper") ! myMove.equals("scissors")
System 3)
}
}


//Randomly generate opponents move( 0,1,2 )
int rand= (int) (Math.Random)() *3
String opponent Move;
if (rand==;
opponentMove= " rock"
) else if (rand== 1){
oppointentMove= "scissors"
opponentMove= " paper"
}else(
opponentMove = " scissors"
}
System.out.printIn("Opponent move:"
