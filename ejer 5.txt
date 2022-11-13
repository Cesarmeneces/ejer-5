class Main {
  public static void main(String[] args) {
int [][] matriz = {{2,4,4},{6,6,9},{8,10,12}};
int matriz[][] = new int[3][3];
for (int x=0; x < matriz.length; x++) {
  for (int y=0; y < matriz[x].length; y++) {...}
}
Scanner consola = new Scanner(System.in);
for (int x=0; x < matriz.length; x++) {
  for (int y=0; y < matriz[x].length; y++) {
    System.out.println("Introduzca el elemento [" + x + "," + y + "]");
    matriz[x][y] = consola.nextInt();
  }
}
for (int x=0; x < matriz.length; x++) {
  for (int y=0; y < matriz[x].length; y++) {
    System.out.println ("[" + x + "," + y + "] = " + matriz[x][y]);
  }
}