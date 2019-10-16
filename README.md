public class Conta {

	int v1 = 10;
	int v2 = 4;
	int v3 = 15;

	if (v1 == v2){
	    System.out.println("O valor 1 é igual ao valor 2");
		}
	    if (v1 == v3){
	    System.out.println("O valor 1 é igual ao valor 3");
	    }
	    if (v2 == v3){
	    System.out.println("O valor 2 é igual ao valor 3");
	    }

	    if (v1 > v2 || v1 < v2 ) {
	    if (v1 > v3 && v1 > v2) {
	        System.out.println(v1 + " é maior que "+ v2 +", "+ v3);
	    }
	    if (v1 < v3 && v1 < v2) {
	        System.out.println(v1 + " é menor que "+ v2 +", "+ v3);
	    }
		}
	    if (v2 > v1 || v2 < v1) {
	    if (v2 > v3 && v2 > v1) {
	        System.out.println(v2 + " é maior que "+ v1 +", "+ v3);
	    }
	    if (v2 < v3 && v2 < v1) {
	        System.out.println(v2 + " é menor que "+ v1 +", "+ v3);
	    }
		}
	    if (v3 > v1 || v3 < v1) {
	    if (v3 > v2 && v3 > v1) {
	        System.out.println(v3 + " é maior que "+ v1 +", "+ v2);
    	}
	    if (v3 < v2 && v3 < v1) {
			System.out.println(v3 + " é menor que "+ v1 +", "+ v2);
		}
	}
