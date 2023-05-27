# indiceLiquidezSeca
Em finanças, a liquidez geral é o cálculo que representa a saúde financeira de uma empresa a longo prazo, por isso tem resultados bem diferentes da liquidez corrente.

```
public class indiceLiquidezSeca {
	public static void main(String[] args) {
		double ativoCirculante = 21190000;
		double passivoCirculante = 17503000;
		double estoques = 518000;

		double liquidezSeca;

		liquidezSeca = (ativoCirculante - estoques)	/ passivoCirculante;

		System.out.println("O índice calculado em liquidez Seca é?  " + 
				liquidezSeca);
	}

}
