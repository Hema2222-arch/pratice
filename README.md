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


//FIBONACCI SERIES:
class main{
    public static void main(String[] args){
        int N = 10;
        int num1 = 0;
        int num2 = 1;
        System.out.println(num1);
        System.out.println(num2);
        for(int i = 0;i<=N;i++){
            System.out.println(num1);
            int temp = num1+num2;
            num1=num2;
            num2 = temp;
        }
    }
}
