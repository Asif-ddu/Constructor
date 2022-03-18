public class Student {
    int no;
    String name;
    Student()
    {
        no = 97;
        name = "Asif";
    }
    Student(int n, String s)
    {
        no = n;
        name = s;
    }
    public static void main (String [] args)
    {
        Student S1 = new Student();
        Student S2 = new Student(98,"Addu");
        System.out.println(S1.no);
        System.out.println(S1.name);
        System.out.println(S2.no);
        System.out.println(S2.name);
    }
}
