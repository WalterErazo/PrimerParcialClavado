# Primer Parcial Programación Avanzada 
### Codigo

## Problema Número 1: Recursividad Método Chudnovsky

### Class: Chudnovsky


public interface Chudnovsky {
	public double getrea();
	public String toString(); 

}


### Class: MetodoChudnovsky


public class MetodoChudnovsky implements Chudnovsky {
	
	

	public int N; 
	
	private int ConstantA = 0;
	private int ConstanteB = 0; 
	private int ConstanteC = 0; 
	
	
	
	public double FacChud ( double Factorial) {
		return Factorial;
		
	}

	@Override
	public int getmetodochug() {
		// TODO Auto-generated method stub
		return 0;
	}
	
	public double CalcularPiChud(int N ) {
		
		double Pi = (Factorial(6* N))*((ConstantA * N)+ ConstanteB)/ ((Factorial(3* N)))*(Math.pow(N, 3))*Math.pow((ConstanteC), N);
		return Pi;
		
	}

	private int Factorial(int N) {
		
		if(N <= 0)
			return 1;
		else 
			return (N * Factorial(N-1));

	}

}



## Problema Número 2: Tennis

public class Tennis {
	
	private static final int N = 6;



	public String[] MyList = new String[N];
	

	
	public String GanadorTennis(int JugadorA, int JugadorB) {
		if(JugadorA > JugadorB) {
			if(JugadorA > 5 ) {
				if(JugadorA < 8) {
					if(JugadorB < 5) {
						if(JugadorB > 0) {
							
							return JugadorA+ " Gano Primer Set";
						}
					}
				}
			}
		}
		if(JugadorA == 7 ) {
			if(JugadorB == 5 ) {
				if(JugadorB == 6) {
					
					return JugadorA + " Gano Primer Set";
					
				}
				else {
					return "Set No Valido"; 
				}
			}
			
			if (JugadorA >= 0 ) {
				if(JugadorA <= 5) {
					if(JugadorB >= 0) {
						if(JugadorB <= 5) {
							return "Juego Continua";
						}
						else {
							return "Set No valido";
						}
					}
				}
			}
			
			if(JugadorA > JugadorB){
				if (JugadorB > 5 )
				{
					if (JugadorB < 8) {
						if(JugadorA > 5) {
							if(JugadorA < 8) {
								return JugadorB + " gana Set";
							}
						}
					}
				}
			}
			if (JugadorB == 7) {
				if (JugadorA == 5 ) {
					if(JugadorA == 6) {
						return JugadorB + " Gana Set";
					}
				}
			}
			else {
				return "Set No Valido";
			}
			
			
		
		}
		
		
	}
	
	public String MostrarCampeon() {
		long GanadorA = 0;
		long GanadorB = 0;
		
		for(int i= 0; i <MyList.length;i++) {
			if(MyList[i] == GanadorA) {
				GanadorA++;
			}
			else (MyList[i]== GanadorB){
				GanadorB++; 
			}
			
			
		}
	}
  
  ## Problema Número 3: Power Ranger
  
  
  ### Class: WaterRanger
  public class WaterRanger extends Power{
	
	public void TipoAtaque() {
		System.out.println("Mi tipo de ataque es Agua");
	}
 }
 
 ### Class: StoneRanger
  public class StoneRanger extends Power{
	
	public void TipoAtaque() {
		System.out.println("Mi tipo de ataque es Tierra");
	}
 }
 
 ### Class: FireRanger
  public class WaterRanger extends Power{
	
	public void TipoAtaque() {
		System.out.println("Mi tipo de ataque es Fire and Ataque Quemar");
	}
 }
 
 ### Class: AirRanger
  public class AirRanger extends Power{
	
	public void TipoAtaque() {
		System.out.println("Mi tipo de ataque es Aire and Volar");
	}
 }

