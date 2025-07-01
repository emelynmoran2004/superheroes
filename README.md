public class SuperheroRoster { 
    public static void main (string[] args {
        String []heroNames= {"Spiderman", "Iron Man",}"Black Widow"};
        String []{"Wed-slinging", "Flying nnand high-tech armor" , "Steath and combat"} ;
        int [] abilities={85,90,80};
        
        Superhero[] heroes= new Superhero [ heroNames.length];
        for (int i = 0; i < heroNames.length; i++)
        heroes [i]= new Superhero (heroNames[i], abilities[i], powerLevels[i);
        System.out.println("Superhero Roster:");
        for (Superhero : heroes) {
            hero.displayHero();
            System.out.println("\nSearching for 'Thor':");
            searchHero (heroNames, abillities, powerLevels, "Thor");
           
            double average= calculateAveragePower(powerLevels);
            System.out.printf("\nAverage Power Level: %. 2f\n", average);
            public static viod searchHero(String[])names. String[]
abilities, int[]powerLevels, String target)
   boolean found =false; 
   for (int i = 0;i < names.length; i++) {
    if (names[i]. equalsIgnoreCase(target)){
          System.out.println("Hero found!");
                System.out.println("Name: " + names[i]);
                System.out.println("Ability: " + abilities[i]);
                System.out.println("Power Level: " + powerLevels[i]);
                found = true;
              break;
            }
        }

        if (!found) {
            System.out.println("Hero not found.");
        }
    }
  public static double calculateAveragePower(int[] powerLevels) {
        int sum = 0;
        for (int power : powerLevels) {
            sum += power;
        }
        return (double) sum / powerLevels.length;
    }
    class Superhero {
        private String name;
    private String ability;
    private int powerLevel;
      public Superhero(String name, String ability, int powerLevel) {
        this.name = name;
        this.ability = ability;
        this.powerLevel = powerLevel;
          public void displayHero() {
        System.out.println("Name: " + name);
        System.out.println("Ability: " + ability);
        System.out.println("Power Level: " + powerLevel);
        System.out.println("------------------------");
    }
}
