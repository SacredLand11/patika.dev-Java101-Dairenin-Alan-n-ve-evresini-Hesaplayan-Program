# patika.dev-Java101-Dairenin-Alanin-ve cevresini-Hesaplayan-Program
Yarıçapı r, merkez açısının ölçüsü 𝛼 olan daire diliminin alanı bulan programı yazınız.

## Code
public class Giris
{
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        double radius = s.nextDouble();
        double alpha = s.nextDouble();
        double perimeter = 2*3.14*radius*alpha/360;
        double area = 3.14*radius*radius*alpha/360;
        System.out.println(perimeter);
        System.out.println(area);
    }
}
