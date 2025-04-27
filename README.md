interface Shapearea{
     void Area();
}
class Triangle implements Shapearea{
    public void Area(){
        double x=2.0f;
        double y=3.0f;
        double area=0.5*x*y;
        System.out.println("area of Triangle:"+area);
    }
}
class  Rectriangle implements Shapearea{
    public void Area(){
        int x=2;
        int y=3;
        int area=x*y;
        System.out.println("area of Rectriangle:"+area);
    }
} 
class Main {
    public static void main(String[] args) {
    Triangle A=new Triangle();
    A.Area();
    Rectriangle B=new Rectriangle();
    B.Area();
    }
}
