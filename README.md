
package study;ㅈㅇㅇㅇㅁㄴㅇㅁㄴㅇㅁㄴㅇㅁㄴㅇㄴㅁㅇㅁㄴㅇㅁㄴㅇㅁㄴ
ㅁㅇㅁㄴㅇㅁㄴ
import java.util.Scanner;ㅇㅁㄴㅇㅁㄴ

public class Main {ㅇㅁㄴㅇㄴㅁㅇㅁ

	public static void main(String[] args) {ㅇㅁㄴㅇㅁㄴㅇㅁㄴ
		Scanner scanner = new Scanner(System.in);
		
        System.out.println("제품을 선택하시오.");
        System.out.println("1.Television 2. Radio");
        System.out.print("select: ");
        int productChoice = scanner.nextInt();

        Product selecteProduct;

        if (productChoice == 1) {
            selecteProduct = new Television();
            System.out.println("Television의 채널을 선택하시오. 1.KBS 2.MBC 3.SBS");
            System.out.println("1.KBS 2.MBC 3.SBS");
            System.out.print("select: ");
            int selecteChannel = scanner.nextInt();
            selecteProduct.changeChannel(selecteChannel);
            
        } else if (productChoice == 2) {
            selecteProduct = new Radio();
            System.out.println("Radio의 채널을 선택하시오.");
            System.out.println("1.107.7 MHz 2.98.1 MHz 3.104.5 MHz");
            System.out.print("selet: ");
            int selecteChannel = scanner.nextInt();
            selecteProduct.changeChannel(selecteChannel);  
            
        } else if(productChoice == 3) {
        	System.out.println("현재 시청하는 TV 채널은 " + 1);
        }
	}
}
