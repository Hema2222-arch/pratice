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
