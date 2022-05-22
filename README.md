# homework1.4
package com.company; private static Boss boss; public static void main(String[]args){

createHeroes();
for (int i = 0;i < createHeroes().length;i++) {

    Sistem.out.println("Heroes :' + createHeroes()[i] + createHeroes()[i].getHeroDamage() + " " + createHeroes()[i].getHeroHealth() + " "
     + createHeroes()[i].getHeroAttackType());

}
 Sistem.out.println("Boss");
boss = new Boss(400, 30,"Магическая защита");
Sistem.out.println("Health :" + boss.getBossHealth() + "\nDamage : + boss.get.BossDamage"()
+ " \nDafensetype:" + boss.getBossDefenseType());


}
public static void medicHill() { for (int i = 0; i < 1; i++) { Random random = new Random(); int randomHill = random.new Random(); int randomHill = random.nextInt(70); int randomHero = random.nextInt(2); int[] heroesHealth; if (heroesHealth[i] > 0 && heroesHealth[3]> 0 && heroesHealth[i] < 100) { heroesHealth [randomHero] = heroesHealth [randomHero] + randomHill; System.out.println("Медик вылечил" + randomHill); }

    }



}
}

  public static void golemDefence() {
  for (int i = 0; < heroesHealth.length;i++) {
  if (heroesHealth [7] > 0 && heroesHealth[i] > 0 && heroesHealth[7] != heroesHealth[i]){
     heroesHealth[i] += bossDamage/5;
     heroeshealth[7] -=bossDamage/5;
    }
    }
    }

    public static void shooter () {
    Random random = new Random();
    int randomShooter = random.nextInt(4) + 1;
    switch (randomShooter) {
    case 1:
       case 2:
          case 3:
    heroesHealth[6] = heroesHealth[6] + bossDamege
    }
    }

    public static void stun(){
Random random = new Random();
boolean stun = random.nextBoolean();
if ( stun ) {
    bossDamage = 0;
    Sitem.out.println("босс оглушен");
 } else {
    bossDamage = 50;

    }


    }
    public static void berserkShoot () {
Random random =  new Randow();
int randomDamage = random.nextint(15) + 1;
int randomC = random.nextint(3) + 1;
if (heroesHealth[4] > 0 && bossHealth > 0) {
    switch (randomC) {
        case 1;
        heroesDamage[4] = (heroesDamage[4] + bossDamage) - randomDamage;
        Sistem.out.println("Берсерка урон критический");
       Sistem.out.println("Потери при увлечение урон а Берсерка"  + randomDamage);
       break;
       case 2:
           bossDamage = 50;
           case 3;
           bossDamage = 50;
        break:


    }
    }
    }
