# pratice
//Prime Number
class main{
    public static void main(String[] args){
        int num = 7;
        for(int i = 2;i<num;i++){
            if(num%i==0){
                System.out.println("Not prime");
                return;
            }
        }
        System.out.println("Prime");
    }
}
//SQUARE NUMBER:
class Main {
    public static void main(String[] args) {
        int num = 2;
        int power = 2;
        int result = 1;
        for(int i = 1;i<=power;i++){
            result = result * num;
        }
        System.out.println(result);
    }
}
