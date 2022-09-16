# calculo-de-nota

package principal;

public class principal {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
    int [] aluno = new int [24];
	int eduardo[] = {35,63,61};
    int murilo[] = {64,97,36};
    int guilerme[] = {68,74,51};
    int Flavia [] = {66,98,62};
    int Ruam [] = {80,65,41};
    int Arnaldo[] = {83,68,77};
    int Lucas [] = {38,53,80};
    int Fabio []= {53,96,89};
    int Alisson []= {45,61,68};
    int Felipe []= {32,41,85};
    int Rachel[]= {4,66,39};
    int Joul[]= {42,93,57};
    int François[]= {59,87,89};
    int Dâmaris[]= {44,50,62};
    int Leonardo[]= {83,92,32};
    int Guilerme2[]= {36,38,76};
    int Wesley[]= {41,52,87};
    int Yuri[]= {87,75,50};
    int Kira[]= {36,46,48};
    int Cleici[]= {91,88,92};
    int JoãoMoacir[]= {38,90,98};
    int Bruno[]= {96,37,100};
    int Elcio[]= {73,71,75};
    int Criscia[]= {50,95,84};
    
    

 System.out.println("--------------");
 System.out.println(" as notas p1 ,p2 e p3 do Eduardo sao:");
 for (int elemento2 : eduardo )  {
	 System.out.println(elemento2);
 }
 int total =0;
for(int i=0;i<eduardo.length;i++){
	total += eduardo[i];
}

System.out.println("total " +total);
System.out.println("a media do Eduardo e " +total/3);


 if((total/3)<70)
	 
 	 System.out.println("Aprovado");
 else {
	 System.out.println("reprovado");
 }
	
 System.out.println("-----------------------------------------------------------");
 System.out.println(" as notas p1 ,p2 e p3 do Murilo sao:");
 for (int elemento2 : murilo )  {
	 System.out.println(elemento2);
 }
 int total2 =0;
for(int i=0;i<murilo.length;i++){
	total2 += murilo[i];
}

System.out.println("total " +total2);
System.out.println("a media do Murilo e " +total2/3);


 if((total2/3)<70)
	 System.out.println("Aprovado");
 else {
	 System.out.println("reprovado");
	}
 
 System.out.println("-----------------------------------------------------------");
 System.out.println(" as notas p1 ,p2 e p3 do guilerme sao:");
 for (int elemento2 : guilerme )  {
	 System.out.println(elemento2);
 }
 int total3 =0;
for(int i=0;i<guilerme.length;i++){
	total3 += guilerme[i];
}

System.out.println("total " +total3);
System.out.println("a media do guilerme e " +total3/3);
int faltaguilerme = 8;
float calcfalta = 8/60*100;
System.out.println("falta " +faltaguilerme);
System.out.println(calcfalta);

 if((total3/3)<70) {
	 System.out.println("Aprovado");}
  
 else {
	 System.out.println("reprovado");
	}
 
	}
}



	



   








