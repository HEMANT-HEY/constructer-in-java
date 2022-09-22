# constructer-in-java 
// constructer.
class Hourse {
    String name;
    int speed;
  Hourse(String name, int speed){
      this.name= name;
      this.speed=speed;
  }
  public void Display (){
   System.out.println(this.name);
   Systemo.out.println(this.speed);
  }
  public static void main (String [] args){
      Hourse sc = new Hourse("raja",250);
      Hourse sc1=new Hourse("jecky",300);
      sc.Display();
      sc1.Display();
  }
}
