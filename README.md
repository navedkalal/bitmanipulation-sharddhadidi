# bitmanipulation-sharddhadidi

import java.util.*;



public class cwh_59 {

    public static void main(String[] args) {

        // get bit
//        int n = 5;
//        int pos = 2;
//        int bitMask= 1<<pos;
//        if(((bitMask & n) ==0)){
//            System.out.println("bit was zero");
//        }
//        else{
//            System.out.println("bit was non zero");
//        }

//        set bit
//        int n = 5;
//        int pos = 1;
//        int bitMask = 1<<pos;
//        int number = bitMask | n;
//        System.out.println(number);

//        clear bit
//        int n = 5;
//        int pos = 2;
//        int bitMask = 1<<pos;
//        int notBitmask = ~(bitMask);
//        int number = notBitmask & n;
//        System.out.println(number);

//        update bit
        Scanner sc = new Scanner(System.in);
        int oper = sc.nextInt();
        int n = 5;
        int pos = 2;
        int bitMask = 1<<pos;
        if(oper==0){
            int notBitMask = ~(bitMask);
            int number = notBitMask & n;
            System.out.println(number);
        }
        else {
            int number = bitMask | n;
            System.out.println(number);
        }
    }
}
