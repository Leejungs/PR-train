ㅁ
        System.out.println("1.Television 2. Radio");dasda
        System.out.print("select: ");
        int productChoice = scanner.nextInt();
ㅇㅁㄴㅇㅁㄴ
        Product selecteProduct;
ㅇㅁㄴㅇㅁㄴㅇㅁㄴㅇㅁㄴㅇㅁㄴㅇㅁㄴㅇㅁ
        if (productChoice == 1) ㅇㅁㄴdasdas
            selecteProduct = new Television();ㅇㅁㄴ
            System.out.println("Television의 채널을 선택하시오. 1.KBS 2.MBC 3.SBS");
            System.out.println("1.KBS 2.MBC 3.SBS");dasdasㅇㅁㄴㅇㅁ
            System.out.print("select: ");dasdas
            int selecteChannel = scanner.nextInt();
            selecteProduct.changeChannel(selecteChannel);
            
        } else if (productChoice == 2) {dasdsadas
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
