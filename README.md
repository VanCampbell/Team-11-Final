package horseCalc;

public class MainCalc {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
GrandMother TC= new GrandMother(); 
TC.setname("A Tempting Chick");
TC.setspeedIndex(99);

Mother DC= new Mother();
DC.setname("A First Down Chick");//all methods currently overloaded from the super g/mother
DC.setspeedIndex(94);

Offspring BE=new Offspring();
BE.setname("Sheza Beautiful Eagle");
BE.setpSpeedIndex((DC.getspeedIndex()+ TC.getspeedIndex())/2);//averages the two SI from g&mother

		

		System.out.println("horse name" + TC.getname() );
		System.out.println("Speed index" + TC.getspeedIndex());
		
		
		System.out.println("momma horse name" + DC.getname());
		System.out.println("moma SI" + DC.getspeedIndex());
		
		System.out.println("offspring name" + BE.getname());
		System.out.println("offspring SI" + BE.getpSpeedIndex());
	}

}
