public class Dice {
 public static voidpublic class Dice {
 public static void main(String args[]) {
  
  Dice Object= new Dice();
  System.out.println(Object.RollDice(2));
  
 }
  
  
  
 public int RollDice(int NumOfDice) {
  
  //number of dices
  
  return (1*NumOfDice + (int) (Math.random() * 6*NumOfDice));

 }
 static int Roll_1_Dice() {
  return 1 + (int) (Math.random() * 6);
 }
} main(String args[]) {
  
  Dice Object= new Dice();
  System.out.println(Object.RollDice(2));
  
 }
  
  
  
 public int RollDice(int NumOfDice) {
  
  //number of dices
  
  return (1*NumOfDice + (int) (Math.random() * 6*NumOfDice));

 }
 static int Roll_1_Dice() {
  return 1 + (int) (Math.random() * 6);
 }
}
